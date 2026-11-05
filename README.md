# AGreateCompany

> Let's do something GREAT, which is MEANINGFUL, to society, to humankind.

我们选择的那件"有意义的事"：**让"发现"发生的速度提升一个数量级，并让这个过程对所有人可见、可核验、可复现。**

为此我们不做一个通用的 AI 助手，而是做**证据引擎**——一层把"一句话"变成"一张带出处、带冲突、带边界的证据卡"的基础设施，然后以学术工作台、产业研发情报、开放 API 三种形态交付。

---

## 文档地图

| 文件 | 内容 | 谁该读 |
|---|---|---|
| [`docs/00-thesis.md`](docs/00-thesis.md) | 使命、五个信念、明确不做的事、北极星指标与反指标、工程原则 | 所有人（10 分钟） |
| [`docs/01-product-directions.md`](docs/01-product-directions.md) | 六个候选方向的评分与取舍、四层产品组合、三个产品的用户/JTBD/MVP/定价/成功判据 | 产品、设计、BD |
| [`docs/02-technical-roadmap.md`](docs/02-technical-roadmap.md) | 五个技术论点、分层架构、Claim Card 全链路、选型表、数据战略、评测体系、Agent 运行时、安全合规、成本模型 | 工程 |
| [`docs/03-delivery-plan.md`](docs/03-delivery-plan.md) | 8 个季度的主题与里程碑、9 个指标看板、预算结构、Kill Review 机制、防扩散的不做清单 | 全员 |
| [`docs/04-risks-and-open-questions.md`](docs/04-risks-and-open-questions.md) | 风险登记册、伦理边界（生物安全/科研诚信/数据）、10 个待验证假设、6 个需要创始人拍板的决定 | 创始人、法务、合规 |
| [`docs/overview.html`](docs/overview.html) | 一页纸可视化：使命 → 产品组合 → 技术底座 → 时间线 → 指标 | 对外沟通、招聘、投资人 |

建议阅读顺序：`overview.html`（建立全局印象）→ `00` → `01` → `02` → `03` → `04`。

---

## 一页纸版本

**主张**：科学研究的瓶颈已从"产生想法"转移到"验证想法"。所以我们卖的不是答案，是答案的可检验性。

**产品**：一套证据引擎，三个出口——学术版 Hypothesis Workbench、产业版 R&D Intelligence、公共品 Open Evidence Graph。

**技术**：断言分解 → 逐条证据检索 → 独立验证器判定 → 冲突聚类 → 置信校准。生成模型不参与判定自己的输出。

**指标**：每周被采纳的**可核验**假设数。配五个反指标防止自欺。

**纪律**：前 18 个月只做 1–2 个领域；定制只做配置不做分支；版权、生物安全、科研诚信三条线一条不越。

---

## 参与方式

- 有领域背景（生命科学 / 材料 / 化学 / 医学信息学）？我们最缺的是能判断"这条证据到底靠不靠谱"的人。
- 觉得某个判断错了？欢迎直接开 Issue 反驳 `00-thesis.md` 里的 B1–B5。**这套文档的价值不在于它正确，而在于它足够具体，以至于能被证伪。**
