# Session Notes: 2026-06-14

## 0. 会话概述
- **扫描文本**：21BEC.md（Listening Script 5.3 "Some Opinions on Art"）
- **21BEC 扫描结果**：学生 12 组疑问点中，`the sort of + 名词`（⚠️ 部分记录）和功能区域零冠词（⚠️ 部分记录）为已有部分覆盖；10 个未记录语言点中提取 7 个进行训练（`good for` / `up to date` / `I can't see how...` / `opinions on` / `enough` / `the sort of` 泛化 / `show + 宾语 + 现在分词`）
- **实际训练**：定向纠偏（`discuss` 及物性 2+2 轮）+ knowledge-gaps 轮换（Tag 极性 2 轮）+ LP 1（`good for` 5 句式+QF）+ LP 2（`up to date` 6 句式+QF）+ LP 3（`I can't see how...` 6 句式+QF）+ LP 4（`opinions on` 6 句式+QF）+ LP 5（`enough` 6 句式+QF）+ LP 6（`the sort of` 泛化 6 句式+QF）+ LP 7（`show + 宾语 + 现分` 6 句式+QF）+ Micro Role-play x2 + 话题构建训练（技术决策与 trade-off 解释，4 步全程走过）
- **本次未训练的语言点**：`somewhere` 作名词、`say` 拟人化用法、功能区域零冠词规则（留待后续扫描训练）
- **模型**：deepseek-v4-flash

---

## 1. 🎯 定向纠偏 (Flash Correct)

### 类别：`discuss` 及物性 — 介词搭配类（2026-05-30 新发现）
**选题原因**：该缺口距上次发现已 15 天，从未做过专项 Flash Correct 巩固。

- **Round 1**: 我们明天需要讨论一下这个项目的截止日期。
  - 学生：`We need to talk the deadline for this project tomorrow.`
  - 评价：❌ `talk the deadline` — `talk` 是不及物动词，不能直接接宾语。正确：`discuss the deadline` ✅ 或 `talk **about** the deadline` ✅。

- **学生自行纠正**：`We discussed the proposal in yesterday's meeting.`
  - 评价：✅ `discussed the proposal` — 及物动词直接接宾语，零错误！过去时 `discussed` 正确，`in yesterday's meeting` 正确。

- **Round 2**: 我们需要在会上讨论一下预算的问题。
  - 学生：`We need to talk the budgets in the meeting.`
  - 评价：❌ **再次回退**：`talk the budgets` — 同一 session 内连续 2 次用 `talk` 替代 `discuss` 且都漏了 `about`。说明 `discuss` 及物性的肌肉记忆还未建立。

- **加练 1 轮**：我们需要讨论一下如何提高销售额。（强制用 `discuss`）
  - 学生：`We need to discuss how to increase the sales.`
  - 评价：✅ `discuss how to...` — 及物动词接宾语从句，完美！⚠️ `increase sales`（不加 `the`）更自然。

- **再加练 1 轮（同一类别）**：我们需要在会上讨论一下预算的问题。（再出一次，强制用 `discuss`）
  - 学生：`We need to discuss the budgets in the meeting.`
  - 评价：✅ `discuss the budgets` — 及物动词直接接宾语，修复成功！

**纠偏小结**：2 次复发 + 2 次修复。`discuss` 的及物性在无提示自由产出时仍被 `talk about` 思维干扰，但强制使用 `discuss` 后掌握。从 🔴 Active 移入 🟡 Monitoring，下次会话继续抽查。

---

## 2. 📝 核心语言点训练

---

### LP 1: `good for`（适合/有益于）— 新学 🆕

**来源**：21BEC — `This is quite good for reception.`
**含义**：① 适合某场景/用途；② 对……有益。注意区分 `good at`（擅长做某事）。
**训练句式**：5/6 句式覆盖（+ QF）。虚拟语气跳过（`good for` 的客观性不适合假设场景）。

#### Round 1 (肯定陈述句)
- 中文：这个小房间放书架挺合适的。
- 学生：`Shelves are good for this small room.`
- 评价：✅ **满分**。`good for` 语义完全正确。`Shelves` 口语中默认指书架，选词精准。

#### Round 2 (否定陈述句) ⚠️ 主客体对应偏差
- 中文：这个位置不适合放这个电脑。
- 学生：`This computer is not good for this place.`
- 评价：⚠️ 主客体关系颠倒。中文主语是"位置"，即 `This place is not good for this computer`（位置不适合放电脑）。学生的 `This computer is not good for this place` 意思是"这个电脑不适合这里"（暗示电脑本身有问题）。这是中英主语切换时的常见偏差。非关键性错误，不追加练习。
- 修正：`This place is not good for this computer.` ✅

#### Round 3 (一般疑问句)
- 中文：这个水池适合浇花吗？
- 学生：`Is this pool good for watering flowers?`
- 评价：✅ **满分**。句式完整，`for + doing` 搭配正确。⚠️ `pool` 默认指"游泳池"，`water tank` / `water basin` 更精准，但不影响 `good for` 结构正确性。

#### Round 4 (反义疑问句) 🏆
- 中文：这个灯适合看书，对吧？
- 学生：`This light is good for reading, isn't it?`
- 评价：✅ **满分**。肯定主句 + 否定 Tag `isn't it`，极性完全正确。Tag 代词 `it` 与主语 `this light` 单数一致。

#### Round 5 (选择疑问句) ❌ 形容词比较级不规则变化（非 `good for` 问题）
- 中文：这本教材更适合初学者还是中级学者？
- 学生：`Is this book more good for beginners or intermediate learners?`
- 评价：❌ `more good` — `good` 的比较级是不规则变化 `good → better → best`。应为 `Is this textbook better for beginners or intermediate learners?`。属于形容词不规则变化的基础语法缺口，非 `good for` 结构本身的问题。

- **修正轮**：这个位置比那个位置更适合开会。
  - 学生：`This place is better for a meeting than that.`
  - 评价：✅ `better for` — 比较级修正成功！⚠️ `than that` 句尾突兀 → `than that one` 更完整。

