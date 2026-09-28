# Internal Audit Report — Xuanbao Phase 2 (2026-09-28)

## 状态说明
- 18:05 定时任务触发了（cron 已按 --delete-after-run 自删），但 system-event 模式未真正唤醒主会话执行（已知限制，2026-09-21 记录过）。用户 19:18 询问时开始实际执行。

## A. 数据站 (data-xuanbao) 审计

### 规模
- 89 个 markdown 页，约 51,400 词，10 个主题分区：
  activated-carbon 15 | scr-denox 15 | voc-engineering 13 | voc-catalysts 11 |
  co-oxidation 9 | molecular-sieves 9 | compliance 5 | testing 5 | methodology 4 | water-purification 2

### 通过项（无需改动）
- [x] 所有页面有 frontmatter（title/description 齐全）
- [x] 无 pages.dev 残留引用
- [x] site_url = https://data.xuanbaoenvironment.com（mkdocs.yml）
- [x] 无内部断链（docs 内相对链接全部有效）
- [x] 无重复 title
- [x] Schema 已有：Organization + WebSite + WebPage/TechArticle + BreadcrumbList + CollectionPage（overrides/main.html）
- [x] 无消费炭/BBQ/水烟炭内容（主题边界干净）
- [x] 营销套话基本干净（grep 命中多为 Tailwind CSS 类名 leading-* 或 "leading to" 短语，非营销腔）
- [x] Data Classification 页面已存在且完整（7 类数据分类，与 Prompt 1 §3 完全对应）
- [x] 工程决策页已有：plate-vs-honeycomb、rco-vs-rto、adsorption-vs-catalytic-oxidation、selection 系列等
- [x] 数据站→主站内链 289 处

### 问题清单（需修复）
1. **P0 — CO 案例页缺第一方现场数据**：co-sintering-machine.md 和 co-waste-incineration.md 两篇案例页正文没有 1499→18 ppm / 11224.2→16.2 mg/Nm³ 数据（数据只存在于 methodology/data-classification.md 例子和主站 cases.ts）。Prompt 1 §9 / Prompt 2 §6 要求案例页带 Evidence 结构。
2. **P1 — 孤儿页面约 20 个**（nav 可达但内容层无入链）：
   - testing: flue-gas-sampling, lab-characterization-methods
   - activated-carbon: raw-materials, honeycomb-vs-columnar, humidity-temperature, ctc-methylene-blue, impregnated
   - compliance: eu-ied-bref, china-ultra-low-emission, compliance-reporting-audit
   - methodology: technical-terms
   - voc-catalysts: printing-industry, pt-vs-pt-pd, precious-vs-non-precious, lifecycle, coating-industry, space-velocity-design, deactivation
   - scr-denox: flow-distribution-cfd, low-temperature-catalyst（+可能更多）
3. **P1 — 污染物实体层缺失**：无 NOx/CO/VOC/苯系物/甲醛 实体页。Prompt 1 §5 要求"仅当有足够内容时创建"。站点现有内容可支撑：NOx（scr-denox 15 页）、CO（co-oxidation 9 页）、VOC（voc-* 24 页）。判断：可建 3-5 个污染物聚合页（NOx/CO/VOC/苯系物+甲醛），内容以聚合现有链接+核心事实为主，不新增编造内容。
4. **P2 — Key Engineering Point 缺失**：Prompt 2 §8 要求核心技术页加 1-3 句工程结论。需给 section index 页 + 核心页加。
5. **P2 — 主站→数据站内链不对称**：主站仅 24 处链接到数据站，数据站 289 处到主站。需在主站产品/材料/应用页增加指向数据站深度文章的链接。

## B. 主站 (xuanbao-astro) 审计

### 规模
- 36 个 astro 页面 + data 文件（cases.ts 3 案例、products.ts 15 产品、solutions.ts、industries.ts、details.ts）
- 68 页构建输出

### 通过项
- [x] 构建 0 错误（68 页）
- [x] 第一方案例数据齐全：sintering 1499→18 ppm（2022-08-23）、medical waste 11224.2→16.2 mg/Nm³（2023-03-20）、3 个案例
- [x] canonical/OG/sitemap 已统一到 xuanbaoenvironment.com
- [x] JSON-LD：breadcrumb + product + faq 数组结构正常

### 问题清单
1. **P2 — 主站→数据站链接少（24 处）**：产品页应链到数据站对应材料/技术深度页。
2. **P2 — 营销套话 grep 命中多为 CSS 类名（leading-tighter 等）**，非正文；正文抽查未发现 "best supplier/advanced technology" 级别套话。低优先级。

## C. 两个 prompt 的执行计划（当前轮次）
1. P0: CO 案例页补充第一方现场数据 + Evidence 结构（数据全部来自已公开的 cases.ts / data-classification.md，不新增编造）
2. P1: 孤儿页面内链修复（在 section index 页的 Related pages 加链接）
3. P1: 污染物实体层 — NOx/CO/VOC 三个聚合页（聚合现有内容）
4. P2: 核心页 Key Engineering Point
5. P2: 主站→数据站内链补充
6. 最终：构建 + QA + 提交推送 + 完整报告
