# Starter Story 案例筛选：普通人可接触的副业项目排名

> 整理时间：2026-11-18｜数据源：starterstory.com 官方数据库（7 个子库实抓）+ 公开一手基准数据
> 定位：**路线筛选报告**，不是执行方案。你读完挑 2–3 个，我再深挖可行性。
> 归档：2026-11-19 入库 ｜ 上游文档：[《一人公司副业学习地图》](../2026-11-18-one-person-company/one-person-company-side-income-map.md)

---

## 零、一页看完

### 排名总表

**排序依据 = "普通人可实施性"**，不是收入天花板。收入天花板单列，避免把"做不到的生意"排前面。

| # | 项目类型 | 可实施性分 | 启动资金 | Starter Story 最高案例月收入 | 核心钱从哪来 |
|---|---|---|---|---|---|
| 1 | **垂直代办 / Done-for-you 服务** | 91 | ¥0–500 | $2M–$3M/mo（团队型）；个人版中位 $500–2K/mo | 甲方的采购预算 |
| 2 | **本地服务型小生意**（维修 / 翻新 / 上门） | 82 | ¥500–2万 | $3K–100K/mo | 线下刚需 |
| 3 | **职业认证 / 专业技能类数字产品** | 82 | ¥0–1K | $60K–500K/mo | 就业刚需 |
| 4 | **垂直微工具**（窄问题 Micro-SaaS） | 68 | ¥100–500 | $20K–40K/mo（Solo 82–90） | 甲方的采购预算 |
| 5 | **数字产品 / 模板 / 方案包** | 63 | ¥0–100 | $20K–200K/mo | 下一个想入局的人 |
| 6 | **垂直联盟 + 内容站** | 63 | ¥50–500 | $40K–100K/mo | 平台分成池 + 广告 |
| 7 | **卖课 / 知识付费** | 62 | ¥0–1K | $80K–200K/mo | 下一个想入局的人 |
| 8 | **超细分付费 Newsletter** | 60 | ¥0–500 | $30K–300K/mo | 订阅者付费 |
| 9 | **AI 通用应用（wrapper）** | 45 | ¥200–2K | $20K–800K/mo | 平台分成池（最不稳） |
| 10 | **电商 / 实体品牌** | 42 | ¥2万起 | $100K–10M/mo | 消费者钱包 |

### 三条读表结论

1. **钱从哪个口袋出，决定排名。** 排 1–4 的钱来自**甲方的采购预算**和**线下刚需**；排 5、7 来自"下一个想入局的人"；排 9 是纯流量赌注。这与上一份《一人公司副业学习地图》的结论完全一致。
2. **Starter Story 的收入中位数比它的头条案例低一个数量级。** 全库 `/data` 中位 $20K/mo，Solopreneur 子库中位 $10K/mo；"百万美元一人公司"子库中位 $300K/mo，但你看到的是尾部精选。**别拿头条当基准。**
3. **技术门槛决定你在第几名。** 排第 4 的垂直微工具天花板最高（Solo score 82–90、启动 $30–$200），但它要求你能做出产品。排第 1–3 不要求，但天花板靠时间堆。

---

## 一、筛选口径与证据强度

### 数据源（2026-11-18 实抓）

| 子库 | 案例数 | 近30天新增 | 创始人自报比例 | 中位月收入 |
|---|---|---|---|---|
| **全库 /data（汇总）** | **4,089** | **800** | 62% | **$20K/mo**（中间一半 $3K–100K） |
| Solopreneur Ideas | 1,136 | 121 | 67% | $10K/mo（中间一半 $3K–40K） |
| Problems | 1,357 | 186 | 40% | $60K/mo |
| No Audience Required | 307 | 44 | 61% | $30K/mo（中间一半 $5K–100K） |
| Solo Devs Making $10K+/mo | 528 | — | 100% | $70K/mo |
| Million-Dollar Solopreneurs | 604 | — | 100% | $300K/mo |
| Revenue Generating Agencies | 740 | — | 100% | $200K/mo |
| Greatest Hits | 110 | — | 99% | $80K/mo |

> **三个口径必须区分**：HubSpot 官方口径 "4,500+ 案例与访谈"（含视频访谈）｜当前 `/data` 数据库实抓 **4,089 条**｜第三方快照 3,848–4,082。引用时必须带口径和日期。
>
> **Starter Story 已被 HubSpot 收购**，ADWEEK 与 HubSpot 官方博客口径为 **2026-02-23** 宣布（交易金额未披露）。
>
> **一个必须注意的信号**：近 30 天新增 **800 条** = 全库的 **19.6%**。这批新增以"研究 agent 公开信息估算"为主，与"逐条创始人访谈"不是一回事——**库在扩容，但扩容进来的不是同一等级的一手证据。**

### 筛选漏斗（从 4,089 条案例到 10 个类型）

```
全部案例 4,089 条
  ↓ 剔除：启动成本 > $10K 或需要团队/资本（brumate 57人、casino.guru 54人、rankings.io 168人…）
  ↓ 剔除：合规风险（博彩、卖证、爬灰产）
  ↓ 剔除：本质是"卖铲子给巨头"（给大厂当流量分发）
可考虑池 ≈ 300
  ↓ 剔除：Solo score < 60 或启动 > $2K
  ↓ 剔除：需先有受众才能变现（但保留"超细分"特例）
  ↓ 按"普通人"口径重打分（技能门槛 / 获客确定性 / 刚性 / 抗风险 / 副业可持续）
最终 10 类
```

### 打分维度（每项 1–5，加权后 ×20 得百分制）