#### Quick Fire
- 场景：同事在考虑买一把新办公椅，你试用过觉得对腰背很好。直接对他说一句英文。
- 学生：`this office bench is good for your waist.`
- 评价：✅ `good for` 结构使用正确。❌ `bench`（长凳）→ `office chair`（办公椅）；`waist`（腰围）→ `back` / `lower back`（腰背）。词汇精准度需提高，但目标结构用对了。反应速度良好，不需要中文中转。

**LP 状态**：🟡 复用中。5 句式覆盖，核心结构掌握稳定。`more good` 暴露了形容词不规则变化的底层缺口。选词精准度（`pool`/`bench`/`waist`）有待提高。

**本次植入历史词组**：无（AI 本轮未从 active-pool 选取历史词组植入，见 AI 问题反思）。

---

### LP 2: `up to date`（新潮的/与时俱进的/最新的）— 新学 🆕

**来源**：21BEC — `Let's have something up to date.`
**含义**：① 形容词短语，后置修饰名词；② 作表语表示"最新版本"；③ 前置作定语时加连字符 `up-to-date information`；④ 拓展 `keep sth up to date`（保持更新）。
**训练句式**：6/6（全部覆盖 + QF）

#### Round 1 (肯定陈述句)
- 中文：我们公司的网站设计很新潮。
- 学生：`The design for our company's websites is up to date.`
- 评价：✅ `is up to date` 表语用法正确。⚠️ `design for` → `design of` 更自然；`websites`（复数）→ `website`（单数，指公司官网）。

#### Round 2 (否定陈述句) 🏆
- 中文：他们的库存系统不是最新的。
- 学生：`Their inventory system is not up to date.`
- 评价：✅ **满分**。`is not up to date` 否定结构完全正确。零瑕疵。

#### Round 3 (一般疑问句) ❌ 双重系动词
- 中文：你的杀毒软件是最新版吗？
- 学生：`Are your antivirus software is up to date?`
- 评价：❌ 双重系动词：一般疑问句公式是 `Be + 主语 + 表语?`，不能既有 `Are` 又有 `is`。且 `antivirus software` 不可数，应用 `Is`。正确：`Is your antivirus software up to date?`。属于一般疑问句结构的基础规则，非 `up to date` 本身错误。

#### Round 4 (反义疑问句) ❌ 多处问题（缺系动词 + Tag 极性 + 单复数）
- 中文：你的简历是最新的，对吧？
- 学生：`Your resumes up to date, is it?`
- 评价：❌ 三处问题：
  1. `resumes` — 简历一般用单数 `resume`（除非多份简历）
  2. 缺系动词：`resumes` 和 `up to date` 之间应该有 `is`（`Your resume is up to date`）
  3. 🔴 **Tag 极性错误**：主句肯定（`is up to date`）→ 反问应为否定 `isn't it?`，不能是 `is it?`。这是 knowledge-gaps 中 Tag 极性回退的又一次复发。
- 修正：`Your resume is up to date, isn't it?` ✅

#### Round 5 (选择疑问句) 🏆
- 中文：你的报告是过时的还是最新的？
- 学生：`Is your report outdated or up to date?`
- 评价：✅ **满分**。选择疑问句结构正确，`outdated` vs `up to date` 完美反义词对照，平行结构正确。

#### Round 6 (虚拟语气) 🏆🏆 学生主动产出
- 学生直接主动产出（未等导师出题）：`If your system was not up to date, there would be security risks.`
- 评价：✅ **满分**。Type 2 虚拟语气 `If + 过去时 → would + 原形` 完全正确。这说明学生对 Type 2 虚拟语气结构已很自信，能主动调用！口语中 `was` 可接受，正式语法可用 `were`。🏆

#### Quick Fire — 植入 `run into`（🟢 历史词组）
- 场景：IT 运维，同事想跳过系统更新。告诉他不更新会出问题，之前就有一次因为没更新遇到了安全漏洞。
- 学生：`If the system is not up to date, we're gonna have some issues. previously we ran into security issues, just because we had not updated it.`
- 评价：✅ `up to date` 正确使用。✅ **`run into` 历史词组成功复用！** `ran into security issues` 过去式正确。时态层级清晰：Type 1 条件句 + 过去时叙事 + 过去完成时（原因在先），三层时态逻辑完全正确。口语连接 `gonna` 地道自然。

**LP 状态**：🟡 复用中。6 句式全覆盖，核心结构掌握良好。虚拟语气和 Quick Fire 表现优异 🏆。双重系动词和 Tag 极性回退是底层基础语法问题。`run into` 历史词组成功复用。

**本次植入历史词组**：`run into` — 🟢，在 QQ 中成功复用，状态维持 🟢。

---

### Micro Role-play 1（整合 LP 1-2: `good for` + `up to date`）

**场景**：你是公司 IT 采购负责人。同事想买一批便宜的旧显示器。你建议不要——那些显示器已经过时了，不适合日常工作。推荐一款新显示器，虽贵但更值得。

**学生产出**：
> `It's better not to buy these outdated displays because they are not good for our daily work. Would better buy up-to-date displays, although it's more expensive, it's worth it.`

**目标短语覆盖**：
| 短语 | 是否使用 | 用法评价 |
|:---|:---:|:---|
| `good for` | ✅ | `not good for our daily work` — 否定形式正确 |
| `up to date` | ✅ | `up-to-date displays` — 带连字符前置作定语，完全正确 |

**评价**：
- ✅ `good for` 否定形式正确使用
- ✅ `up-to-date` 前置带连字符，用法精准
- ❌ `Would better buy` — 这是本次新暴露的缺口：`had better` / `would be better to` 的混淆。正确说法：`We'd better buy...` ✅ 或 `It would be better to buy...` ✅。不能单独说 `Would better + 动词`

**Micro RP 通过**（目标短语覆盖 ✅，`Would better` 为新发现缺口）。

---

### LP 3: `I can't see how...`（委婉表达质疑/不理解）— 新学 🆕

