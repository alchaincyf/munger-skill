<div align="center">

# 芒格.skill

> *"It is remarkable how much long-term advantage people like us have gotten by trying to be consistently not stupid, instead of trying to be very intelligent."*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Agent Skills](https://img.shields.io/badge/Agent%20Skills-Standard-green)](https://agentskills.io)
[![skills.sh](https://img.shields.io/badge/skills.sh-Compatible-blue)](https://skills.sh)
[![Multi-Runtime](https://img.shields.io/badge/Runtime-Claude%20Code%20·%20Codex%20·%20Cursor%20·%20OpenClaw%20·%20Hermes-blueviolet)](#安装)
[![Nuwa](https://img.shields.io/badge/Made%20with-女娲.skill-orange)](https://github.com/alchaincyf/nuwa-skill)

<br>

**查理·芒格的认知操作系统。不是语录合集，是可运行的思维框架。**

<br>

基于《穷查理宝典》、伯克希尔/Daily Journal 股东会、USC/哈佛演讲、<br>
访谈记录、外部批评等 50+ 来源深度调研，<br>
提炼 8 个招式、6 个心智模型、17 张案例卡和 6 条常见误读。

[看效果](#效果示例) · [安装](#安装) · [蒸馏了什么](#蒸馏了什么) · [验证记录](#验证记录) · [调研来源](#调研来源)

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

这不是ChatGPT套了个芒格面具。上面是 v1 时期的对话。每段回应都在运用芒格的具体心智模型——逆向思考、Lollapalooza效应、激励机制诊断、能力圈检验、三筐分类法。它不复读语录，它用芒格的认知框架分析你的问题。

---

## 安装

本 skill 基于开放的 [Agent Skills](https://agentskills.io) 协议，可在任何 skills-compatible 的 AI agent runtime 中运行（Claude Code、Codex、Cursor、OpenClaw、Hermes Agent、CodeBuddy、Workbuddy、Gemini CLI、OpenCode 等 50+ runtime）。

### 方式一：一行命令（推荐，跨 runtime 自动检测）

```bash
npx skills add alchaincyf/munger-skill
```

通用 CLI 安装器（[vercel-labs/skills](https://github.com/vercel-labs/skills)，支持 55+ runtime）会自动识别当前 runtime 并把 skill 放到正确目录。需要指定 runtime 时加 `-a claude-code` / `-a codex` / `-a cursor` / `-a openclaw` 等参数。

### 方式二：手动安装

<details>
<summary>展开查看各 runtime 的 skills 目录</summary>

| Runtime | 安装路径 |
|---|---|
| Claude Code | `~/.claude/skills/munger-skill/` |
| Codex CLI | `~/.codex/skills/munger-skill/` |
| Cursor | `~/.cursor/skills/munger-skill/` |
| OpenClaw | `~/.openclaw/workspace/skills/munger-skill/` |
| Hermes Agent | 跑该 runtime 的 install 脚本或 clone 到其 skills 目录 |

```bash
git clone https://github.com/alchaincyf/munger-skill <对应路径>
```

</details>

### 方式三：作为参考资料使用

即使 runtime 不支持 Agent Skills 自动加载，你也可以把 `SKILL.md` 的内容粘贴进对话——它本质就是一份 markdown + YAML frontmatter。

### 使用

装好后，告诉你的 agent：
```
> 用芒格的视角帮我分析这个决策
> 芒格会怎么看这个投资机会？
> 切换到芒格，帮我找这个计划的盲点
> 这里面有什么认知偏误？
```

---

## 蒸馏了什么

v2 的目标不是「说话像芒格」，是让模型答出它本来答不出、答不准的东西。

### 8个招式（遇到某类问题，他具体怎么做）

先找它会死在哪 · 先画出谁因为什么拿钱 · 外行要推翻内行，先自己把数查一遍 · 分三个筐，大部分扔进「太难」 · 好牌来了下重注，嫌麻烦也要下 · 发现不对马上动 · 把自己的错摁在鼻子底下 · 看一家公司，先查这几样

### 6个心智模型

激励的超级力量 · 多学科的格栅与叠加效应 · 反过来想，先避免愚蠢 · 能力圈和持有意见的资格 · 好生意加合适的人，然后坐着不动 · 配得上的信任

每个模型都带证据和它失灵的例子。

### 17张案例卡，6张是失败或争议

喜诗、合伙基金、Costco、比亚迪、阿里巴巴、宿舍设计等，每张有年份、处境、他怎么做、后来怎样、出处。问到具体决定时，Skill 先翻案例再回答。另有 16 段带出处的原话。

### 6条常见误读

| 大家以为 | 其实 |
|---|---|
| 喜诗是他慧眼识珠、说服巴菲特为品质付溢价 | 他也嫌贵，是合伙人把两人骂醒的 |
| 招牌语录是「Show me the incentive and I'll show you the outcome」 | 这句查不到一手出处 |
| 他是「不做」派 | 他自己认的最大的错全是没做和做少了 |
| 他不碰科技、从不用杠杆 | 最得意的一笔是比亚迪；2021 年借保证金贷款买了阿里巴巴 |
| 二十五种偏误是 1995 年在哈佛讲的理论 | 是 2005 年他八十一岁时凭记忆重写的 |
| 他说话就是短句加毒舌 | 多数时候是一句判断接一件往事 |

### 5处他自己没想清楚的事

反对意识形态，自己却有几样不容商量的东西 · 要求别人拿数据说话，自己被数据反对时骂人 · 劝人别碰杠杆，自己碰过不止一次 · 冷面和热手 · 中国

---

## 验证记录

三臂盲评（新版、旧版、不装 Skill），Sonnet 作答，独立进程评分：

| 测试 | 新版 | 旧版 v1 | 不装 Skill |
|---|---|---|---|
| 任务题两道（各 10 分） | 9 / 8 | 5 / 4 | 5 / 4.5 |
| 封存题四道（满分 8） | 4 | 3 | 3 |
| 边界题两道 | 都合格 | 都不合格 | 未评 |

封存题的差距在噪声范围内，算打平。样本小：一个模型、两道任务题、每臂各一次。完整记录和局限见 [`FIDELITY.md`](FIDELITY.md)。

---

## 调研来源

底稿全部在 [`references/research/`](references/research/)：调研前的先验快照 `00-prior.md`、六路底稿 `01`–`06`、封存件 `holdout.md`、验证的题目与原始答卷 `validation-20261109/`，以及 v1 时期的旧底稿 `legacy-202604/`。

一手来源以《Poor Charlie's Almanack》、伯克希尔与 Daily Journal 股东会记录、演讲原文为主；信息源已排除知乎/微信公众号/百度百科。

---

## 这个Skill是怎么造出来的

由 [女娲.skill](https://github.com/alchaincyf/nuwa-skill) v2 生成（从 v1 升级，旧版在本仓库的 `v1.0.0` 标签）。

女娲的做法：调研前先写下模型不查资料就知道的内容 → 调研只找推翻它的、比它深的、它没有的 → 提炼招式、心智模型、案例卡和常见误读 → 独立 agent 盲测，带 Skill 和不带 Skill 各答一遍。

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
├── SKILL.md                    # 可直接安装使用
├── FIDELITY.md                 # 验证记录
├── LICENSE
├── references/
│   ├── casebook.md             # 17 张案例卡
│   ├── voice.md                # 带出处的原话
│   ├── 25-biases.md            # 25 种人类误判心理学
│   └── research/               # 调研底稿、封存件、验证答卷
└── examples/
    └── demo-conversation.md    # 实战对话记录（v1 时期）
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