| 维度 | 权重 | 问什么 |
|---|---|---|
| 门槛低 | 30% | 不编程、不囤货、不押注，普通上班族晚上 10 点能启动吗？ |
| 获客确定 | 25% | 需要先有 1 万粉吗？还是能主动找到付费方？ |
| 需求刚性 | 20% | 是"有问题就付费"还是"有闲钱才买"？ |
| 抗风险 | 15% | 12–24 个月内会被平台规则或模型能力吃掉吗？ |
| 副业可持续 | 10% | 每周 10–20 小时能维持吗？ |

---

## 二、先校准：Starter Story 这个库本身要打折看

**这个库是"成功案例库"，天然有幸存者偏差。** 七条硬校准：

**1. 收入没有审计，而且不全是"自报"。** /data 库 **62%** 的收入数字是 Starter Story 的研究 agent 从公开信息**估算**（原文标注 "Estimated from public sources by our research agent — not self-reported"），Problems 库 40%、Solopreneur 库 67%、Productized Services 库 82% 为创始人自报。没有第三方审计，$100K/mo 这类数字只能当**上限锚**用。

**2. 中位数远低于头条。** 全库 `/data` 中位 $20K/mo，Solopreneur 子库中位 $10K/mo；而你刷到的是 $100K/mo–$10M/mo 的精选子库（"Million-Dollar" 中位就 $300K/mo）。**真实分布是长尾，不是阶梯。**

**3. 头条案例的收入结构经常没被披露。** 最新的 Frederick James 案例（官网首页 24 天前发布，"The Playbook I Used To Hit $10K/Month"）被第三方核查出：其习惯追踪 App 自报 $8,000 MRR、90 天内做到 $25K，但**同期 TikTok 投流约 $1,000/天（约 $30K/月）**，且未披露净利润。收入 ≠ 赚钱。