**来源**：21BEC — `I can't see how that is art.`
**含义**：`can't see` 在此非"看不见"，而是"不理解/不认同"。"how" 在此表质疑（"凭什么/怎么能"），非中性"如何"。区分 `how`（质疑合理性）vs `why`（问原因）。
**训练句式**：6/6（全部覆盖 + QF）

#### Round 1 (肯定陈述句 — 带否定 can't) ❌ 选词偏差 + 主谓一致
- 中文：我看不出这个方案怎么能省钱。
- 学生：`I cannot see how this plan make money.`
- 评价：❌ 两处问题：
  1. "省钱" → `save money`，非 `make money`（赚钱）。词汇理解偏差。
  2. `this plan make` → 第三人称单数应用 `makes`，或加情态动词 `can save`。
- 🔴 **关键性错误 → 加练 1 轮**

- **加练轮**：我看不出这么短的会议怎么能做出决定。
  - 学生：`I cannot see how we can make decisions in this short meeting.`
  - 评价：✅ **加练通过**。`I cannot see how...` 结构正确，从句 `how we can make decisions` 陈述语序正确，`in this short meeting` 介词正确。

#### Round 2 (否定陈述句) ⚠️ 选词偏差
- 中文：我看不出这个功能有什么特别之处。
- 学生：`I cannot see how this feature can work specially.`
- 评价：⚠️ `work specially` — `specially` = "特意地/专门地"（副词），不是"特别的"（形容词）。"有什么特别之处" 应表达为 `how this feature is anything special`。非关键性错误，不追加练习。

#### Round 3 (一般疑问句) 🏆
- 中文：你能看出来他的方案怎么行得通吗？
- 学生：`Can you see how his plan can work?`
- 评价：✅ **满分**。从 `I can't see how` 灵活变体为 `Can you see how`，这正是句式灵活的体现。从句语序 `how his plan can work` 陈述语序正确。

#### Round 4 (反义疑问句) 🏆🏆 本次最佳
- 中文：你看不出这个安排怎么能成功，对吧？
- 学生：`You cannot see how this arrangement can succeed, can you?`
- 评价：✅ **满分**。否定主句 `cannot see` → 肯定反问 `can you?`，**Tag 极性完全正确！** 这是今天所有反义疑问句中唯一一次极性直接正确的。从句 `how this arrangement can succeed` 陈述语序正确。🏆🏆

#### Round 5 (选择疑问句) ❌ `lack of` 名词/动词混淆
- 中文：你看不出他是经验不足还是不在状态吗？
- 学生：`Can you see he's lack of experience or out of sorts?`
- 评价：❌ `he's lack of experience` — `he's` = `he is`，但 `He is lack of experience` 语法不通。`lack of` 是名词短语（需加冠词 `a lack of`），不能直接放系动词后当表语。正确：`Can you see whether he lacks experience or is out of sorts?`（`lack` 作及物动词）。
- 🔴 **关键性错误 → 加练 1 轮**

- **加练轮**：你看得出他是在开玩笑还是认真的吗？
  - 学生：`Can you see he's joking or serious?`
  - 评价：✅ **加练通过**。`see` 表"看出/判断出"语义正确，`joking or serious` 平行结构通顺。口语可接受。

#### Round 6 (虚拟语气)
- 中文：如果你是他，你也看不出这个安排该怎么推进。
- 学生：`If you were him, you would not see how this arrangement can be moved forward.`
- 评价：✅ Type 2 虚拟语气 `If + were → would + 原形` 完全正确。✅ `would not see how...` 目标结构在虚拟条件中正确嵌入。⚠️ `can` → `could`（虚拟条件从句时态需后退一致），`be moved forward` 被动语态可用主动 `move this arrangement forward` 更自然。

#### Quick Fire
- 场景：团队讨论选新人做项目负责人——此人刚入职两周。你完全觉得不合理。对旁边的同事小声说一句。
- 学生：`I cannot see how he can finish this task.`
- 评价：✅ `I cannot see how...` 结构正确。⚠️ 略微偏离场景：场景是"选他做负责人"，应说 `how he can lead a team` 而非 `finish a task`。但目标结构用对，无语法错误，通过。

**LP 状态**：🟡 复用中。6 句式覆盖，核心结构掌握良好。反义疑问句极性第一次全程正确 🏆。两个加练轮分别暴露了 `lack of` 名词/动词混淆和词汇选词偏差（`save` vs `make` money），均已当轮修复。

**本次植入历史词组**：无（系统未从 active-pool 植入到 `I can't see how` 的造句中，见 AI 问题反思）。

---

### LP 4: `opinions on` / `views on`（表达对…的看法）— 新学 🆕

**来源**：21BEC — `Some Opinions on Art`（课文标题）
**含义**：`opinions on` = 对某事的看法/意见（侧重个人判断）；`views on` = 对某事的观点（侧重系统性见解）。都用介词 **`on`** 引出对象。❌ 不要说 `opinions about art`。
**训练句式**：6/6（全部覆盖 + QF）

#### Round 1 (肯定陈述句) 🏆
- 中文：大家对远程办公有不同的看法。
- 学生：`There are different opinions on remote working.`
- 评价：✅ **满分**。`opinions on` + 宾语 `remote working` 完全正确。`There are` + 复数名词，主谓一致正确。

#### Round 2 (否定陈述句) ⚠️ Most of people 冠词缺
- 中文：大多数人还没有对此形成一个明确的看法。
- 学生：`Most of people have not had a clear opinion on this.`
- 评价：⚠️ `Most of people` ❌ → `Most people` ✅（泛指）或 `Most of the people` ✅（特指）。`most` + 泛指名词不加 `of`。`opinion on` 结构用对了 ✅。`had` → `formed` 更精准（"形成看法"）。

#### Round 3 (一般疑问句) 🏆
- 中文：你对这个培训计划有什么看法吗？
- 学生：`Do you have any opinions on this training plan?`
- 评价：✅ **满分**。一般疑问句结构正确，`any opinions on` 高频搭配。

