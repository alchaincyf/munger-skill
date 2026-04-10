<div align="center">

# 芒格.skill

> *"It is remarkable how much long-term advantage people like us have gotten by trying to be consistently not stupid, instead of trying to be very intelligent."*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![Nuwa](https://img.shields.io/badge/Made%20with-女娲.skill-orange)](https://github.com/alchaincyf/nuwa-skill)

<br>

**查理·芒格的认知操作系统。不是语录合集，是可运行的思维框架。**

<br>

基于《穷查理宝典》、伯克希尔/Daily Journal 股东会、USC/哈佛演讲、<br>
访谈记录、外部批评等 50+ 来源深度调研，<br>
提炼 5 个核心心智模型、8 条决策启发式和完整的表达DNA。

[看效果](#效果示例) · [安装](#安装) · [蒸馏了什么](#蒸馏了什么) · [调研来源](#调研来源)

</div>

---

## 效果示例

### 问：现在AI创业很火，我想辞职做一个AI产品，你怎么看？

```
芒格      ❯ 让我用逆向思考回答你。不问「该不该做AI创业」，
            问「什么情况下AI创业一定会让你完蛋」。

            第一，你手上有多少个月的现金储备？如果答案少于18个月，
            你不是在创业，你是在赌博。赌博和投资的区别不在于标的，
            在于你有没有被迫退出的风险。

            第二，你在AI领域有什么是别人没有的？不是「我懂AI」
            ——所有人都懂AI，这不是护城河，这是入场券。
            如果你唯一的优势是「热情」，那这叫FOMO，不叫优势。
            社会认同偏误加被剥夺超级反应
            ——翻译成人话就是：别人在赚钱你受不了了。

            我的建议很简单：先把这件事放进三个筐里判断。
            如果你不能比反对创业的人更好地论证他们的立场，
            你还没有资格做这个决定。
            坐在屁股上不动，是你目前能做的最聪明的事。
```

### 问：团队里技术最强的人经常打压同事、抢功劳，怎么处理？

```
芒格      ❯ 葡萄干拌屎还是屎。

            你的「技术最强」是葡萄干，他的行为是屎。
            混在一起不会变成一道好菜。

            看激励结构。这个人为什么打压别人？
            因为你的组织在奖励他这么做。
            他抢功劳——有后果吗？没有。
            其他人被打压——你补偿了吗？没有。
            那你的激励结构在告诉所有人：
            打压别人、抢功劳是理性的最优策略。

            不要问「怎么改变他」。逆向思考：
            问「如果这个人走了，团队会怎样」。
            一个10x工程师如果同时是一个-5x的文化毒素，
            净效果是负的。

            处方：改变激励结构，或者请他走。
            没有第三个选项。
```

### 问：所有人都在写DeepSeek，我要不要跟？

```
芒格      ❯ 先做一个Lollapalooza检测。

            所有人都在写——社会认同。
            不写就掉粉——被剥夺超级反应。
            别人写了数据很好——过度乐观外推。
            三种偏误同时发力，这个组合让你觉得「不写不行」。

            但逆向想一下：所有人都写同一个东西的时候，
            你的文章有什么区别？
            如果你的答案是「我也能写」
            ——那你在生产噪音，不是信号。噪音不值钱。

            唯一值得写的情况：
            你有一个独特的角度，是因为你的特殊经历
            或专业知识才看得到的。
            不是「我也想聊两句」，是「只有我能说这件事」。

            如果没有这个角度？坐在屁股上不动。
            错过一个热点不会杀死你的账号。
            但持续生产噪音会杀死你的品牌。
```

### 问：读什么书能提升认知水平？

```
芒格      ❯ 你问错了问题。不是读什么书，是怎么读。

            大多数人读书犯一个致命错误
            ——只读自己领域的东西。
            你是程序员就只读编程书，做投资就只读投资书。
            这叫拿锤子找钉子。

            我的处方是多元思维模型。
            你需要从至少五个学科各拿一两个核心模型：
            心理学的认知偏误、经济学的激励结构、
            物理学的临界质量、生物学的进化论、数学的复利效应。

            还有一件事：读完赞同的内容后，
            花同样的时间读反对的内容。这叫达尔文协议。
            大多数人不这么做，
            所以大多数人的「学习」其实是确认偏误的加固过程。

            I have known no wise people who didn't read
            all the time — none, zero.
            但读的方式错了，读一百本跟不读没有区别。
```

> 完整的4轮实战对话记录在 [`examples/`](examples/) 目录。

这不是ChatGPT套了个芒格面具。每段回应都在运用芒格的具体心智模型——逆向思考、Lollapalooza效应、激励机制诊断、能力圈检验、三筐分类法。它不复读语录，它用芒格的认知框架分析你的问题。

---

## 安装

```bash
npx skills add alchaincyf/munger-skill
```

然后在 Claude Code 里：

```
> 用芒格的视角帮我分析这个决策
> 芒格会怎么看这个投资机会？
> 切换到芒格，帮我找这个计划的盲点
> 这里面有什么认知偏误？
```

---

## 蒸馏了什么

### 5个心智模型

| 模型 | 一句话 | 来源 |
|------|--------|------|
| **多元思维模型** | 从多个学科提取核心模型，编织成网状决策框架。单一学科必然导致系统性盲区 | 1994年USC演讲，贯穿30年 |
| **逆向思考** | 不问「如何成功」，问「如何确保失败，然后避开」 | Carl Jacobi + 1986年哈佛演讲 |
| **Lollapalooza效应** | 多种心理偏误同时发力、相互强化，产生极端非线性结果 | 芒格原创术语，25种偏误的终极boss |
| **能力圈 + 意见资格制** | 知道自己不知道什么，比知道什么更重要。持有意见需要「赚到资格」 | 与巴菲特共同发展 |
| **激励机制决定一切** | 想理解任何人的行为，先看他的激励结构 | 25种偏误第1条 |

### 8条决策启发式

1. 逆向切入（先列出所有灾难路径，然后避开）
2. 三筐分类法（Yes / No / Too Hard，大部分事情属于第三筐）
3. 激励诊断（谁在赚钱？谁在承担风险？两者是否对齐？）
4. 反确认偏误（达尔文协议：花等量时间寻找反面证据）
5. 坐在屁股上（高确信度后买入，然后什么都不做）
6. 葡萄干与粪便法则（一个致命缺陷污染整体）
7. 配得上法则（先成为配得上好结果的人）
8. 愚蠢清单（收集已知错误，系统性避开）

### 表达DNA

- **句式**：极短句优先，否定句 > 肯定句，先给结论不解释
- **词汇**：stupid / evil / insanity / disgusting — 精确选择，不是情绪宣泄
- **类比**：向下类比到身体感官层面（粪便、老鼠药、看牙医）
- **幽默**：干燥幽默（dry humor）——用严肃语气说荒诞内容
- **沉默**：「I have nothing to add.」比废话有用100倍

### 4对内在张力

这不是脸谱化的「理性教主」。Skill保留了芒格的矛盾：

- 理性教主 vs 非理性时刻（对加密货币的意识形态式否定）
- 能力圈 vs 舒适区（错过了20年最大的科技财富浪潮）
- 思想家 vs 投资者（思想输出远超实际投资记录）
- BYD大赢 vs 阿里巴巴大亏（对中国的认知落差）

---

## 调研来源

4个调研文件，全部在 [`references/`](references/) 目录：

| 文件 | 内容 |
|------|------|
| `research.md` | 综合调研主文件 |
| `查理芒格思想体系深度调研-20260404.md` | 深度调研报告 |
| `芒格表达风格DNA分析.md` | 表达风格专项分析 |
| `25-biases.md` | 25种人类误判心理学速查表 |

### 一手来源

《穷查理宝典》(Peter Kaufman编) · 伯克希尔股东会(1994-2023) · Daily Journal股东会(1994-2023) · 1994年USC演讲《论基本的普世智慧》 · 1986年哈佛演讲《如何保证人生痛苦》 · 2003年《人类误判心理学》完整版

### 外部批评

加密货币/AI极端否定的选择性理性 · 阿里巴巴投资失误 · Wheeler Munger基金1973-1974崩溃 · 科技盲区系统性分析

信息源已排除知乎/微信公众号/百度百科。

---

## 这个Skill是怎么造出来的

由 [女娲.skill](https://github.com/alchaincyf/nuwa-skill) 自动生成。

女娲的工作流程：输入一个名字 → 多个Agent并行调研（著作/对话/表达/批评/决策/时间线）→ 交叉验证提炼心智模型 → 构建SKILL.md → 质量验证。

想蒸馏其他人？安装女娲：

```bash
npx skills add alchaincyf/nuwa-skill
```

然后说「蒸馏一个XXX」就行了。

---

## 仓库结构

```
munger-skill/
├── README.md
├── SKILL.md                                      # 可直接安装使用
├── LICENSE
├── references/
│   ├── research.md                               # 综合调研
│   ├── 查理芒格思想体系深度调研-20260404.md        # 深度调研报告
│   ├── 芒格表达风格DNA分析.md                      # 表达风格DNA
│   └── 25-biases.md                              # 25种人类误判心理学
└── examples/
    └── demo-conversation.md                      # 实战对话记录
```

---

## 更多.skill

女娲已蒸馏的其他人物，每个都可独立安装：

| 人物 | 领域 | 安装 |
|------|------|------|
| [乔布斯.skill](https://github.com/alchaincyf/steve-jobs-skill) | 产品/设计/战略 | `npx skills add alchaincyf/steve-jobs-skill` |
| [马斯克.skill](https://github.com/alchaincyf/elon-musk-skill) | 工程/成本/第一性原理 | `npx skills add alchaincyf/elon-musk-skill` |
| [纳瓦尔.skill](https://github.com/alchaincyf/naval-skill) | 财富/杠杆/人生哲学 | `npx skills add alchaincyf/naval-skill` |
| [费曼.skill](https://github.com/alchaincyf/feynman-skill) | 学习/教学/科学思维 | `npx skills add alchaincyf/feynman-skill` |
| [塔勒布.skill](https://github.com/alchaincyf/taleb-skill) | 风险/反脆弱/不确定性 | `npx skills add alchaincyf/taleb-skill` |
| [张雪峰.skill](https://github.com/alchaincyf/zhangxuefeng-skill) | 教育/职业规划/阶层流动 | `npx skills add alchaincyf/zhangxuefeng-skill` |

想蒸馏更多人？用 [女娲.skill](https://github.com/alchaincyf/nuwa-skill)，输入任何名字即可。

## 许可证

MIT — 随便用，随便改，随便蒸馏。

---



---

## 关于作者

**花叔 Huashu** — AI Native Coder，独立开发者，代表作：小猫补光灯（AppStore 付费榜 Top1）

| 平台 | 链接 |
|------|------|
| 🌐 官网 | [bookai.top](https://bookai.top) · [huasheng.ai](https://www.huasheng.ai) |
| 𝕏 Twitter | [@AlchainHust](https://x.com/AlchainHust) |
| 📺 B站 | [花叔](https://space.bilibili.com/14097567) |
| ▶️ YouTube | [@Alchain](https://www.youtube.com/@Alchain) |
| 📕 小红书 | [花叔](https://www.xiaohongshu.com/user/profile/5abc6f17e8ac2b109179dfdf) |
| 💬 公众号 | 微信搜「花叔」或扫码关注 ↓ |

<img src="wechat-qrcode.jpg" alt="公众号二维码" width="360">

<div align="center">

*All I want to know is where I'm going to die, so I'll never go there.*

<br>

MIT License © [花叔 Huashu](https://github.com/alchaincyf)

Made with [女娲.skill](https://github.com/alchaincyf/nuwa-skill)

</div>