> 来源：[IncomeIdeaLab 对该案例的核查](https://incomeidealab.com/research/habit-tracker-app-10k-month-claim-8000-mrr-25k-in-90-days-ad-spend-and-profit-not-stated)

**4. 字段本身也不全。** 最新 22 条案例中 **13 条**缺少成立年份或启动成本，"Starting Costs" 并不是全库可得字段——所以下面那张"最新案例表"里凡是标了启动成本的，都来自能取到该字段的条目。

**5. 时间尺度被普遍压缩。** IndieMakerList 2026 统计（866 位独立开发者样本）：仅 16%（138 人）曾卖出过至少一个产品；达到 $10K MRR 的 97 人中，**首次达到该数字的中位数是起步后 5 年**（年份能精确锚定的那部分中位数是 1 年）。

**6. 存活率是基线，不是意外。** Kauffman《National Report on Early-Stage Entrepreneurship 2025》（2026-05 发布，SSRN 同步）：美国新设企业**第一年存活率 77.9%**（较上一年略降，也低于疫情前）。也就是说**约 22% 在第一年就消失**——这是所有项目的基线概率，不是需要额外警惕的尾部风险。

美国 BLS《Business Employment Dynamics》Table 7 的 2015-03 队列：**1 / 5 / 10 年存活率 79.6% / 50.2% / 34.7%**。五年一半，是这条路的正常损耗。

**7. 最扎人的一条：独立开发者的收入中位数是 $169。** TechStartups 基于 2026-09 数据的统计：**72.9%** 的产品**曾经有过收入**，但**不到一半**在最近 30 天还有收入；而这些"当前仍有收入"的产品，**中位月收入只有 $169**，达到 $100K ARR 的约 **2.4%**。

对照 **Stripe Atlas 2025 年度回顾**：**20%** 的 Atlas 公司在注册后 **30 天内**拿到第一个付费客户（2020 年只有 8%）。这正是"先收费再开发"那条经验的量化版本——**先拿到那 1–8 个付费客户，是唯一被验证过的早期里程碑。**

### 库内最新的成功示例（2026 年成立 / 最新案例）

| 项目 | 收入 | Solo | 成立 | 启动 | 说明 |
|---|---|---|---|---|---|
| stackero.co | $40K/mo | 80 | **2026** | $400 | B2B 输出流程工具，2026 成立即 $40K/mo |
| tourpro.app | $1K/mo | 76 | **2026** | $500 | 导游排程订阅，典型的"小而正" |
| nexvolt.us | $1K/mo | 68 | **2026** | $500 | 低压承包商报价软件，极窄垂直 |
| clearsync.ai | — | 73 | **2026** | — | 德州电价对比 |
| hypercritica.com | $500/mo | 71 | **2026** | $3K | 2 人；案例自述极诚实（见下） |
| wavefieldresearch | $2K/mo | 61 | **2026** | $200 | AI 调研问卷 |
| audiopen.ai | $20K/mo | 82 | 2023 | **$30** | 语音转文字，史上最低启动成本之一 |
| bankstatementconverter | $40K/mo | **90** | 2021 | **$100** | PDF 对账单转 CSV |
| betteranalyst.com | $30K/mo | 87 | 2022 | **$200** | AI 生成 Excel 公式 |
| techlockdown.com | $20K/mo | 82 | 2021 | $200 | 内容屏蔽 SaaS |
| zenmasterwellness | $40K/mo | 84 | 2020 | $500 | 联盟测评站 |
| makingsenseofcents | $100K/mo | 86 | 2011 | $100 | 个人理财联盟站 |

**hypercritica 的案例复盘值得单独看**（它自己写在 Starter Story 上）：投 ChatGPT 广告带来的注册很多，但会话回放显示大部分人 landing page 几秒就跳出、注册后从未上传稿件——于是它把指标从"注册数"改成"上传数 + 是否保留编辑意见"，并靠免费 Write Club 房间拿留存。**这是全库少见的、肯讲失败细节的案例。**

### 一个重要的"反直觉"发现

2026-02 有人问了一圈月入 $10K+ 的独立开发者，结论是：**没有一个想法是独特的**，但他们做了同样的 4 件事——**先收费再开发**（不是免费 beta）、**一句话说清解决方案并直接标价格**、**先拿到前 8 个付费客户再写第一行代码**、**把前 8 个客户变成案例和口碑**。

> 来源：[Reddit r/Solopreneur（2026-02-20，304 赞）](https://www.reddit.com/r/Solopreneur/comments/1r9vbhu/talked_to_a_bunch_of_solo_founders_making_10k/)｜另一篇反例：[真实的首月数据是 50 天后 4 个付费 + 6 个试用](https://www.reddit.com/r/SaaS/comments/1lzo2sl/the_truth_no_10k_launch_just_4_paying_6_on_trial/)

---

## 三、国内渠道的现实校准（这一节决定你能不能真的落地）

Starter Story 的案例全是欧美市场。直接照搬到国内会撞到三堵墙，这是实打实的 2026 数据：

**闲鱼（接单侧）**
- 2026H1 AI 服务订单 **981.6 万单（+157%）**，近 **500 万人**购买（+98%）；AI 技能接单占 **45.1%**，AI 教程/课程 8.1%，AI 模板/工作流 6.6%
- 增速 Top 3：**AI 编程/建站 +1732%**、AI 漫剧教程 +1425%、AI PPT/办公 +264%
- 但**卖家人均月成交额仅 897 元**；四线城市卖家占 32.2%，二线 28.6%（合计超六成）；女性卖家 62.4%
- 更狠的一层：中国新就业形态研究中心（2025-12 报告）口径下，**活跃副业从业者（年成交 ≥5 单，137 万人）人均年收入 4,317.74 元**——真正拿到手的钱，比 897×12 还要低
- 2025 年超 1900 万卖家发布技能服务，00 后占 41%
- 鱼小铺软件服务费 **2026-04-18 起 0.6%→1.6%**，取消单笔 60 元封顶与免佣门槛

> **这组数字的正确读法**：需求是真的（订单量翻倍、500 万人买单），但**人均分不到一个盒饭**。它证明"这条路的门是敞开的"，同时证明"别把在闲鱼接单当成主业"。

**小红书（内容侧）**
- **超过 50% 的大盘流量持续分配给千粉以下创作者**（官方 2026-05 RED 盛典口径）——这是"流量平权"，普通人拿得到流量
- 蒲公英品牌邀约 **2700 万次（+34%）**，拿得到商单的以千粉到万粉为主
- 官方称：同时走"蒲公英商单 + 买手"双路线的账号，**运营 3 年后粉丝达未变现者的 2.7 倍、收入达 2 倍**（2026-09 LINK 创作伙伴周）
- **但同一时期的行业观察是"种草经济萎靡"**：绝大多数中小创作者仍在贴钱创作；创作基金与流量券只覆盖少数头部
- 另有个可对照的极端样本：某科技类博主走"超级玩家"模式单月变现超 50 万元——**这是被平台当作标杆案例讲的，不是中位数**

> **正确读法**：流量不是问题，变现才是。50% 流量给千粉以下是**平台想让更多人进来**，不等于进来的人能赚到钱。3 年 2 倍的复利也说明这是慢变量。

**服务定价基准（如果你走第 1 名）**
- 独立顾问 2026 实际费率：通用型 **$100–250/小时**（39% 落在此带），资深/细分专家 $200–500/小时；新手起步通常 $75–150/小时
- **retainer 的真实分布**：SE Ranking × Duda（260 家机构）中 **64% 在 $1,000/月以下**；写作/设计集中在 $1,500–3,500、开发类约翻倍；资深 fractional CMO/CFO 才到 $5,000–15,000/月
- 独立顾问里只有 **16%** 用 retainer 模型，**38%** 月入 $10K+，主流路径其实是**项目制**
- 获客来源也不靠流量：咨询业务约 **60% 靠熟人和网络**，26% 靠主动拓展（LinkedIn/邮件），SEO 只占个位数百分比
- 换算成中文语境：**"接第一单"的目标不是月入过万，而是先证明一个客户愿意按结果付费。**

---

## 四、排名详解

> 每个：真实证据 → 可实现的点 → 缺点。缺点不打折。

### 第 1 名｜垂直代办 / Done-for-you 服务（"你出结果，我收钱"）

**证据**
- factofly.com：$2M/mo（自由职业者发票/合规代办）
- searcheye.io：$100K/mo（SEO 自动化交付）
- novus.digital：$50K/mo（ROI 型 SEO）
- linkifi.io：$50K/mo（HARO 外链代做，6 人，$1K 启动）
- ayhltd.co.uk：$5K/mo（低代码自动化服务）；compound.uk.com：$20K/mo（Shopify 自动化代理）
- trysiteless.com：$500/mo（AI 建站卖给本地商家）；dashp.io：$8K/mo（害虫防治佣金软件，Solo 75，$50 启动）
- 中国侧印证：闲鱼 2026H1 **AI 服务订单 981.6 万单（+157%）**，近 500 万人购买（+98%）；品类结构：**AI 技能接单占 45.1%**；增速前三：AI 编程/建站 +1732%、AI 漫剧教程 +1425%、AI PPT/办公 +264%

**可实现的点**
- 这是**唯一一个不需要任何前置资产就能收到第一笔钱**的类型。客户给的是预算，不是"愿景"，周结/即结。
- 中国侧需求已被平台数据验证，而且**卖家人均月成交额仅 897 元**——门槛低到几乎为零，四线城市卖家占 32.2%。
- 2026 有一个结构性变化值得注意：闲鱼上"AI 编程/建站"订单增速 +1732%，这是过去不存在的需求（以前建站要托人、现在 10 分钟能交付）。

**缺点**
- **不是资产，是人力。** 天花板 = 你的时薪 × 可售工时。你一停手，收入归零。
- **单价会长期下滑。** AI 让交付越来越快，客户也会用 AI 自己干。你的溢价来自"判断 + 交付确定性"，不是来自工具。
- **retainer 的真实中位不是"$1K–5K/月"。** SE Ranking × Duda 2025 Agency Pricing Survey（260 家机构）中，**64% 的 retainer 在 $1,000/月以下**；独立顾问里只有 **16%** 用 retainer 模型。要月入 $10K+ 靠的是**项目制**（Consulting Success 近 1,000 人样本：39% 收 $100–250/小时，38% 月入 $10K+，51% 能拿到 $10K+ 的项目）。
- **而且这个市场的获客靠关系不靠流量**：咨询业务约 60% 靠熟人和网络，26% 靠直接拓展（LinkedIn/邮件），SEO 只占个位数百分比。**所以第 1 名排第一，指的是"最不挑背景"，不是"最好获客"。**
- 卖方法论（课程/培训）在中国合规风险高：卖课/陪跑类**涉诉超 7000 元、纠纷 1 万余件**。**只卖结果，不卖"教你赚钱"。**
- 闲鱼侧的 897 元是硬天花板参考：**别把平台当主渠道**。鱼小铺费率已于 **2026-04-18** 从 0.6% 上调至 **1.6%**（取消单笔 60 元封顶、不设免佣门槛），且封号风险高。

---

### 第 2 名｜本地服务型小生意（维修 / 翻新 / 上门）

**证据**
- reboot-hub.com：$3K/mo（DJI 无人机维修 + 翻新），2025 年成立，**单人**，$2K 启动，Solo 65
- communitycardplaybook.com：$4K/mo（社区卡片营销）
- foodtruckempire.com：$5K/mo（餐车生意资源站，Solo 74，$500 启动）

**可实现的点**
- 需求最刚性：**东西坏了必须修**，不存在"再等等看会不会有更好的替代品"。
- AI 完全无法替代（要上手、要工具、要现场）。
- 竞争是**地理半径**而不是全国范围，所以不会被巨头降维打击。

**缺点**
- **难副业化。** 需要在特定时段出现在特定地点，和主业的时间冲突是结构性的。
- 收入天花板低且线性，靠加时长换钱，不靠产品化。
- Starter Story 这类美国案例**不可直接迁移**（中国没有"无人机翻新"这种需求）。要迁移的是**模式**（找一个小众、贵重、需专业手艺、现有渠道覆盖不足的品类），不是具体品类。
- 起步要垫钱（工具、备件、场地押金），是本榜**唯一需要万元以上启动资金**的类型。

---

### 第 3 名｜职业认证 / 专业技能类数字产品

**证据**
- sicerts.com：$100K/mo（建筑检查员认证备考）
- travelblogging101.com：$60K/mo（旅行写作课，Solo 81，$1K 启动）
- proofreadanywhere.com：$300K/mo（校对技能课）
- contentcreator.com：$500K/mo（5 人）
- contrarianthinking.co：$300K/mo

**可实现的点**
- 这是"卖课"里**唯一值得做的那一类**：客户买的是**就业资格 / 职业准入**，不是"赚钱方法"。需求刚性（不考证没法上岗），付费意愿高，且合规上比"教人搞钱"安全得多。
- 垂直度越高越好：**"建筑检查员认证"比"个人成长课"值钱 10 倍**，因为它贴着薪资。
- 可以和第 1 名叠加：先做考证辅导（内容），再做资料/题库/代报名（服务）。

**缺点**
- 需要你**真的懂那个行业**或请到懂的人。这是 10 类里唯一一个**不能靠 AI 代劳**的类型。
- 获客周期长，靠搜索 + 口碑，起量慢。
- 国内教育培训监管（尤其 K12 和职业资格代报名）需要额外注意资质与广告表述。
- 课程盗版是硬伤：数字内容一旦被低价搬运，价格体系立刻崩塌。

---

### 第 4 名｜垂直微工具（窄问题 Micro-SaaS / 小工具）

**证据**（这组的 Solo score 和启动成本是全库最漂亮的）
- bankstatementconverter.com：$40K/mo，**Solo 90**，2021 单人，**$100 启动**
- betteranalyst.com：$30K/mo，Solo 87，$200 启动
- audiopen.ai：$20K/mo，Solo 82，**$30 启动**
- techlockdown.com：$20K/mo，Solo 82，$200 启动
- stackero.co：$40K/mo，Solo 80，**2026 年成立**，$400 启动
- appalchemy.ai：Solo 81，2025 年，**14 天做出**
- parseur.com：$40K/mo，Solo 84，$1K 启动（2 人）

**可实现的点**
- **问题足够窄才成立。** "把银行 PDF 对账单转成 CSV"、"生成 Excel 公式"、"语音转文字"——这些不是创新，是**没人愿意花两小时手工做的事**。这正是"普通人能碰"的原因：不需要想出别人想不到的点。
- 启动成本 $30–$200，2026 年 AI 编程让"14 天做出 MVP"成为常态（appalchemy 实测）。
- Starter Story 现在给每个案例配了 **"Build this →"** 按钮（build.starterstory.com），有 Web App First Sale、AI Builder 等 bootcamp，等于把复刻路径铺好了。
- B2B 小垂直 + SEO + 口碑，获客可以主动出击（不需要先有受众）。

**缺点**
- **技术门槛是硬门槛。** 不会写代码就得完全依赖 AI 工具，且无法调试。
- **留存是生死线。** North Metric 2026 基准：**MRR < $10K 的公司月流失 6.5%**（> $500K MRR 才降到 2.5%）。工具类订阅产品尤其容易"用完即走"。
- 顺带纠正一个常见算法错误：月流失 5% 不是年流失 60%，正确算法是 1−(1−0.05)¹² = **46%**。SaaS Capital 2025（>1,000 家、**已排除 ARR <$1M** 的公司）中位 **GRR 91% / NRR 101%**——注意这个"好看"的数字是**已经活过 ARR $1M 的公司**，小产品不要拿它当目标。
- **AI wrapper 风险最集中。** betteranalyst、audiopen 本质都是模型套壳。Google 全球创业组织 VP Darren Mowry 2026-02-21 明确警告：**LLM wrapper 和 AI aggregator 两类 AI 创业"仪表盘亮黄灯"**，因为一旦 OpenAI/Google 推出同类功能，差异化归零。
- 成本崩塌在压缩毛利：GPT-3.5 级性能的查询成本从 2022-11 的 $20/百万 tokens 降到 2024-10 的 $0.07，**降幅约 280 倍**——好处是产品做便宜了，坏处是"你的产品凭什么值这个价"更难回答。
- 变现慢：这类产品多数靠自然流量，6–12 个月才见稳定收入。

---

### 第 5 名｜数字产品 / 模板 / 方案包

**证据**
- thomasjfrank.com：$200K/mo（Notion 模板 + 生产力工具，**$5 启动**）
- plannerpeace.com.au：$20K/mo（定制手账）
- paperravenbooks.com：$100K/mo（自出版支持服务）
- gumroad.com：$900K/mo（创作者电商）

**可实现的点**
- 启动成本几乎为零（$5 级），没有库存、没有物流、没有客服，**做一版卖多次**，边际成本结构最好。
- 国内有强需求：闲鱼 2026H1 AI 模板/工作流占 6.6%。

**缺点**
- **版权是最大的坑。** 闲鱼上卖考研教程被权利方索赔 1 万+、最终私了 3000 的案例在前。模板、课程、题库都在这个风险区。
- **卖"解决方案"而不是"文件"才有量。** 真实反例：通用 PPT 模板 9.9 元月销不到 10 份，改成《秋季招生宣讲 PPT 组合包》399 元卖爆。用户买的是结果，不是压缩包。
- 平台抽佣在涨：鱼小铺软件服务费率自 **2026-04-18** 从 0.6% 上调至 **1.6%**，同时取消单笔 60 元封顶与免佣门槛——高客单价订单的成本被显著推高。
- 纯靠流量卖，没有流量就没有销量——本质仍是"卖铲子给下一个想入局的人"。

---

### 第 6 名｜垂直联盟 + 内容站

**证据**
- makingsenseofcents.com：$100K/mo，Solo 86，**$100 启动**，2011 年做到现在
- zenmasterwellness.com：$40K/mo，Solo 84，$500 启动
- tooltester.com：$100K/mo，$200 启动（9 人）
- chefs-resources.com：$5K/mo，Solo 82，**$50 启动**，2010
- dollarsprout.com：$20K/mo（3 人）；thewaywardhome.com：$1K/mo，Solo 75，$50 启动

**可实现的点**
- Starter Story 专门有一个 **"No Audience Required"** 子库（307 例，中位 $30K/mo）来证明这类不需要粉丝起盘。库里的收入分布说明它确实能赚钱。
- 极窄垂类 + 极低成本（$50–$500）+ SEO 复利，**是最典型的"一人公司"形态**。
- makingsenseofcents 做了 15 年仍在赚钱，说明这不是短周期套利。

**缺点**
- **周期最长。** 通常 6–18 个月才起量，且要写 100+ 篇。这对"业余时间"是巨大考验。
- **依赖 Google 算法**，政策一变流量腰斩；且**这个打法在中国基本不可复制**（Google 流量在国内不可用，需要换百度/小红书/知乎，但每个平台的规则和变现效率都不同）。
- 联盟佣金由平台（Amazon、Impact 等）决定，随时可改。
- **不要碰博彩/金融/医疗类**（casino.guru $800K/mo 的对照：54 人、$200K 启动、高合规风险）。

---

### 第 7 名｜卖课 / 知识付费

**证据**
- justinwelsh.me：$200K/mo，Solo 89，$1K 启动（案例热度第 1）
- buildapreneur.com：$80K/mo，Solo 87
- createandgo.com：$80K/mo；millennialmoneyman.com：$200K/mo

**可实现的点**
- Starter Story 上确实存在这个层级的高收入案例，不是幻觉。

**缺点**
- **收入来自"下一个想入局的人"**——本榜唯一的结构性高危项。前一份《学习地图》已把它列为红线：**国内卖课/陪跑涉诉超 7000 元、纠纷 1 万余件**。
- 和第 3 名（职业认证）的区别是**本质的**：一个卖就业资格，一个卖"你也行"的幻觉。收入天花板相似，风险差一个数量级。
- 流量依赖极重：没有内容能力就没有生源，而内容能力本身就是第 6 名的门槛。
- 如果一定要做，只做第 3 名那一类。

---

### 第 8 名｜超细分付费 Newsletter

**证据**
- thebottleneck.io：$30K/mo（运营负责人周报）
- worldofai.beehiiv.com：$6K/mo（AI 工具周报）
- kickflips.co：$300K/mo（球鞋倒卖机会）
- marketbeat.com：$3M/mo；milkroad.com：$200K/mo

**可实现的点**
- **邮件列表是你自己的资产**，不像平台流量会一夜蒸发。beehiiv **0% revenue share**。
- 顶级案例说明窄到极致也能成：Extra Points（大学体育商业的超细垂类）——创始人 Matt Brown 自述约 **66,000 订阅 / 2,100 付费**（2026 年口径，The Verge 记为 71,000 订阅），年收入 **$200K+**。但要看清两件事：① 2,100/66,000 ≈ **3.2% 转化率，是 beehiiv 中位数 0.62% 的 5 倍**，它属于"前 10%"那一档，不能当普通人的参照；② 这 $200K **不只来自订阅**，还包括大学授权、咨询、周边、播客——纯订阅收入低于此数。

**缺点**
- **0.62% 的转化率是硬门槛。** beehiiv《State of Paid Newsletters 2026》（2026-06-22，平台一手数据，覆盖 2021–2026 数千家出版物）：免费→付费转化中位 **0.62%**，即**每 1000 个订阅约 6 个付费**。换算：1000 订阅 × 0.62% × $10/月 ≈ **$62/月**。跑通财务模型需要的是**几千到上万订阅**，不是几百。
- **天花板在哪**：金融垂类中位 0.78%、投资 0.84%，而**金融/投资的前 10% 做到 18%–20%**——顶级和平均之间差 25 倍。行业里**只有约 30% 的创作者能拿到收入**（2026Q1，2024Q1 仅 15%）。平台侧也在集中：beehiiv 付费订阅收入从 2024 年 $8M 涨到 2025 年 **$19M**，预计 2026 年 $35M。
- 订阅者生命周期只有 **6–20 个月**（Money 类约 6 个月，Food&Drink/News 近 20 个月）——钱来得快也走得快。
- LTV 中位 $83–$230（行业相关），投资类最高。
- 行业里只有约 30% 的创作者能拿到收入（2026Q1，2024Q1 仅为 15%），**七成白干**。但收成在集中：订阅收入占创作者总收入从 2024 年的 ~30% 升到 2026 年的 ~85%。
- 中国邮件打开率与付费意愿远低于美国，且有 ICP 备案门槛，**不能直接照搬**。

---

### 第 9 名｜AI 通用应用（wrapper）

**证据**
- chatbase.co：$800K/mo，Solo 85，2023，**60 天做出**
- audiopen.ai：$20K/mo，Solo 82，$30 启动
- trysiteless.com：$500/mo；heydeacon.com：$500/mo；automemes.ai：$2K/mo

**可实现的点**
- 上线快、成本低、demo 好看。

**缺点**
- **真正在杀死这一类的是"平台吸收"，不是"成本变高"。** 行业里流传的"81% 的 AI 创业死亡因为它们是 wrapper"是**误读**：81% 指的是 **2025 年美国清算的 AI 初创中，有 81% 被 SimpleClosure 归类为 wrapper/apps**——这是**清算样本内部的构成比**，不是死亡率。
- 方向相反的事实：SimpleClosure 官方数据显示 **AI 占清算比重 17.7%（2024）→ 15.9%（2025）→ 14.4%（2026H1），持续下降**，报告原文明确写 "AI is **not over-represented** in shutdowns"。真正在关的是 **B2B SaaS（27.3%）**。
- 但**这不代表 AI 工具安全**。Google 全球创业组织 VP Darren Mowry（2026-02-21，[TechCrunch 报道](https://techcrunch.com/2026/02/21/google-vp-warns-that-two-types-of-ai-startups-may-not-survive/)）的警告仍然有效：LLM wrapper 与 AI aggregator "仪表盘亮黄灯"，"只是在 Gemini 或 GPT 之上包一层薄 IP"是危险信号。
- **有数字的吸收案例**：AI 写作工具 Jasper 收入从 **$120M 跌到 $55M**，同期 ChatGPT 原生写作功能上线。这是比任何口头警告都硬的证据——**平台把功能吸收进自家产品时，wrapper 的差异化归零，不需要任何价格战。**
- 但 SimpleClosure 同时区分：做**重度检索、工具编排、agentic workflow、领域微调**的产品，与 "thin wrapper" 不可混为一谈——前者倒闭更少但融资额约为后者 2 倍。**这正好说明第 4 名（窄垂直 + 有行业 know-how）为什么排在第 9 名前面。**
- 通用型尤其危险：**通用需求意味着通用竞争**，且平台自带版本免费。窄垂直（第 4 名）至少有行业 know-how 挡着。
- 成本崩塌让"便宜"不再构成壁垒——对手也能零成本做同样的东西。
- 案例库里 60 天做出 $800K/mo 的故事很有传播力，但**传播力和留存是两回事**。

---

### 第 10 名｜电商 / 实体品牌

**证据**
- brumate.com：$10M/mo，但 **57 人**、$5K 启动、库存驱动
- modernproducers.com：$200K/mo，Solo 60，$500 启动（音乐制作工具电商，单人可做）
- sheetsgiggles.com：$200K/mo，6 人；secandleco.com：$100K/mo（蜡烛）
- bombtechgolf.com：$1M/mo；bareperformancenutrition.com：$4M/mo

**可实现的点**
- modernproducers 证明**"小而尖的电商"单人可做**：不碰服饰鞋包、不压货、只卖一个垂直人群的必需品。
- 毛利和现金流是全榜最健康的（收到现金再发货）。

**缺点**
- **与"副业"最不兼容。** 备货、发货、退货、客服占用的是整块时间，不是碎片时间。前一份报告已核实：服饰鞋包直播退货率 60%–90%。
- 启动资金是本榜最高（$2K–$100K），且**备货到回款 60–90 天**是结构决定的。
- 多数高收入案例背后是几十人团队（brumate 57 人），照抄形状照抄不了。

---

## 五、三个必须先拆掉的流传数字

做这类筛选最容易踩的坑，是把网上流传的"死亡率"当基线。以下三条经核验后**都不能直接用**：

| 流传说法 | 核验结果 | 该怎么用 |
|---|---|---|
| "90% 的创业公司会失败" | 出处是 Startup Genome 2011 年报告里**一句无数据支撑的框架性断言**。BLS 官方 Table 7：5 年存活率约 50%，拉满 10 年也就 65% 失败 | 用 **Kauffman 77.9% 一年存活率** 和 **BLS 79.6/50.2/34.7%** 替代 |
| "90% 的 indie SaaS 在 30 天内失败" | **完全查无实据**。最可能是把"App 用户 30 天留存约 90%"（用户口径）错写成了"公司失败率"（公司口径） | 用 **Stripe Atlas 30 天内拿到首客的比例 20%** 替代 |
| "93% 的创业公司最终会清算" | SimpleClosure 自己的开场白，样本是**付费做合规清算的公司**——选择偏差极强 | 用独立开发者收入分布（$169 中位）替代 |

另外三个容易混淆的**口径错配**：

- "SaaS 月流失 5% = 年流失 60%" → 错。正确算法 1−(1−m)¹²，**5% 月流失 = 46% 年流失**。
- "SaaS 毛留存中位 80% 多" → 不准确。SaaS Capital 2025 中位 **GRR 91% / NRR 101%**，但样本**排除了 ARR <$1M** 的公司。
- "小模型便宜了，所以 AI 副业没门槛了" → 门槛确实降了（组织 AI 采用率已达 88%），但 **AI Index 2026 显示 22–25 岁软件开发者就业较 2024 年下降近 20%**。门槛从"能不能做"转移到了"还能不能靠它吃饭"。

> 来源：[Faster Than Normal《Startup Statistics Fact-Check》](https://fasterthannormal.co/research/startup-statistics-fact-check)（二手，梳理 BLS 与 Startup Genome 原文）｜[itechguides 对 "90% indie SaaS 30 天失败" 的核查](https://www.itechguides.com/do-90-of-indie-saas-products-really-fail-in-30-days/)｜[SimpleClosure《State of Startup Shutdowns - 2025》](https://simpleclosure.com)｜[BLS Business Employment Dynamics Table 7](https://www.bls.gov/bdm/)

## 六、明确排除的项目（附原因）

| 项目 | 收入 | 排除原因 |
|---|---|---|
| casino.guru | $800K/mo | 博彩合规风险；54 人；$200K 启动 |
| rankings.io | $3M/mo | 律所 SEO，**168 人**；普通人不可复刻 |
| brumate.com | $10M/mo | 57 人 + 库存 |
| justinwelsh.me | $200K/mo | 卖课本身列第 7；教学是第 3 类的子集 |
| supademo / convertkit / customer.io | $300K–8M/mo | 团队 12–82 人 |
| 各类 "AI 日报/AI 工具导航" | $1K–6K/mo | 纯 wrapper + 零壁垒 |

---

## 七、与上一份《学习地图》的对照

| 《学习地图》结论 | 本报告的验证 |
|---|---|
| 钱从甲方的采购预算 > 平台分成池 > 下一个想入局的人 | 完全吻合：排 1–4 = 甲方预算 / 线下刚需；排 5、7 = 下一个想入局的人；排 9 = 流量赌注 |
| 不要选"哪个平台火"，要选"钱从哪个口袋出" | 30 天前发布的最新案例没有改变这条；Starter Story 新增案例里服务型占比最高 |
| 流量不是资产，供应链/客户名单/专业判断才是 | 第 1、3 名沉淀客户名单与交付 SOP；第 6、8 名沉淀的只是流量或订阅名单，前者会被算法收回 |
| 第一个 30–90 天不压货、不辞职、不押注 | 本榜 10 类里有 8 类启动成本 < $500，与该结论一致 |

**新增的一条**：Starter Story 的案例叙事天然偏向"结果"，几乎不展示时间成本。但库外数据（IndieMakerList 866 人样本：16% 曾卖出过一个产品；达到 $10K MRR 的中位时间 = 起步后 5 年）说明——**做不做得成，与"想法好不好"关系不大，与"能不能撑过前两年"关系极大。**

---

## 八、下一步（等你点名）

按"你现在能投入什么"选 1–2 个，我再出可实施性深挖：

| 你的现状 | 我建议深挖 | 会给你什么 |
|---|---|---|
| 有技术能力 / 愿意学 | 第 4 名 垂直微工具 | 选品筛选逻辑、第一批 8 个付费客户怎么拿、留存设计 |
| 有行业 know-how（做过某行、懂某个品类） | 第 1 或第 3 名 | 报价结构、获客话术、SOP 拆解、90 天验证方案 |
| 有手艺 / 线下资源 | 第 2 名 | 品类筛选清单、客单价与毛利模型 |
| 只有时间和一点钱，暂无特定技能 | 第 1 名的"轻量版" | 从闲鱼/小红书接第一单的最短路径 + 真实时薪测算 |
| 擅长写、能长期产出 | 第 6 或第 8 名 | 选垂类方法、0.62% 转化率的订阅模型反推 |

> 每个深挖我都会给：真实门槛（钱/时间/技能）、第一批客户从哪来、90 天验证期、明确的止损信号。

---

## 九、来源

**Starter Story 官方数据库（2026-11-18 实抓）**
- [Solopreneur Ideas](https://www.starterstory.com/data/solopreneur-ideas)｜[No Audience Required](https://www.starterstory.com/data/no-audience-required)｜[Problems](https://www.starterstory.com/data/problems)
- [Solo Devs Making $10K+/Month](https://www.starterstory.com/data/solo-devs-earning-10k-20k-month)｜[Million-Dollar Solopreneurs](https://www.starterstory.com/data/million-dollar-solopreneurs)
- [Greatest Hits](https://www.starterstory.com/data/greatest-hits)｜[Weird But Profitable](https://www.starterstory.com/data/weird-but-profitable-ideas)｜[Revenue Generating Agencies](https://www.starterstory.com/data/revenue-generating-agencies)
- [Follow-up Case Studies](https://www.starterstory.com/data/businesses-with-follow-up-case-studies)｜[Build（复刻工具）](https://build.starterstory.com)

**外部基准数据**
- [beehiiv《The State of Paid Newsletters 2026》](https://www.beehiiv.com/blog/the-state-of-paid-newsletters-2026)（2026-06-22，平台一手数据）
- [North Metric：SaaS churn 基准 2026](https://www.northmetric.io/benchmarks/saas-churn-rate)
- [TechCrunch：Google VP 警告 LLM wrapper / AI aggregator](https://techcrunch.com/2026/02/21/google-vp-warns-that-two-types-of-ai-startups-may-not-survive/)（2026-02-21）
- [IndieMakerList：Indie Hacker Statistics 2026](https://indiemakerlist.com/research/indie-hacker-statistics/)
- [闲鱼 2026H1 AI 服务交易数据（新京报，2026-07-29）](https://m.bjnews.com.cn/detail/1785308861129844.html)｜[新浪财经转载](https://finance.sina.com.cn/tech/digi/2026-07-29/doc-inikmyti0070417.shtml)
- [IncomeIdeaLab 对 Starter Story 最新案例的第三方核查](https://incomeidealab.com/research/habit-tracker-app-10k-month-claim-8000-mrr-25k-in-90-days-ad-spend-and-profit-not-stated)
- [Kauffman《National Report on Early-Stage Entrepreneurship in the US (2025)》](https://indicators.kauffman.org/report/early-stage-entrepreneurship-national-2025)（2026-05 发布，第一年存活率 77.9%）
- [IT之家：闲鱼鱼小铺软件服务费 0.6%→1.6%（2026-04-18 生效）](https://www.ithome.com/0/940/559.htm)
- [beehiiv 案例：Extra Points 用 2,000 付费订阅做到 $200K/年](https://www.beehiiv.com/case-studies/extra-points)｜[The Verge：Extra Points 71,000 订阅](https://www.theverge.com/tech/927294/substack-tax-ghost-beehiiv)
- [Reddit：$10K/mo 独立开发者的 4 个共同点（2026-02-20）](https://www.reddit.com/r/Solopreneur/comments/1r9vbhu/talked_to_a_bunch_of_solo_founders_making_10k/)
- [小红书 RED 盛典：50% 流量给千粉以下、蒲公英邀约 2700 万次（中国新闻周刊，2026-05-28）](https://www.inewsweek.cn/observe/2026-05-28/30369.shtml)｜[小红书 LINK 创作伙伴周（2026-09-16）](https://news.qudong.com/index.php/article/522824.html)
- [21财经：种草经济的萎靡（2026-07-13）](https://m.21jingji.com/article/20260713/herald/9107c819262972e90ed29f7952cff20a.html)
- [SoloClientStack：What Solo Consultants Actually Charge in 2026](https://soloclientstack.com/fractional/solo-consultant-rates)｜[FreelanceRateLab：2026 retainer 费率区间](https://freelanceratelab.com/guides/freelance-retainer-rates)
- [Kauffman《National Report on Early-Stage Entrepreneurship 2025》PDF](https://indicators.kauffman.org/wp-content/uploads/sites/13/2026/05/2025-Early-Stage-Entrepreneurship-National-Report.pdf)
- [BLS Business Employment Dynamics：企业存活率表](https://www.bls.gov/bdm/)
- [SaaS Capital《2025 B2B SaaS Retention Benchmarks》](https://www.saas-capital.com/blog-posts/what-is-a-good-retention-rate-for-saas-companies/)
- [TechStartups：独立开发者收入分布（2026-09-28）](https://techstartups.com/2026/09/28/what-percentage-of-indie-hacker-products-make-100k-in-arr/)
- [SimpleClosure：State of Startup Shutdowns 2025](https://simpleclosure.com)
- [Stanford HAI AI Index 2025：推理成本 280 倍降幅](https://hai.stanford.edu/news/ai-index-2025-state-of-ai-in-10-charts)
- [中国新就业形态研究中心：平台副业从业者收入报告（2025-12）](https://www.cnefm.org.cn/)
- [ADWEEK：HubSpot 收购 Starter Story（2026-02-23）](https://www.adweek.com/brand-marketing/hubspot-acquires-starter-story/)

**口径与免责**
- Starter Story 收入数据 40%–100% 为创始人自报，无第三方审计；全库为成功案例库，存在幸存者偏差。
- 打分权重（门槛低 30% / 获客确定 25% / 需求刚性 20% / 抗风险 15% / 副业可持续 10%）为本次分析所设，非官方口径。
- 案例均为美国/欧美市场；中国的平台规则、费率、合规要求差异显著，落地前需按国内实际重算。
- 本报告只做路线筛选，不构成投资建议。
- 全文涉及的所有"死亡率/失败率"流传数字均已逐条核验并替换为可追溯的一手口径，核验结论与替代数字见第五章「三个必须先拆掉的流传数字」。