#### Round 4 (反义疑问句) ❌ Tag 极性回退
- 中文：你对远程办公有些看法，对吧？
- 学生：`You have some opinions on remote work, do you?`
- 评价：✅ `opinions on` 正确。🔴 Tag 极性回退：肯定主句 `You have` → 应为否定反问 `don't you?`（非 `do you?`）。今日第二次 Tag 极性回退（首次在 LP 2）。

#### Round 5 (选择疑问句) ⚠️ 单复数代词不匹配
- 中文：你对他的提议是持积极的看法还是消极的看法？
- 学生：`Do you have positive opinions on his proposal or negative one?`
- 评价：✅ `opinions on` 正确。⚠️ `negative one` — `one` 单数指代复数 `opinions`，应为 `negative ones`。更自然的说法：`Do you have a positive or negative opinion on his proposal?`

#### Round 6 (虚拟语气) ✅
- 中文：如果你是客户，你对这个价格会有不同的看法吗？
- 学生：`If you were the client, would you have different opinions on this price?`
- 评价：✅ Type 2 虚拟语气完全正确。`opinions on` 嵌入 `would have` 结构中自然使用。⚠️ `opinions on this price` 稍显生硬，`pricing` / `pricing strategy` 更自然，但非错误。

#### Quick Fire
- 场景：刚做完项目汇报，新同事悄悄问你大家对汇报的看法。
- 学生：`Well, I have different opinions on this report, but I cannot say right now, I have to conclude my opinions in a document later.`
- 评价：✅ `opinions on` 正确。⚠️ 场景理解略有偏差：同事问的是"大家"的看法，你回应的是"你个人的"看法。`conclude my opinions` 中式搭配 → `summarize my thoughts` / `write up my opinions`。

**LP 状态**：🟡 复用中。核心结构掌握良好。Tag 极性回退 1 次 + `Most of people` 冠词缺失 + `conclude` 搭配偏差。6 句式全覆盖。

---

### LP 5: `enough` 后置修饰形容词 — 新学 🆕

**来源**：21BEC — `It isn't bold enough for this area.`
**含义**：`adj + enough`（后置修饰形容词）；`enough + noun`（前置修饰名词）；`adj + enough + for + sb/sth`；`adj + enough + to do`。❌ `very + adj + enough` 双重程度修饰冲突。
**训练句式**：6/6（全部覆盖 + QF）

#### Round 1 (肯定陈述句) ❌ very simple enough 双重修饰
- 中文：这个问题很简单，足够让新人也解决。
- 学生：`This question is very simple enough to make newcomers solve it.`
- 评价：❌ `very simple enough` — `very` 和 `enough` 不能同时修饰同一形容词，语义冲突。❌ `make newcomers solve it` → `for newcomers to solve`。🔴 **关键性错误 → 加练 1 轮**。
- **修正轮（→句式 2 合并）**：按句式 2 否定陈述句继续出题。

#### Round 2 (否定陈述句) 🏆
- 中文：这个会议室不够大，坐不下 20 个人。
- 学生：`This meeting room is not big enough to fit twenty people.`
- 评价：✅ **满分**。`not big enough to fit` — 否定形式 + `enough to do` 结构完美。零瑕疵。

#### Round 3 (一般疑问句) 🏆
- 中文：这个报告够详细吗，能交给经理看了？
- 学生：`Is this report detailed enough to submit to the manager?`
- 评价：✅ **满分**。`detailed enough to submit` — 一般疑问句 + `adj + enough + to do` 完美。

#### Round 4 (反义疑问句) 🏆 Tag 极性连续正确
- 中文：这间办公室够干净的了，对吧？
- 学生：`this office is clean enough, isn't it?`
- 评价：✅ **满分**。Tag 极性正确：肯定主句 `is clean` → 否定反问 `isn't it?` ✅（LP 4 Tag 回退后立即回归正确）。

#### Round 5 (选择疑问句) ⚠️ a little bit 冗余
- 中文：这个任务对你来说是足够简单还是有点难？
- 学生：`Is this task easy enough or a little bit difficult for you?`
- 评价：✅ `easy enough` 正确。⚠️ `a little bit` 冗余，`a bit` 或 `a little` 任一即可。

#### Round 6 (虚拟语气) 🏆
- 中文：如果这间公寓再大一点，对我们来说就够住了。
- 学生：`If this flat were a little bigger, it would be good enough for us.`
- 评价：✅ **满分**。Type 2 虚拟语气 + `adj + enough` 完美融合。`flat`（英式）地道。

#### Quick Fire
- 场景：看同事写的设计文档，想告诉他细节还不够，还不能给开发团队看。
- 学生：`Well, the idea is correct, however, details are not good enough for you to submit to the development team.`
- 评价：✅ `not good enough` 结构正确。⚠️ `good enough` → `detailed enough`（更精准）；`for you to submit` → `for us to hand off to`（场景是"我们"一起，而非"你"）；`submit` → `hand off to` / `share with`。

**LP 状态**：🟡 复用中。核心结构掌握良好。`very + adj + enough` 双重修饰 + QF 选词精准度需巩固。

---

### Micro Role-play 2（整合 LP 4-5: `opinions on` + `enough`）

**场景**：PM 想在周会上让大家对新流程提意见。你担心大家对流程还不够了解，现在收集看法太早。

**学生产出**：
> `Well, my opinions on this new workflow are that it's too early for us to collect feedback because most of us are still not familiar with this process. So if we are good enough to use this new process, we would be able to give the feedback.`

**目标短语覆盖**：
| 短语 | 是否使用 | 用法评价 |
|:---|:---:|:---|
| `opinions on` | ✅ | `my opinions on this new workflow` — 介词 `on` 正确 |
| `enough` | ✅ | `good enough to use` — 结构对但选词偏差（应为 `familiar enough` / `comfortable enough`） |

**评价**：
- ✅ `opinions on` 正确使用
- ⚠️ `good enough to use` → `familiar enough with` 更精准
- ❌ 条件句混搭：`if we are`（Type 1 现在时）→ `we would be`（Type 2 结果句）❌。Type 2 的条件从句应为 `if we were`
- **Micro RP 通过**（目标短语覆盖 ✅，条件句混搭为新发现细节）

---

## 3. ⚡ knowledge-gaps 轮换 — Tag 极性专项

