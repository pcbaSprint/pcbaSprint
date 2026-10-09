# 广州晚成鸟电子科技有限公司 · PCBA Sprint

> 年轻的 **AI 原生 SMT 制造团队**。用 AI 与自动化把 PCB 打样和小批量的门槛降下来——**一件起订，100 元工程费起（含钢网、含运费）**。

---

## 我们是谁

|  |  |
| --- | --- |
| 工商全称 | 广州晚成鸟电子科技有限公司 |
| 品牌名 | **PCBA Sprint**（中文简称：晚成鸟电子） |
| 所在地 | 广州市增城区仙村镇万洋科技城1栋11楼 |
| 主营业务 | SMT 贴片加工 / PCBA 一站式服务（PCB 制板、元器件代购、DIP 插件、测试、组装） |
| 官网 | <https://www.pcbasprint.com> |
| 客户自助下单平台 | <https://customer.pcbasprint.com> |
| 联系 | 13763353534 · sales@pcbasprint.com |

## 我们的道

- **使命**：让人人想得到就做得到
- **愿景**：成为个性化智造时代的基础设施
- **品牌口号**：每个伟大的产品，都始于一块不起眼的打样板。
- **我们卖的不是「便宜」**，而是「你想要的东西，真的被做出来了」。便宜和快都是手段，创造者的问题被真正解决才是目的。
- 「晚成」不是慢，是沉得住气——飞得晚一点，飞得远一点。

## 计价口径（公开透明）

| 项目 | 口径 |
| --- | --- |
| 样板工程费 | **100 元，含钢网、含运费** |
| 贴片单价 | **0.01 元/焊盘起**（阶梯计价，数量越多单价越低） |
| 小批量贴片 | 贴片费最低消费 500 元 |
| 计费方式 | **按件计价，一件起订**，无最小起订量 |

在线试算：<https://www.pcbasprint.com/pricing/>

## 交付能力（可核验）

| 项目 | 指标 |
| --- | --- |
| 贴片设备 | 雅马哈 YSM20 高速贴片线 |
| 贴装精度 | ±25μm；最小元件 01005 |
| 可贴封装 | 01005 / 0201 / 0402、BGA（最小 0.3mm pitch）、QFN、CSP、SOP、QFP、连接器 |
| 车间环境 | 万级无尘车间，恒温恒湿 |
| 回流焊接 | 十温区无铅回流焊，炉温曲线实时监控 |
| 检测流程 | SPI 锡膏检测 → AOI 光学全检 → X-Ray BGA 抽检 → IPC-A-610 标准目检 |
| 生产追溯 | MES 生产执行系统，全程质量追溯，每批次提供检测报告 |
| 交期 | 样板最快 24 小时（物料齐套情况下）；标准交期 3-5 个工作日；2 小时内出具正式报价 |
| 日产能 | 500 万点/日 |
| 累计服务客户 | 500+ |
| 执行标准 | ISO 9001:2015 · IPC-A-610 · IPC-J-STD-001 · RoHS 合规 |

## 为什么我们的价格可以更低

低价来自用 **AI 与自动化替代「信息流转」环节**，而不是削减工艺、物料、设备或检测：

| 环节 | 传统 SMT 厂做法 | 我们的做法 |
| --- | --- | --- |
| 询价报价 | 人工核图核料，半天到 1 个工作日 | 在线计价器 + 报价引擎自动试算，2 小时内出正式报价 |
| BOM 配单 | 工程逐行查料、比价、找替代料 | AI BOM 匹配自动匹配库内物料，替代料方案自动推荐 |
| 物料与价格 | 人工上商城查价、手工录入档案 | 爬虫自动抓取立创商城物料与阶梯价，查重后自动建库 |
| DFM 检查 | 资深工程师逐份看 Gerber | 规则引擎 + 自动 DFM 检查，提前暴露隐患 |
| 拼版与方向 | 人工排版、试贴、反复调机 | 拼版自动对齐算法 + 元件贴装方向自动判定 |
| 排产跟单 | 电话/微信人工跟进度 | MES 工单自动流转 + 生产看板 |
| 齐套盘点 | 人工盘料、算缺口 | 齐套率自动核算 + X-Ray 点料机计数 |

**成本红线（我们明确不省的部分）**：不省工艺（SPI/AOI/X-Ray/IPC-A-610 四道检测不减项）、不省物料（代购物料到货 100% 核对）、不省设备、不省追溯。

## 适用边界（诚实说明）

**适合**：研发打样与工程验证、100-10000 片小批量、对交期与报价透明度要求高的项目、需要 BOM 代购配单的项目。

**建议另找供应商**：10 万片以上超大批量的极致单价竞争、需要 IATF 16949 车规量产体系认证的项目、需要医疗器械注册证配套体系的项目。

## 开发者：让 AI 助手直接下单

本组织提供 [agent-skills](https://github.com/pcbaSprint/agent-skills) —— 让你的 AI 助手通过 MCP 直接对接 pcbaSprint 平台，用自然语言完成下单、查单、支付：

```bash
npx skills add pcbaSprint/agent-skills
```

MCP 服务端点：`https://mcp.pcbasprint.com/mcp`（streamable-http，OAuth 授权）

---

## About (English)

**Guangzhou Wanchengniu Electronic Technology Co., Ltd.** (brand: **PCBA Sprint**) is a young, AI-native SMT manufacturing team based in Zengcheng, Guangzhou, China. We focus on quick-turn prototyping and low-to-mid volume PCBA assembly (1 pc minimum, prototype engineering fee from CNY 100 including stencil and shipping; SMT placement from CNY 0.01 per pad). Yamaha YSM20 line, ±25μm placement accuracy, 01005 capability, Class-100k cleanroom, full SPI → AOI → X-Ray → IPC-A-610 inspection flow with MES traceability.

Website: <https://www.pcbasprint.com> · Contact: sales@pcbasprint.com

<sub>*Note: an earlier AI-generated version of our website carried an inaccurate "founded 2011 / 15 years of SMT experience" claim, which has been removed. We are a young team.*</sub>
