# CKB Community Fund DAO规则和流程

# **DAO 的治理范围**

CKB Community Fund DAO 是由 Nervos 社区发起，社区和基金会共同捐款的社区基金，用于资助社区成员围绕 CKB 生态进行如代码开发、活动组织、内容制作、宣传推广等促进生态发展的工作。CKB Community Fund DAO （以下简称 DAO）初始持有资金 276,000,000 CKBs.

DAO 支持两种类型的治理：

1. 决定是否通过来自团队或个人，为 CKB 生态建设相关工作所申请预算(CKB)的提案。
2. 决定是否通过 DAO 的元规则的修改，如投票权重的计算、投票的准入资格、通过的条件等。

# 治理流程

## 治理工具

1. 提案发起和讨论论坛 [Nervos Talk](https://talk.nervos.org/c/ckb-community-fund-dao/65): Nervos Talk 是一个基于开源项目 Discourse 搭建的论坛，其为 CKB Community Fund DAO 建立了专用版块，用于提案的讨论和推进。
2. 提案投票工具 [Metaforo](https://dao.ckb.community/): Metaforo 是一个 Web3 原生社区平台。CKB Community Fund DAO 使用了投票功能，对提案进行投票。

## 提案的流程

提案从提出到执行分三个阶段：**Discussion Stage, Voting Stage and Execution Stage**

### 第一阶段：Discussion Stage — [on Nervos Talk(Discourse)](https://talk.nervos.org/c/ckb-community-fund-dao/65)

**这个阶段主要有两个目的：**

1. 给予充足的时间（一周），帮助社区充分理解提案的内容和提案预算的合理性，并且有足够的时间留给社区讨论并给予提案者修改的建议和意见。
2. 测试这个提案的热度，及是否有一定数量的社区成员对这个议题感兴趣。

**通过条件：**

在一周的时间内提案帖累积 30 个赞（心），则视为通过了 Discussion Stage.

**如何提交一个优秀的 Discussion Stage 提案：**

- 好的提案通常源于对一个好问题的捕捉，包含了对这个问题的分析并给出合适的解决方案。
- 通常在提交一个提案之前需要和社区通过论坛或其他形式先进行基本的沟通以初步测试自己的想法和解决方案，但此过程并非流程所必须，所以在此不过多赘述。
- 标题以 **[DIS]** 开头，应该简洁且准确，比如 “[DIS] 在越南定期组织社区线下聚会 - 2023 Q1“
- 提案内容方面，格式上并没有强制要求，希望通过实践逐步形成最佳实践。但通常内容应该包含以下部分：
    - 为什么要做这件事？(Why?)
    - 为什么你适合去做这件事？(Why you?)
    - 为什么要现在去做这件事？(Why now?)
    - 你申请的预算是多少？为什么是这么多？(Budget)
    - 你打算怎么开展工作？有几个 milestone, 分别是什么? (How?)
- 用什么语言写提案
    - 提案要求语言为英文或中文。
    - 无论选择哪种语言，建议用 [Deepl](https://www.deepl.com/translator) 或 [Google Translate](https://translate.google.com/) 等翻译软件翻译成另一种语言，并把翻译贴在帖子尾部。

提案要么包含对资金的申请，要么包含对元规则的修改。如果纯粹只是做提案前期讨论，请不要以 [DIS] 开头作为标题。可以直接在本版块提问如： “大家觉得是否值得去越南定期组织线下社区聚会？”

### 第二阶段：Voting Stage — [on Metaforo](https://dao.ckb.community/)

如果 Discussion Stage 通过后，发起者希望继续推动提案。那么此提案将进入第二个阶段: Voting Stage.  在这个阶段社区成员将最终对提案进行投票，并决定此提案是否通过。

**如何提交 Voting Stage 提案：**

1. Voting Stage 提案需要[在 Metaforo 进行](https://dao.ckb.community/)，并且提交者要求至少有 100,000 CKBs 存放于 Nervos DAO 中，才能发起提案。(如何在 Metaforo 绑定 Nervos DAO 地址请参看教程：[如何在 Metaforo 中绑定你的 Nervos DAO 地址并参与投票？](https://dao.ckb.community/thread/metaforo-nervos-dao-41912))

    投票设置的细节 - 请务必按照教程设置，否则管理员有权删除此提案

    - 新建一个 Poll, 选择 “Calculate voting power with Nervos DAO“, 并勾选 “Weight users’s votes by number of tokens the user holds“ 和 “Set a quorum limit“.


        ![](https://github.com/CKB-Community-Fund-DAO/rules/blob/main/assets/poll-setup-1.png?raw=true)

    - 名字以 **[VOT]** 开头，名字正文部分和 **Discussion Stage** 阶段保持一致
    - “Automatically close poll”: 选择七天之后的日期，如 4日发起的 Poll, 应该选择 11 日作为 close date.
    - “The minimum number of votes required to pass the proposal” **设置为提案中你申请预算的 CKB 数量的 3 倍**，如果你要申请 10,000,000 个 CKB, 那么此处应该填写 30,000,000. **如果此提案涉及元规则的修改，那么应该设置为 185,000,000**
    - “Fill in the % of total votes voting to yes to pass the proposal” 设置为 **51%,** 如果是修改元规则提案，需要设置为 **67%**
    - Show Results: Always visible
    - Show who voted: checked.

        ![](https://github.com/CKB-Community-Fund-DAO/rules/blob/main/assets/poll-setup-2.png?raw=true)


2. 提案标题和内容
    - 提案的标题和内容，标题和投票一致: 以 **[VOT]** 开头，名字内容的部分和 **Discussion Stage** 阶段保持一致.
    - 原则上，内容应该和 **Discussion Stage** 提案一致，可以复制粘贴。 如果内容有修改，请务必在最上方醒目位置强调修改的部分。
    - **如果是申请预算的提案，请务必在正文第一行包含接收预算的 CKB 地址。（不能修改）**
    - 内容中也应该包含通过的 Discussion Stage 阶段原帖链接。
    - **修改 [DIS] 原帖，正文第一行写上 Voting Stage 投票链接地址**

        ![](https://github.com/CKB-Community-Fund-DAO/rules/blob/main/assets/poll-setup-3.png?raw=true)

**通过条件：**

根据上述在创建投票时设置的参数，通过条件分两种情况：

1. 预算申请提案: 通过7天的公开投票，结束时获得不少于 **51%** 的赞成票，并且总参与票数（quorum）不低于提案中申请预算的3倍 CKB 数量。（如果申请 100,000 CKB, 那么总参与票数至少要大于等于 300,000票）
2. 元规则修提案：通过7天的公开投票，结束时获得不少于 **67%** 的赞成票，并且总参与票数（quorum）不低于 **185,000,000** 票

### 第三阶段：Execution Stage

提案通过后，将进入最终的执行阶段。

- 如果是申请预算的提案，提案内容中没有另外的资金支付规则，那么 DAO 资金管理委员会应该按照默认规则，在一周内进行支付。如果有另外的支付规则，则按照提案中的规则执行。
    - 当提案通过后，申请团队即可立马开展工作，招人、开发、办活动等等等。
    - 在过程中，申请团队有义务向社区同步之后开展工作的进展，比如定期或达成某个 milestone 后，以 **[Status Update]** 为标题开头在论坛给社区汇报工作进展。保持良好的沟通才有利于团队得到社区的帮助，甚至找到志同道合的同伴一起前行。
    - 社区成员也有权利监督申请团队的工作效果和资金使用，并以论坛发帖的方式进行评论或探讨。
- 如果是修改元规则提案，此类提案通过之后，由于可能会涉及必要的系统开发等因素，无法马上开始执行。对于此类提案，管理委员会应在二周之内给出实施计划，并定期进行状态更新，直到最终实施。

## 修正案

- [禁止向 DAO 的投票者空投任何资产](https://dao.ckb.community/thread/vot-ban-incentivized-voting-in-dao-43212)。
- [Metaforo 上的票数根据投票者当前持有的 Nervos DAO 存款值计算，已解锁/提现的 CKB 不计入投票权重](https://dao.ckb.community/thread/vot-changing-how-votes-are-calculated-43287)。