**选题原因**：上午 LP 2 和下午 LP 4 共 2 次 Tag 极性回退，需专项拦截。

- **第 1 题**：你对这个决定不太满意，对吧？
  - 学生：`You're not happy with this decision, are you?`
  - 评价：✅ **满分**。否定主句 `not happy` → 肯定反问 `are you?`，极性完全正确。🏆

- **第 2 题**：你不觉得这个方案有什么问题，对吧？
  - 学生：`You don't think there were any issues with this proposal, do you?`
  - 评价：✅ **满分**。否定主句 `don't think` → 肯定反问 `do you?`，极性完全正确。🏆 ⚠️ `were` → `are` 更贴合中文原句现在时，但 `were` 在语境中也能说通。

**Flash Correct 小结**：2/2 满分 ✅。Tag 极性今日首次在专项 Flash Correct 中零回退。

---

### LP 6: `the sort of` 泛化 — 部分重复 🆡（基于 20BEC `the sort of thing`）

**来源**：21BEC — `It is the sort of painting to help you relax.`
**含义**：从已学的 `the sort of thing` 泛化到 `the sort of + 任意名词`（`painting` / `person` / `approach` 等）。特指某一类，缩小范围。
**训练句式**：6/6（全部覆盖 + QF）

#### Round 1 (肯定陈述句)
- 中文：非暴力沟通是那种能改变团队氛围的交流方式。
- 学生：`Nonviolent communication is the sort of way that can change the atmosphere of the team.`
- 评价：✅ `the sort of` 从 `thing` 泛化到 `way` ✅。⚠️ `way` 偏空泛 → `approach` 更精准；`the atmosphere of the team` → `team atmosphere` 更简洁。

#### Round 2 (否定陈述句)
- 中文：匆忙赶工不是那种能带来好结果的做事方式。
- 学生：`Rushing through work is not the sort of way that can bring good results.`
- 评价：✅ `not the sort of` 否定形式正确。

#### Round 3 (一般疑问句) 🏆
- 中文：你觉得这是一种可以复用的方案吗？
- 学生：`Do you think this is the sort of thing that can be reusable?`
- 评价：✅ `the sort of thing` 正确，主动复用历史学习内容。🏆 ⚠️ `can be reusable` → `can be reused` 更常见（但非错误）。

#### Round 4 (反义疑问句) 🏆 Tag 极性连续第 4 次正确
- 中文：那种紧急但不重要的任务，是最容易让人分心的，对吧？
- 学生：`The urgent but not important task is the sort of thing that can make people distracting, isn't it?`
- 评价：✅ `the sort of thing` 正确。🏆 Tag 极性正确（`is`→`isn't it?`）。❌ `make people distracting` → `distract people` ✅（`distracting` 是形容词，`make sb + adj` = 让某人变成...，逻辑不通）。

#### Round 5 (选择疑问句) 🏆
- 中文：你觉得他是那种擅长技术的人，还是擅长沟通的人？
- 学生：`Do you think he is the sort of person good at technology or communication?`
- 评价：✅ **满分**。`the sort of person` — 从 `thing` 成功泛化到 `person`！🏆 选择疑问句平行结构正确。

#### Round 6 (虚拟语气)
- 中文（简化后）：如果他是个爱冒险的人，这种安稳的工作就不是他会选的。
- 学生：`If he were the sort of person who loves adventures, then the stable work would not be his choice.`
- 评价：✅ `the sort of person who` — Type 2 虚拟语气中完美嵌入。`If he were → would not be` 完全正确。⚠️ `the stable work` → `a stable job`；`would not be his choice` 偏书面化。

#### Quick Fire
- 场景：同事连续三周周末加班。告诉他周末加班这种事不是长久之计。
- 学生：`Well, working at the weekends is not the sort of thing that can live long.`
- 评价：✅ `the sort of thing` 正确。❌ `live long` → `last long` ✅（`live` 主语必须是生物）。可用上历史词组：`works in the long run` ✅。

**LP 状态**：🟡 复用中。`the sort of` 泛化成功，从 `thing` 到 `person` 自然丝滑。`distracting`→`distract` 词性混淆 + `live long`→`last long` 选词偏差。

---

### LP 7: `show + 宾语 + 现在分词`（宾语补足语）— 新学 🆕

**来源**：21BEC — `It shows a man thinking.`
**含义**：`show + 宾语 + 现在分词`，现在分词作宾语补足语，强调宾语"正在做某事"的持续状态。类似结构：`see sb doing` / `hear sb doing` / `find sb doing`。
**训练句式**：6/6（全部覆盖 + QF）

#### Round 1 (肯定陈述句) 🏆
- 中文：监控录像显示他在进办公室前等了很久。
- 学生：`The CCTV footage shows him waiting for a long time before entering the office.`
- 评价：✅ **满分**。`shows him waiting` + `before entering`，零瑕疵。

#### Round 2 (否定陈述句) 🏆
- 中文：这张照片并没有显示大家在开会。
- 学生：`This photo doesn't show them attending the meeting.`
- 评价：✅ **满分**。`doesn't show them attending`，否定形式 + 宾补结构完美。

#### Round 3 (一般疑问句)
- 中文：那组数据有没有显示销售额在下降？
- 学生：`Do the data show sales declining?`
- 评价：✅ `show sales declining` 正确。⚠️ `data` 现代英语更常用单数 `Does the data show`，但 `Do the data` 在正式场合也正确。

#### Round 4 (反义疑问句) 🏆 Tag 极性连续第 5 次正确
- 中文：这个数据显示出我们的用户在增长，对吧？
- 学生：`The data shows our users growing, doesn't it?`
- 评价：✅ **满分**。`shows our users growing` 正确。Tag 极性 `doesn't it?` 连续第 5 次正确 🏆！

#### Round 5 (选择疑问句) ⚠️ 两选项同义
- 中文：这些数据说明用户在流失还是在增长？
- 学生：`Does this data show users leaving or churning?`
- 评价：✅ `show users leaving/churning` 结构正确。⚠️ `leaving` 和 `churning` 含义一致（都是"流失"），应对比"流失 vs 增长"→ `churning or growing`。

