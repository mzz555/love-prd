# CORE 三阶段双人模式 · 正式题库 v1

> 定稿日期：2026-09-17（负责人拍板，决定 D14）
> 版本：`language_version` 升一版（中文题干由「工作译稿」变为定稿）；`instrument_version`、`scoring_version` **不变** —— 本次只改中文措辞，分值与维度归属一个字没动（决定 D18）。
> 效力：本文件属「负责人拍板」层，**高于** `source/dual-qbank-校对-20260917/` 里的校对表原件。两者不一致的地方只有 10 处，逐条见[附表一](#附表一--与校对表不同的-10-处)。
> 范围：本文件是**题干与分值的唯一出处**。`requirements.md` 不再重复题干与指导语，只写题序、ID 规则、维度归属与计分口径。

## `{ta}` 是占位符

题干里的 `{ta}` 是指代伴侣的占位符。**显示成什么还没定**（决定 D2：可能是「TA」「他/她」，也可能由用户填写的称呼替换），前端怎么渲染同样待定。

本文件一律保留 `{ta}` 字面，不要在这里替换成任何具体写法 —— 一旦替换，就无法再分辨哪些位置需要随显示方式一起改。

## 阅读这三张表

- 三张表的列一律是：`ID` · `英文原文` · `定稿题干` · `维度`（CSI 为`选项组`）· （CSI 另有 `O1 起分值`）· `文字来源`。
- `文字来源` 只有三种取值：
  - **校对表原译** —— 校对意见「合格」，取校对表的「中文译文」列；
  - **校对表修改列** —— 校对意见「不合格」，取校对表的「修改内容」列；
  - **2026-09-17 决定 Dn** —— 负责人当天另行拍板，与校对表不同，逐条见附表一。
- ISM18 那张表的「定稿题干」列装的是**特质词**（每项特质分别以 W、P 两种任务各作答一次），列名统一是为了让核对脚本按同一个位置取值。

---

## 一、PRI16（16 题）

### 指导语

> 请为以下每道题勾选最能描述你近期对这段关系感受的选项。在过去两周里……

「过去两周」这个时间窗保留（决定 D7）。

### 选项与分值（16 题共用）

| 选项 | 文字 | 分值 |
|---|---|---|
| O1 | 完全不符合 | 0 |
| O2 | 有一点符合 | 1 |
| O3 | 有些符合 | 2 |
| O4 | 相当符合 | 3 |
| O5 | 非常符合 | 4 |
| O6 | 完全符合 | 5 |

### 计分

- `PRI_R` = 回应性 R 八题（C01、C03、C05、C07、C09、C11、C13、C15）的均值。
- `PRI_N` = 不敏感 N 八题（C02、C04、C06、C08、C10、C12、C14、C16）的均值。
- 两项范围都是 0–5。**不反向、不相减、不合成总分。**
- 维度内部名用 `N`（不敏感）；校对表与原作者写的是 `I`（PRI-I），指的是同一个维度，只是叫法不同。

### 题表

| ID | 英文原文 | 定稿题干 | 维度 | 文字来源 |
|---|---|---|---|---|
| PRI16_C01 | My partner really listened to me, | {ta}会认真听我说话。 | R | 校对表修改列 |
| PRI16_C02 | My partner did NOT accept my feelings and concerns | {ta}不把我的感受和担忧当回事。 | N | 校对表修改列 |
| PRI16_C03 | My partner seemed interested in what I was thinking and feeling | {ta}好像很在意我的想法和感受。 | R | 校对表修改列 |
| PRI16_C04 | My partner ignored my side of the story | {ta}根本不听我解释。 | N | 2026-09-17 决定 D3 |
| PRI16_C05 | My partner was understanding | {ta}能理解我。 | R | 2026-09-17 决定 D6 |
| PRI16_C06 | My partner seemed to ignore the things that were most important to me | {ta}似乎不把我最在意的事放心上。 | N | 校对表修改列 |
| PRI16_C07 | My partner tried to see where I was coming from | {ta}会试着站在我的角度想问题。 | R | 校对表修改列 |
| PRI16_C08 | My partner dismissed my concerns too easily | {ta}太轻易就把我的担忧打发掉了。 | N | 2026-09-17 决定 D7 |
| PRI16_C09 | My partner was attentive to my needs | {ta}对我的需求很上心。 | R | 校对表修改列 |
| PRI16_C10 | My partner did NOT really take my concerns seriously | {ta}其实并没有把我的担忧当回事。 | N | 校对表修改列 |
| PRI16_C11 | My partner was responsive to my needs | {ta}会回应我的需求。 | R | 2026-09-17 决定 D11 |
| PRI16_C12 | When I was feeling worried or stressed about something, it only made things worse to tell my partner about it | 当我为某件事担心或压力很大时，告诉{ta}只会让情况更糟。 | N | 校对表修改列 |
| PRI16_C13 | My partner really got my point of view | {ta}真的懂我的想法。 | R | 2026-09-17 决定 D13 |
| PRI16_C14 | My partner often really did NOT hear what I was saying. | 我说的话，{ta}经常没听进去。 | N | 2026-09-17 决定 D4 |
| PRI16_C15 | My partner took my concerns seriously | {ta}重视我的担忧。 | R | 校对表修改列 |
| PRI16_C16 | My partner did NOT really understand my wants and needs | {ta}其实并不明白我想要什么、需要什么。 | N | 校对表修改列 |

---

## 二、ISM18（18 项特质 × W / P 两种任务）

18 项特质每项分别作答两次，ID 在特质号后加 `_W` / `_P`（例：`ISM18_T01_W` 与 `ISM18_T01_P` 是两条独立回答）。**W 与 P 必须分开指导、分开记录。**

### 指导语

- **W（理想重要性）**

  > 请评定以下各项特质在描述你亲密关系中的理想伴侣时有多重要。亲密关系包括恋爱、同居或婚姻。

- **P（现任符合度）**

  > 请评定以下各项特质对你当前关系中的现任伴侣描述得有多准确。当前关系包括恋爱、同居或婚姻。

### 选项与分值（W、P 共用）

`O1` 至 `O7` 依次映射为 `1、2、3、4、5、6、7`。

| 任务 | O1 端 | O7 端 | 中间五档 |
|---|---|---|---|
| W | 非常不重要 | 非常重要 | **只有数字，不自拟文字锚点** |
| P | 完全不符合我伴侣的情况 | 非常符合我伴侣的情况 | **只有数字，不自拟文字锚点** |

### 计分

- 六个均值：`W_WT` / `W_VA` / `W_SR` / `P_WT` / `P_VA` / `P_SR`，各取对应维度六项的均值，范围 1–7。
- **不算 W−P 差值、不算匹配率、不合成总分。**
- 维度：WT = 温暖与可信赖（T01、T04、T07、T10、T13、T16）；VA = 活力与吸引力（T02、T05、T08、T11、T14、T17）；SR = 地位与资源（T03、T06、T09、T12、T15、T18）。

### 题表

| ID | 英文原文 | 定稿题干 | 维度 | 文字来源 |
|---|---|---|---|---|
| ISM18_T01 | Understanding | 善解人意 | WT | 校对表原译 |
| ISM18_T02 | Adventurous | 喜欢尝试新事物 | VA | 校对表修改列 |
| ISM18_T03 | Good job | 有一份好工作 | SR | 校对表原译 |
| ISM18_T04 | Supportive | 能支持我、鼓励我 | WT | 校对表修改列 |
| ISM18_T05 | Nice body | 身材好 | VA | 校对表原译 |
| ISM18_T06 | Financially secure | 经济稳定 | SR | 2026-09-17 决定 D5 |
| ISM18_T07 | Considerate | 体贴 | WT | 校对表原译 |
| ISM18_T08 | Outgoing | 外向 | VA | 校对表原译 |
| ISM18_T09 | Nice house or apartment | 有不错的房子 | SR | 校对表修改列 |
| ISM18_T10 | Kind | 善良 | WT | 校对表原译 |
| ISM18_T11 | Sexy | 性感 | VA | 校对表原译 |
| ISM18_T12 | Appropriate ethnicity | 家庭背景合适 | SR | 校对表修改列 |
| ISM18_T13 | A good listener | 善于倾听 | WT | 校对表原译 |
| ISM18_T14 | Attractive | 有吸引力 | VA | 校对表原译 |
| ISM18_T15 | Successful | 有所成就 | SR | 校对表原译 |
| ISM18_T16 | Sensitive | 敏感细腻 | WT | 校对表原译 |
| ISM18_T17 | A good lover | 亲密时很体贴 | VA | 校对表修改列 |
| ISM18_T18 | Dresses well | 衣着有品味 | SR | 校对表修改列 |

---

## 三、CSI32（32 题）

### 指导语

原件（中英对照稿的译者说明）只给了两段指导语，**其余题目没有单独指导语** —— 不是漏抄，是原件就只有这两段（另见 `requirements.md` 第 9.1 节：CSI 的其余指导语随三份原题文件一起缺）。

- **C02–C04 前**

  > 大多数人在关系中都会存在分歧。请就下列各项，指出你与伴侣的意见大致有多一致或不一致。

- **C26–C32 前**

  > 对于以下各项，请选择最能描述你对这段关系感受的答案。请根据你对该项的第一印象和当下感受作答。

### 选项组

| 组 | O1 | O2 | O3 | O4 | O5 | O6 | O7 |
|---|---|---|---|---|---|---|---|
| A | 极不幸福 | 相当不幸福 | 有些不幸福 | 幸福 | 很幸福 | 极其幸福 | 完美 |
| B | 总是一致 | 几乎总是一致 | 偶尔有分歧 | 经常有分歧 | 几乎总是有分歧 | 总是有分歧 | — |
| C | 总是 | 大多数时候 | 较多时候 | 偶尔 | 很少 | 从不 | — |
| D | 完全不符合 | 有一点符合 | 有些符合 | 大体符合 | 几乎完全符合 | 完全符合 | — |
| E | 一点也不 | 有一点 | 有些 | 大体上 | 几乎完全 | 完全 | — |
| F | 比其他所有关系都差（极其糟糕） | （原表无文字） | （原表无文字） | （原表无文字） | （原表无文字） | 比其他所有关系都好（极其好） | — |
| G | 从不 | 一个月不到一次 | 每月一两次 | 每周一两次 | 每天一次 | 更频繁 | — |
| H | 六个位置 O1–O6：题干斜线左边是左端词，右边是右端词，**中间四档不加字** | | | | | | — |

F 组的中间四档原表就没有文字锚点，**留空，不自拟中性锚点**。

### 计分

- `CSI_TOTAL` = 32 题按各自 `option_id` 映射的分值求和，范围 **0–161**。
- **不二次反向**（表里的「O1 起分值」已经是最终方向）、**不启用 104.5 截点**做分类 / 排序 / 着色。
- **任何一题缺答，正式总分为 null**（后台可另记数学范围，但不作为正式分数）。

### 题表

| ID | 英文原文 | 定稿题干 | 选项组 | O1 起分值 | 文字来源 |
|---|---|---|---|---|---|
| CSI32_C01 | Please indicate the degree of happiness, all things considered, of your relationship. | 综合考虑各方面，你觉得现在这段关系有多幸福？ | A | 0,1,2,3,4,5,6 | 2026-09-17 决定 D8 |
| CSI32_C02 | Amount of time spent together | 你们会不会因为陪伴时间的长短产生分歧？ | B | 5,4,3,2,1,0 | 校对表修改列 |
| CSI32_C03 | Making major decisions | 一起做重大决定时，你们更倾向哪种情况？ | B | 5,4,3,2,1,0 | 校对表修改列 |
| CSI32_C04 | Demonstrations of affection | 在表达爱意的方式上，你们是否合拍？ | B | 5,4,3,2,1,0 | 校对表修改列 |
| CSI32_C05 | In general, how often do you think that things between you and your partner are going well? | 你经常觉得你和{ta}之间一切都挺顺利？ | C | 5,4,3,2,1,0 | 校对表修改列 |
| CSI32_C06 | How often do you wish you hadn't gotten into this relationship? | 你经常希望自己当初没有进入这段关系吗？ | C | 0,1,2,3,4,5 | 校对表修改列 |
| CSI32_C07 | I still feel a strong connection with my partner | 我觉得和{ta}很亲近。 | D | 0,1,2,3,4,5 | 校对表修改列 |
| CSI32_C08 | If I had my life to live over, I would marry (or live with / date) the same person | 如果人生能重来，我还是会和{ta}结婚（或同居 / 交往）。 | D | 0,1,2,3,4,5 | 校对表修改列 |
| CSI32_C09 | Our relationship is strong | 我们的感情很稳固。 | D | 0,1,2,3,4,5 | 校对表修改列 |
| CSI32_C10 | I sometimes wonder if there is someone else out there for me | 我有时会想，是不是还有更适合我的人。 | D | 5,4,3,2,1,0 | 校对表修改列 |
| CSI32_C11 | My relationship with my partner makes me happy | 和{ta}在一起让我感到幸福。 | D | 0,1,2,3,4,5 | 校对表修改列 |
| CSI32_C12 | I have a warm and comfortable relationship with my partner | 和{ta}在一起让我感到温暖和自在。 | D | 0,1,2,3,4,5 | 2026-09-17 决定 D13 |
| CSI32_C13 | I can't imagine ending my relationship with my partner | 我无法想象和{ta}结束这段关系。 | D | 0,1,2,3,4,5 | 校对表修改列 |
| CSI32_C14 | I feel that I can confide in my partner about virtually anything | 我觉得几乎什么事都可以跟{ta}说。 | D | 0,1,2,3,4,5 | 校对表修改列 |
| CSI32_C15 | I have had second thoughts about this relationship recently | 最近，我对这段关系产生了动摇。 | D | 5,4,3,2,1,0 | 校对表原译 |
| CSI32_C16 | For me, my partner is the perfect romantic partner | 我觉得{ta}是我的完美另一半。 | D | 0,1,2,3,4,5 | 校对表修改列 |
| CSI32_C17 | I really feel like part of a team with my partner | 我觉得我和{ta}能一起面对问题。 | D | 0,1,2,3,4,5 | 校对表修改列 |
| CSI32_C18 | I cannot imagine another person making me as happy as my partner does | 我无法想象还有谁能像{ta}一样让我幸福。 | D | 0,1,2,3,4,5 | 校对表修改列 |
| CSI32_C19 | How rewarding is your relationship with your partner? | 和{ta}在一起的这段时间，你认为你有成长吗？ | E | 0,1,2,3,4,5 | 校对表修改列 |
| CSI32_C20 | How well does your partner meet your needs? | {ta}在多大程度上满足了你的需求？ | E | 0,1,2,3,4,5 | 校对表修改列 |
| CSI32_C21 | To what extent has your relationship met your original expectations? | 现在这段关系有达到你最初的期待吗？ | E | 0,1,2,3,4,5 | 校对表修改列 |
| CSI32_C22 | In general, how satisfied are you with your relationship? | 你对现在这段关系满意吗？ | E | 0,1,2,3,4,5 | 校对表修改列 |
| CSI32_C23 | How good is your relationship compared to most? | 和大多数情侣相比，你认为你们的感情有多好？ | F | 0,1,2,3,4,5 | 校对表修改列 |
| CSI32_C24 | Do you enjoy your partner's company? | 你喜欢和{ta}待在一起吗？ | G | 0,1,2,3,4,5 | 校对表修改列 |
| CSI32_C25 | How often do you and your partner have fun together? | 你和{ta}在一起时，大概多久会有一段很开心的时光？ | G | 0,1,2,3,4,5 | 2026-09-17 决定 D9 |
| CSI32_C26 | INTERESTING / BORING | 有趣的 / 无聊的 | H | 5,4,3,2,1,0 | 校对表原译 |
| CSI32_C27 | BAD / GOOD | 糟糕的 / 好的 | H | 0,1,2,3,4,5 | 校对表原译 |
| CSI32_C28 | FULL / EMPTY | 充实的 / 空洞的 | H | 5,4,3,2,1,0 | 校对表修改列 |
| CSI32_C29 | LONELY / FRIENDLY | 孤独的 / 亲切的 | H | 0,1,2,3,4,5 | 校对表修改列 |
| CSI32_C30 | STURDY / FRAGILE | 稳固的 / 脆弱的 | H | 5,4,3,2,1,0 | 校对表原译 |
| CSI32_C31 | DISCOURAGING / HOPEFUL | 令人灰心的 / 充满希望的 | H | 0,1,2,3,4,5 | 校对表原译 |
| CSI32_C32 | ENJOYABLE / MISERABLE | 令人愉快的 / 令人痛苦的 | H | 5,4,3,2,1,0 | 校对表原译 |

### 重点核对

- C05 与 C06 共用频率选项组 C，但分值方向相反。
- C10、C15 与 D 组其他题方向相反。
- C26 至 C32 两端的正负方向交替，不要按顺序默认。
- C24 的原题文字配频率选项（G 组），按原稿保留；不能为了顺口换成程度选项还沿用当前分值。

---

## 附表一 · 与校对表不同的 10 处

这 10 处是**本文件与 `source/dual-qbank-校对-20260917/` 校对表原件不一致的全部位置**。校对表的取用规则是「校对意见『不合格』取『修改内容』列，『合格』取『中文译文』列」；下面每一条都是负责人 2026-09-17 在该规则之外另定的。

| 题号 | 校对表的写法 | 定稿写法 | 依据 | 为什么 |
|---|---|---|---|---|
| PRI16_C04 | 两种写法用 `/` 并列，没选定 | `{ta}根本不听我解释。` | D3 | `side of the story` 指「我这边的说法」，多半发生在分歧时的解释场景 |
| PRI16_C05 | 校对意见「合格」，按规则应取原译「我的伴侣能理解我。」 | `{ta}能理解我。` | D6 | 16 题的称呼统一成 `{ta}`，不留「我的伴侣」这一处例外 |
| PRI16_C08 | `{ta}总是不把我的担忧当回事。` | `{ta}太轻易就把我的担忧打发掉了。` | D7 | 原文 `too easily` 讲的是程度不是频率；「总是」会压低 `PRI_N`，「打发」也能与 C02、C10 区分开 |
| PRI16_C11 | `{ta}会满足我的需求。` | `{ta}会回应我的需求。` | D11 | `responsive` 是「有回应」，不是「做到了」 |
| PRI16_C13 | `{ta}真地懂我的想法。` | `{ta}真的懂我的想法。` | D13 | 笔误 |
| PRI16_C14 | 两种写法用 `/` 并列，没选定 | `我说的话，{ta}经常没听进去。` | D4 | 另一种写法「走神」描述的是另一种行为，不是没听进去 |
| ISM18_T06 | `经济稳定/经济条件好` | `经济稳定` | D5 | `secure` 是「有保障」；「条件好」会与 T03（有一份好工作）、T15（有所成就）重叠 |
| CSI32_C01 | `请综合考虑各方面，说说你对现在这段关系的感受/体验。` | `综合考虑各方面，你觉得现在这段关系有多幸福？` | D8 | 「说说」读起来像要用户打字；本题的选项是幸福程度七档 |
| CSI32_C12 | 句末缺句号 | `和{ta}在一起让我感到温暖和自在。` | D13 | 笔误 |
| CSI32_C25 | `你和{ta}在一起时会经常让你感到愉快吗？` | `你和{ta}在一起时，大概多久会有一段很开心的时光？` | D9 | 本题选项是频率档（G 组），原句已经不是在问频率 |

## 附表二 · 含义已与原量表不同、分数不能跟原量表比的 3 题

这三题的中文定稿把测的东西换掉了。**维度归属与分值一律不动**（决定 D18），但**不能拿这三题的分数与原量表的常模或文献结果比较**。

| 题号 | 英文原文 | 定稿题干 | 依据 | 实际测的是什么 |
|---|---|---|---|---|
| ISM18_T12 | Appropriate ethnicity | 家庭背景合适 | D1 | 仍算「地位与资源」（SR）维度，但测的不是族裔 |
| ISM18_T17 | A good lover | 亲密时很体贴 | D1 | 仍算「活力与吸引力」（VA）维度，但更接近「体贴」 |
| CSI32_C19 | How rewarding is your relationship with your partner? | 和{ta}在一起的这段时间，你认为你有成长吗？ | D12 | 测的是「成长」，不是原题的「关系的回报感」；仍计入 `CSI_TOTAL` |

---

本文件与校对表原件的差异只有附表一那 10 处，可用 `scripts/verify_phase3_qbank.py` 自动核对。