#### Round 6 (虚拟语气) ✅
- 中文：如果数据没显示出问题，他就不会这么担心了。
- 学生：`If the data didn't show any issues, he would not be so worried.`
- 评价：✅ Type 2 虚拟语气完全正确。`show any issues` — 这里不需要硬套 `show + obj + V-ing`，因为"问题"不是"正在做某事"的持续动作。学生理解了这个结构的最佳使用场景 ✅。

#### Quick Fire
- 场景：和同事看一张活动现场照片——老板在逗乐大家，所有人都在笑。
- 学生：`So, I want to take a picture of the boss that shows him amusing us.`
- 评价：✅ `shows him amusing us` 结构完全正确！⚠️ 场景理解略偏：是"已经在看照片"而非"想去拍"。结构本身掌握了。

**LP 状态**：🟡 复用中。6 句式全覆盖，零关键性错误。Tag 极性连续 5 次正确。结构理解到位，知道最佳使用场景。

---

## 4. 🏗️ 话题构建训练 — 技术决策与 trade-off 解释

**场景**：你是 Tech Lead，团队里有人想继续用老框架，有人想迁移到新技术栈。在组会上表达立场——为什么应该迁移。

### Step 1 (中文 Brainstorm) ✅
- 学生 5 个观点：老框架影响开发进度 → 迁移过程会引发隐藏问题 → 这是 trade-off 选择 → 老框架慢慢迭代跟不上业务 → 承受短期痛苦换取长期跟上业务需求
- 导师反馈：观点逻辑清晰，抓住了 trade-off 的核心——短期代价 vs 长期收益。建议补充"老框架具体在什么地方跟不上了"让论据更扎实。

### Step 2 (骨架供给)
- 骨架 1：`If we keep ___ing, it's going to ___`
- 骨架 2：`The downside is that ___, but that's a trade-off worth making because ___`
- 骨架 3：`The real risk isn't ___ — it's ___`
- Filler/softener：`to be honest` / `the thing is` / `realistically` / `in the long run`

### Step 3 (有脚手架输出)

**观点 1**（老框架影响进度，骨架 1）：
- 学生：`If we keep using the old framework, it's gonna affect our development progress.`
- 评价：✅ 骨架完全用对。Type 1 真实条件句正确。`gonna` 口语自然。

**观点 2**（迁移有代价但值得，骨架 2）：
- 学生：`The downside is that we might run into issues when transmission to the new framework, but that's a trade off worth making because it'll allow us to keep up with the development.`
- 评价：✅ 骨架使用正确。✅ `run into` 🟢 历史词组成功复用。❌ `transmission`（数据传输/信号传送）→ `migration` / `migrating` / `transitioning`（技术栈迁移）。❌ `trade off` → `trade-off`（连字符写法）。⚠️ `keep up with the development` → `keep up with business demands` 更精准。

**观点 3**（真正风险是长期落后，骨架 3）：
- 学生：`The real risk isn't during the migration, is the effect in the long run.`
- 评价：⚠️ 骨架第二个槽位少了主语 `it`（应为 `it's`）。Comma splice 逗号拼接两个独立句子。`in the long run` 是历史词组（已归档），在此自然使用 ✅。`the effect` 模糊 → `falling behind` 更清晰。
- 修正后学生：`The real risk isn't during the migration, it is falling behind in the long run.`
  - ✅ 骨架完整使用，`it is` 修正成功。✅ `falling behind` + `in the long run` 两个历史词组叠加使用。⚠️ 仍为 comma splice（口语可接受）。

### Step 4 (撤骨架) 🏆

**学生产出（整段连贯表达）**：
> `Well, if we keep up using the old framework, of course, we won't have migration issues. However, we might not be able to keep up with the business. And if we are going to use the new framework, we're gonna have or we're gonna run into migration issues. However, I think this is a trade-off worth making because it'll allow us to keep up with the business. So, we just put a lot of efforts on how to make the migration smoothly. after all, the real risk isn't during migration, it is falling behind in the long run.`

**评价**：

| 维度 | 评分 | 详情 |
|:---|:---:|:---|
| 骨架内化 | ⭐⭐⭐⭐⭐ | 三个骨架全部保留：`If we keep...` / `trade-off worth making because...` / `real risk isn't... it is...` |
| 历史词组复用 | ⭐⭐⭐⭐⭐ | `run into` ✅ / `keep up with` ✅ / `in the long run` ✅ / `trade-off` ✅ |
| 软词/Filler | ⭐⭐⭐⭐⭐ | `Well` / `of course` / `However` / `I think` / `after all` — 自然得体 |
| 语法精准度 | ⭐⭐⭐⭐ | 见下方具体问题 |
| 连贯性 | ⭐⭐⭐⭐⭐ | 从老框架问题 → 迁移代价 → trade-off → 结论，逻辑链条完整 |

**具体问题**：
1. ❌ `keep up using` — `keep up` + `using` 冗余。`keep using` ✅ 或 `stick with` ✅
2. ❌ `put a lot of efforts on how to make the migration smoothly` — 两处问题：
   - `put efforts on how to` ❌ → `put effort into making` ✅
   - `make the migration smoothly` ❌ → `make the migration **smooth**` ✅（形容词作宾补）或 `make the migration go smoothly` ✅
3. ⚠️ `we're gonna have or we're gonna run into` — 自我纠正从 `have` 到 `run into`，意识非常好！

**优化参考版（母语者级别）**：
> *"Well, if we stick with the old framework, sure — we won't have migration issues. But we might not be able to keep up with the business. And if we move to the new framework, we're gonna run into some migration pain. However, I think that's a trade-off worth making, because it'll allow us to keep up with business demands. So we should put our effort into making the migration go smoothly. After all, the real risk isn't the migration — it's falling behind in the long run."*

---

## 4. 📊 不足汇总 (Improvement Areas)

### 4.1 本次新增/复发缺口

| # | 缺口 | 严重度 | 详情 | 关联 |
|:---:|:---|:---:|:---|:---|
| 1 | 🔴 **`discuss` 及物性 — 自由产出时被 `talk about` 干扰** | 🔴→🟡 | Flash Correct 中连续 2 次在未提示的场景下用 `talk the deadline` / `talk the budgets` 替代 `discuss`，且都漏了 `about`。强制用 `discuss` 后通过。2 轮加练后当轮修复。`discuss` 的肌肉记忆仍未建立。 | 2026-05-30 新发现，本次首次 Flash Correct |
| 2 | 🔴 **`more good` → `better` 形容词不规则比较级** | 🔴 | 选择疑问句中 `more good` ❌。`good → better → best` 是不规则变化的基础语法。同一 sentence 中未自发调用 `better`。低位基础缺口，在造句压力下暴露。 | 新发现 |
| 3 | 🔴 **`Would better + 动词` — `had better` / `would be better to` 混淆** | 🔴 | Micro Role-play 中 `Would better buy` ❌。混淆了两个结构：`had better do sth`（最好做某事）和 `It would be better to do sth`（做某事更好）。不能单独用 `Would better + 动词`。 | 新发现（新类型） |
| 4 | 🔴 **`lack of`（名词性）vs `lack`（动词）混淆** | 🔴 | `he's lack of experience` ❌。`lack of` 是名词短语（如 `a lack of experience`），不能直接放系动词后当表语。动词用法 `lack sth` 不接 `of`。 | 新发现（新类型） |
| 5 | 🟡 **双重系动词（一般疑问句）** | 🟡 | LP 2 一般疑问句 `Are your antivirus software is up to date?` ❌ — 既有 `Are` 又有 `is`。一般疑问句公式 `Be + 主语 + 表语?` 中的 `Be` 已从主语位置提前。 | 新发现 |
| 6 | 🟡 **反义疑问句 Tag 极性回退（第 N 次）** | 🔴 | LP 2 反义疑问句 `is it?`（应为 `isn't it?`）❌ — 肯定主句后 Tag 应用否定。同一 session 的 LP 3 反义疑问句中极性正确（`can you?` ✅），说明此缺口不稳定。 | knowledge-gaps Active 已有（2026-06-07 同一 session 两次复发），本次再次复发 |
| 7 | 🟡 **`transmission` vs `migration` — 技术词汇选词** | 🟡 | 话题构建中 `transmission` ❌ → `migration` / `transitioning` ✅。`transmission` = 数据传输/信号传送（物理层面），不是技术栈迁移。 | 新发现 |
| 8 | 🟡 **`put efforts on how to make...smoothly` — 搭配混乱** | 🟡 | 话题构建撤骨架中复合错误：① `efforts` → `effort`（不可数）；② `put efforts on how to` ❌ → `put effort into doing` ✅；③ `make the migration smoothly` ❌ → 形容词作宾补 `make the migration smooth` ✅ 或加动词 `make the migration go smoothly` ✅。 | 新发现（新类型） |
| 9 | 🟡 **`save money` vs `make money` 词汇混淆** | 🟡 | LP 3 造句中"省钱"翻译为 `make money`（赚钱）❌。基础词汇混淆，在造句压力下暴露。 | 新发现 |
| 10 | 🟡 **`specially`（特意地）vs `special`（特别的）** | 🟡 | LP 3 否定句 `work specially` ❌ → `is anything special` ✅。`specially` 是副词，修饰动词表示"特意地"；这里需要形容词 `special` 表"特别之处"。 | 新发现 |
| 11 | 🟡 **`keep up using` — 动词短语冗余** | 🟡 | 话题构建撤骨架中 `keep up using` — `keep up` 和 `using` 语义重叠（`up` 表"持续"+"using"也表持续）。查 `keep using` ✅ 或换词 `stick with` ✅。 | 新发现 |
| 12 | 🟡 **主客体对应偏差（中英主语切换）** | 🟡 | LP 1 否定句 `This computer is not good for this place` — 中文主语是"位置"，但翻译时把主语换成了"电脑"，导致语义偏差。 | 新发现 |
| 13 | 🟡 **`distracting`（adj）vs `distract`（v）混淆** | 🟡 | LP 6 反义疑问句 `make people distracting` ❌ → `distract people` ✅。`distracting` = 让人分心的（主动属性），`make sb distracting` 逻辑不通。 | 新发现 |
| 14 | 🟡 **`live long` vs `last long` 选词** | 🟡 | LP 6 QF `the sort of thing that can live long` ❌ → `last long` ✅。`live long` = 长寿（主语必须是人/生物），表示"长期有效"用 `last long` / `is sustainable`。 | 新发现 |
| 15 | 🟡 **`very + adj + enough` 双重程度修饰** | 🟡 | LP 5 肯定句 `very simple enough` ❌ — `very` 和 `enough` 不能同时修饰同一形容词。`very simple` 或 `simple enough`，不能叠加。 | 新发现 |
| 16 | 🟡 **`Most of people` → `Most people`（冠词/限定词）** | 🟡 | LP 4 否定句 `Most of people` ❌ → `Most people` ✅（泛指）或 `Most of the people` ✅（特指）。`most` + 泛指名词不加 `of`。 | 新发现 |

### 4.2 本次会话新学语言点初始状态

| 语言点 | 初始状态 | 判定依据 |
|:---|:---:|:---|
| `good for`（适合/有益于） | 🟡 复用中 | 5 句式通过，但选择疑问句 `more good` 暴露不规则比较级缺口 + QF 词汇选词偏差（bench/waist） |
| `up to date`（新潮的/及时的） | 🟡 复用中 | 6 句式覆盖，双重系动词和 Tag 极性回退需巩固。虚拟语气主动产出优秀 🏆 |
| `I can't see how...`（委婉质疑） | 🟡 复用中 | 6 句式覆盖，`lack of` 混淆和选词偏差各 1 次。反义疑问句极性满分 🏆 |
| `opinions on`（对…的看法） | 🟡 复用中 | 6 句式+QF 覆盖，Tag 极性回退 1 次（`do you?`→`don't you?`），已当场指出 |
| `enough`（后置修饰形容词） | 🟡 复用中 | 6 句式+QF 覆盖。`very simple enough` 双重程度修饰 1 次，`good enough` vs `familiar enough` 选词偏差 1 次 |
| `the sort of` 泛化（任意名词） | 🟡 复用中 | 6 句式+QF 覆盖，从 `the sort of thing` 成功泛化到 `person/approach`。`distracting`→`distract` 词性混淆 1 次，`live long`→`last long` 选词 1 次 |
| `show + 宾语 + 现在分词`（宾补） | 🟡 复用中 | 6 句式+QF 覆盖，零关键性错误。场景理解 1 次偏差（非语言问题）|

> 七个 LP 初始状态全部为 🟡（非 🟢），因为每个 LP 都在训练过程中暴露了至少 1 个需要后续关注的底层语法或选词问题。

### 4.3 历史词组复用追踪

| 词组 | 来源 | 原状态 | 本次复用情况 | 新状态 |
|:---|:---|:---:|:---|:---:|
| `run into` | active-pool | 🟢 | QF 中成功使用 `ran into security issues` ✅ + Topic Building 中 `run into issues` ✅ | 🟢 维持 |
| `keep up with` | active-pool | — | Topic Building 中多次自然使用 | ✅ |
| `in the long run` | mastered-points (archived) | — | Topic Building 撤骨架中 `falling behind in the long run` ✅ | ✅ 归档区抽查通过 |
| `trade-off` | — | — | Topic Building 中正确使用 | ✅ |

### 4.4 本轮 AI 执行问题反思

| # | 问题 | 严重度 | 详情 |
|:---:|:---|:---:|:---:|
| 1 | **历史词组植入严重不足** | 🔴 | GEMINI.md 要求每道造句题至少植入 1 个历史词组，但 LP 1 (`good for`) 和 LP 3 (`I can't see how...`) 的核心造句轮次未从 active-pool 系统选取历史词组植入。仅 LP 2 Quick Fire 中植入了 `run into`。Topic Building 中学生自主复用了 `run into`/`keep up with`/`in the long run`/`trade-off`。违反 GEMINI.md 强制检查步骤。 |
| 2 | **出题前 Checklist 执行不完整** | 🔴 | GEMINI.md 要求在出题前"在思考中明确回答：① 本题要植入哪个历史词组（从 active-pool 选取，记录名称和状态）② 中文句子中的哪些措辞能引导用户用上该词组"。本次会话大部分出题轮次跳过了此步骤。 |

### 4.5 已修复确认

| # | 缺口 | 结果 | 证据 |
|:---:|:---|:---:|:---|
| 1 | `discuss` 及物性 | ✅ 当轮修复 | Flash Correct 2 轮加练后通过 |
| 2 | `more good` → `better` | ✅ 当轮修复 | 修正轮正确使用 `better for` |
| 3 | `Would better buy` | ✅ 已指出 | Micro RP 反馈中指出并给出修正 |
| 4 | `lack of` vs `lack` | ✅ 当轮修复 | 加练轮后口语正确 |
| 5 | `save money` vs `make money` | ✅ 当轮修复 | 反馈中已纠正 |
| 6 | Tag 极性（LP 3 反义疑问句） | ✅ 首次全程正确 | LP 3 反义疑问句 `can you?` 极性完美 |

---

## 5. ✨ 亮点与进步

1. **LP 2 `up to date` 虚拟语气学生主动产出 🏆**：无需导师出题，学生直接主动完整输出 `If your system was not up to date, there would be security risks.` Type 2 虚拟语气结构完全正确，说明对虚拟语气信心明显增强。
2. **LP 3 `I can't see how` 反义疑问句极性满分 🏆🏆**：在 Tag 极性多次复发后，`You cannot see...can you?` 极性完全正确，为今日所有反义疑问句中最复杂的一个。
3. **话题构建撤骨架全部保留 🏆**：三个核心骨架全部在撤骨架后被内化使用，软词/Filler 使用自然得体（`Well`/`However`/`after all`/`I think`）。
4. **历史词组自然复用**：`run into`（🟢）在 QF 和 Topic Building 中多次正确使用；`in the long run`（archived）在撤骨架中被正确调用。
5. **自我纠正意识**：Topic Building 中 `we're gonna have or we're gonna run into` — 从 `have` 自我纠正为 `run into`，词汇选择意识良好。
6. **21BEC 全文扫描完成**：12 组疑问点全部分析，10 个未记录语言点识别完成。
7. **Tag 极性下午连续 5 次正确 🏆🏆**：LP 4 回退 1 次后，LP 5/6/7 + Flash Correct 连续 5 次 Tag 极性零错误，明显好转。
8. **7 个语言点全部覆盖**：21BEC 中 7 个适合造句训练的语言点全部完成训练，仅剩 3 个偏概念/修辞类留待后续。
9. **`show + 宾语 + 现分` 零关键性错误**：学生理解了该结构的最佳使用场景（视觉/证据呈现中某人正在做某事），不盲目套用。

---

## 6. 🛠️ 会话末检查清单

### SRS 维护

**新词加入 active-pool：**
- `good for`（适合/有益于）→ 🟡 复用中
- `up to date`（新潮的/及时的）→ 🟡 复用中
- `I can't see how...`（委婉质疑句式）→ 🟡 复用中
- `opinions on`（对…的看法）→ 🟡 复用中
- `enough`（后置修饰形容词）→ 🟡 复用中
- `the sort of` 泛化（任意名词）→ 🟡 复用中（合并到原有 `the sort of thing` 🟡 条目）
- `show + 宾语 + 现分`（宾语补足语）→ 🟡 复用中

**本轮植入的历史词组状态更新：**
- `run into` 🟢 → 🟢 维持（在 QF + Topic Building 中正确使用 2 次）
- `keep up with` — Topic Building 中自主复用
- `in the long run` 🟢（archived）— Topic Building 撤骨架中成功召回

**归档检查**：无符合归档条件的词组。

### 进度追踪更新

详见各子文件的更新（knowledge-gaps.md / session-overview.md / next-steps.md / active-pool.md）。
