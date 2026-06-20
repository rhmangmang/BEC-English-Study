# Session Notes: 2026-06-20

## 0. 会话概述
- **扫描文本**：23BEC.md（补齐遗留 LP）+ 24BEC-10s.md（全新扫描）
- **23BEC 扫描结果**：5 个已记录 LP（06-16 完成），1 个未完成（`if you wish` 仅 1/6），3 个未开始（`give a presentation on` / `have + 时间 + to do` / `while you prepare`）
- **24BEC-10s 扫描结果**：学生 14 组问答中提取 6 个未记录 LP，其中 4 个完成训练、2 个跳过
- **实际训练**：Flash Correct × 3 组（Tag 极性/代词、many/much、have sb do）+ LP 1-8 训练 + Micro Role-play × 2 + 概念辨析（`go over` vs `go through`、`ground` 隐喻义、`testing` 作主语）
- **跳过的语言点**：`give a presentation on` / `for + noun` / `every + 数字 + 时间单位` / `while + doing`（非学生提问）
- **模型**：deepseek-v4-pro

---

## 1. ⚡ 定向纠偏 (Flash Correct)

### 组 1：Tag 极性 + 代词匹配（knowledge-gaps 🔴 Active）
**选题原因**：Tag 极性 2026-06-07 同一 session 两次复发，Tag 代词 2026-05-05/05-22 均有复发记录。

**规则**：主句肯定 → Tag 否定；主句否定 → Tag 肯定。Tag 代词必须与主句主语人称/数一致。

- **Round 1**: "你们团队已经在用这个新系统了，不是吗？"
  - 学生：`Your team has already been using this new system, haven't you?`
  - 评价：✅ 时态 `has been using` 正确。🔴 **Tag 代词不匹配**：主句 `your team`（第三人称）→ Tag 用了 `haven't you?`（第二人称）。纠正：`haven't they?` / `hasn't it?`。**本轮加练**。

- **Round 1b（加练）**: "你的经理已经看过这份报告了，对吧？"
  - 学生：`Your manager has already seen this report, hasn't he?`
  - 评价：✅ Tag 代词 `manager → hasn't he?` 完全正确。极性/时态/代词三要素全部到位 🏆。修复成功。

- **Round 2**: "你不打算参加明天的会议，是吗？"
  - 学生：`You don't want to attend tomorrow's meeting, do you?`
  - 评价：✅ Tag `don't...do you?` 极性/代词/时态全对。⚠️ `don't want to` = 不想（意愿），中文「不打算」更贴合 `don't plan to` / `aren't planning to`。

**组 1 小结**：2/3 初始通过 + 1 次加练修复。Tag 代词匹配（`team → you`）再次复发，当场修复。

---

### 组 2：`many/much` 辨析（knowledge-gaps 🔴 Active）
**选题原因**：2026-06-06 复发（`as much needs` ❌），从 Monitoring 重新激活至 Active。

**规则**：可数名词用 `many`，不可数用 `much`。复合缺口：`too more` ❌ → `too many` ✅。

- **Round 1**: "这个功能有太多 bug 了，我们不能再延期上线。"
  - 学生：`There are a lot of bugs with this feature. We cannot delay the launch anymore.`
  - 评价：❌ 用 `a lot of` 回避了 `too many`。`a lot of` = 中性描述数量大，`too many` = 超出合理范围的「太多」。**本轮加练**。

- **Round 1b（加练）**: 重出同句
  - 学生：`There are too many bugs with the feature. We cannot delay the launch anymore.`
  - 评价：✅ `too many bugs` 正确。⚠️ `bugs with the feature` → `bugs in this feature` 更自然。

- **Round 2**: "这些需求涉及太多变更了，我们没有足够的时间来重新评估。"
  - 学生：`There are too many changes involved in these requirements, we don't have enough time to reassess them.`
  - 评价：✅ `too many changes` 连续两轮正确。`reassess` 精准。⚠️ 逗号连接两个独立句（Monitoring 中 `as a result` 同样问题）。

**组 2 小结**：1/2 初始回避 + 1 次加练修复。`too many`/`too more` 混淆本轮未触发。

---

### 组 3：`have sb do`（knowledge-gaps 轮换，使役动词无 to）
**选题原因**：2026-05-03 发现，2026-06-07 `let sb to do` + `allow` 混淆复发。按 `knowledge-gaps` 轮换规则取此类别。

- **Round 1**: "PM 让我们在周五之前把所有的测试用例跑完。"
  - 学生：`the PM let us finish all the test cases by Friday.`
  - 评价：✅ `let us finish` 无 to，`let sb do` 规则守住。⚠️ 中文「让」在此偏"安排/要求"而非"允许" → `have sb do` 更精准。

- **Round 2**: "测试环境又挂了——我让运维帮忙查一下原因。"
  - 学生：`The test environment doesn't work again. I'll have the maintainer find the root cause.`
  - 评价：✅ `have the maintainer find` 使役动词无 to 正确。⚠️ `maintainer` = 开源项目维护者，运维 = `ops guy` / `the ops team`。⚠️ `doesn't work again` → `is down again`（环境挂掉的标准说法）。

**组 3 小结**：2/2 初始通过。`let sb do` / `have sb do` 无 to 本轮零回退。

---

## 2. 📝 核心语言点训练

---

### LP 1: `if you wish` — 补齐 23BEC 遗留 🔄

**来源**：23BEC — `you can make notes if you wish while you prepare`
**含义**：`if you wish` = if you want to / if you'd like to，句末软化建议，给予对方选择权。
**上次进度**：2026-06-16 仅完成肯定陈述句（1/6 + 无 QF）
**本次补齐**：否定句 → 特殊疑问句 → 反义疑问句 → 选择疑问句 → Quick Fire（虚拟语气跳过）

#### Round 2（否定陈述句）— 植入 `from your perspective` 🔴 → AI 失职
- 中文：如果你不想参与讨论，你完全可以保持沉默，如果你愿意的话。
- 学生：`If you don't want to join the discussion, you can completely keep silent, if you wish.`
- 评价：✅ `if you wish` 句末位置正确。⚠️ `completely keep silent` 略显生硬 → `just stay quiet`。🔴 **AI 自检失职 #1**：声明植入 `from your perspective` 但中文句中没有对应措辞。

#### Round 3（特殊疑问句 — 重出 ×1）
- 原第 1 版中文被学生当场质疑"怎么才能把 if you wish 植入进去"。AI 承认句子不兼容。
- 重出中文：从你的角度看，如果你愿意的话，我们该怎么调整这个流程让它更高效？
- 学生：`From your perspective, if you wish, how can we adjust the process to make it more effective?`
- 评价：✅ `if you wish` + `from your perspective` 🏆 双 LP 同时用上。⚠️ `if you wish` 夹在中间略显卡顿 → 移至句末更顺。

#### Round 4（反义疑问句）
- 中文：你可以先看看文档熟悉一下内容，如果你想的话，对吧？
- 学生：`You can read the document to get familiar with the content, if you wish, can't you?`
- 评价：✅ Tag `can't you?` 极性/代词/时态全对。⚠️ `if you wish` 和 `can't you?` 句末重复征求。🏆 **亮点**：`get familiar with` 避开了 `familiar with` vs `used to` 混淆坑。

#### Round 5（选择疑问句 — 重出 ×3）
- 第 1 版被学生质疑"别扭"。
- 第 2 版被学生质疑"别扭"。 
- 第 3 版被学生质疑"哪个表达对应 if you wish"。AI 承认「看你自己」对应 `up to you` 不是 `if you wish`。
- 第 4 版中文：你想让我直接讲重点，还是你先自己看一遍——如果你想的话？
- 学生：`Do you want me to tell you the high points directly, or do you want to look at it by yourself first, if you wish?`
- 评价：✅ `if you wish` 句末自然。⚠️ `high points` = 亮点/高光时刻 → `key points` / `main points` ✅。

**句式 6（虚拟语气）**：⏭️ 跳过。`if you wish` 本身是条件软化结构，塞入 Type 3 不自然。

#### Quick Fire
- 场景：同事讨论代码审查流程，你想给他加一轮检查的选择权。
- 中间学生问 `go over` vs `go through` 区别（概念辨析）：`go over` = 快速浏览/讲要点（浅），`go through` = 仔细通读/逐条审查（深）。
- 学生：`you can add one more check if you wish.`
- 评价：✅ 简洁、准确、自然 🏆。

**LP 状态**：🟡 补齐至 5/6 + QF。选择疑问句出题 3 次失败暴露 `if you wish` 在平行结构中的语序适配问题。

**历史词组植入**：`from your perspective` ✅（第 1 次成功使用）。

---

### LP 2: `give a presentation on` — ⏭️ 用户跳过

学生说：`please skip this language point because I think it's not worth practicing.`

---

### LP 3: `have + 时间 + to do` — 23BEC 新学 🆕

**来源**：23BEC 原文 `You will have about a minute to prepare for this`
**含义**：`have + 时间段 + to do` = 拥有人/时间去完成某事。职场高频口语句式。
**训练句式**：6/6（全部覆盖 + QF）

#### Round 1（肯定陈述句）— AI 自检：植入失职 #2
- 中文：面试前你有大概十分钟时间来看一遍案例材料。
- 学生：`You have about 10 minutes to go over the cases before interview.`
- 评价：✅ `have 10 minutes to go over` 精准。⚠️ `before interview` → `before the interview`（可数名词单数需冠词）。🔴 **AI 自检失职 #2**：声明植入 `from your perspective` 但中文句中没有。

#### Round 2（否定陈述句）— 植入 `get onboard with` 🔴
- 中文：大部分新人没有足够的时间来上手新系统，因为培训只安排了半天。
- 学生：`Most of the newcomers don't have enough time to get onboard with the new system because the training is arranged just for half a day.`
- 评价：✅ `don't have enough time to get onboard with` 🏆 `get onboard with` 🔴 初次成功复用（06-16 刚修复）。⚠️ `is arranged` 偏生硬 → `was only scheduled for half a day`；`Most of the newcomers` 可简化为 `Most newcomers`。

#### Round 3（特殊疑问句）— 🔴 关键性错误：目标结构未使用 → 加练
- 中文：你觉得我们需要多长时间来准备这个演示？从你的角度看。
- 学生：`From your perspective, how long do you think we need to prepare this presentation?`
- 评价：🏆 `from your perspective` 🔴 成功。🔴 **目标结构未使用**：`need to prepare` 回避了 `have time to prepare`。**本轮加练**。⚠️ `prepare this presentation` → `prepare **for** this presentation`（`prepare sth` = 制作材料，`prepare for` = 为某事做准备）。

- **加练轮**：小组讨论之前，我们有多长时间来整理自己的思路？从你的角度看。
- 学生：`Before the group discussion, how long do we have to prepare our own ideas from your perspective?`
- 评价：⚠️ `do we have to prepare` 产生歧义（=`must` prepare vs `have time` to prepare）。建议用 `how much time` 消歧。⚠️ `prepare our own ideas` → `organize our thoughts`。🏆 `from your perspective` 连续两轮成功。

#### Round 4（反义疑问句）— AI 自检：本轮未植入历史词组 #3
- 中文：正式上线之前，我们还有一周时间来修复这些 bug，不是吗？
- 学生：`Before the formal launch, we have one week to fix these bugs, don't we?`
- 评价：✅ `have one week to fix` 精准。✅ Tag `don't we?` 正确——`have` 作实义动词时 Tag 用 `do` 做助动词。⚠️ `formal launch` → `official launch`。🔴 **AI 自检失职 #3**：未在出题前声明并植入历史词组。

#### Round 5（选择疑问句）— 双词组植入：`enough` 🟡 + `or anything` 🟡
- 中文：你觉得我们有足够的时间来通读整份文档，还是应该先看看摘要之类的就好？
- 学生：`Do you think we have enough time to go through the whole document, or should we first look at the summary or anything?`
- 评价：✅ `have enough time to go through` 精准。✅ `enough` 🟡 + `or anything` 🟡 双植入。✅ `Do you think` 后间接疑问句语序正确。⚠️ `or anything` 位置可优化 → 直接贴在名词后面更自然。

#### Round 6（虚拟语气 Type 3）— 🔴 `many/much` 复发
- 中文：如果当初我们有更多时间来测试这个功能，上线后就不会出那么多问题了。
- 学生：`If we had had more time to test this feature, there would not have been so much issues after the launch.`
- 评价：✅ Type 3 `had had → would not have been` 结构正确。🔴 `so much issues` → `so many issues`（`issues` 可数复数）。**`many/much` 在 Flash Correct 中零复发，但在复杂句式压力下再次回退。**

#### Quick Fire
- 场景：主持技术分享，一个分享者没到，确认有没有缓冲时间。
- 学生：`Do you have time to wait for another presenter?`
- 评价：⚠️ `Do you have time` = 问同事"个人有没有时间"，不是确认议程缓冲。→ `Do we have any time to wait?`

**LP 状态**：🟡 复用中。6 句式全覆盖。关键性错误 1 次（R3 未使用目标结构→加练修复）。`many/much` 在虚拟语气压力下复发 1 次。

**历史词组植入**：`get onboard with` 🏆 / `from your perspective` 🏆🏆 / `enough` ✅ / `or anything` ✅

---

### 🎭 Micro Role-play 1（整合 LP 1 + LP 3）

**场景**：Tech Lead 回答同事关于分享准备的问题。融入 `have time to do` 和 `if you wish`。

- 同事问：我这周太忙了，你觉得我需要多长时间来准备这个分享？还有，我要不要自己先讲一遍给你听听？
- **第 1 次回答（理解偏差）**：学生翻译了同事的问题，而不是以 Tech Lead 身份回答。
- **第 2 次回答**：`Well, I think you should have at least a week to prepare for this first presentation, because we have a lot of things to do, and you can also talk to me first if you wish.`
- 评价：✅ `have a week to prepare` + `if you wish` 双 LP 融入。⚠️ `first presentation` 歧义；`talk to me` → `run through it with me`；因果关系反向（事多应该更需要时间）。

**Micro RP 结果**：✅ 通过。两个 LP 自然融入。

---

### 概念辨析（穿插）

- **`go over` vs `go through`**：`go over` = 快速过/讲要点（浅），`go through` = 仔细通读/逐条审查（深）。学生在 Quick Fire LP 1 后提问。
- **`ground` 隐喻义**：`a lot of ground to cover` = 内容量大。`ground` = 话题范围（隐喻为"土地"），常见变体：`common ground`（共识）、`middle ground`（折中）、`break new ground`（开创新领域）。
- **`testing` 作主语**：`Testing missed a lot of bugs` 中 `Testing` = 测试环节/阶段（非人，流程本身）。英文中把流程当主语很常见，不指名道姓，只说结果。

---

### LP 4: `work with / align with the business` — 24BEC 新学 🆕

**来源**：24BEC 老师补充用法 — `work with the business`（对接业务）、`align with the business`（对齐业务）
**含义**：`work with + 部门/团队` = 日常对接协作；`align with sb on + 具体事项` = 目标/需求对齐。`the business` 特指"业务方"。
**训练句式**：6/6（全部覆盖 + QF）

#### Round 1（肯定陈述句）— 🔴 `come across as` 结构错误 #1
- 中文：作为开发，你需要日常对接业务方来收需求，但有时候你给人的感觉是自己心里都没数。
- 学生：`As a developer, usually, you need to work with the business to collect requirements. but sometimes you came across as like you seems unreliable.`
- 评价：✅ `work with the business` 精准。🔴 `came across as like you seems` — 多重堆叠错误：① `came` 时态跳跃（应为 `come` 现在时）；② `as` + `like` 双用；③ `you seems` → `you seem`。

#### Round 2（否定陈述句）— 🔴 `come across as` 结构错误 #2
- 中文：如果你不主动对齐业务方的目标，你提出来的需求很容易被推回来——给人的感觉就是你没做功课。
- 学生：`If you don't actively align with the goal of the business, then the requirements you ask for will be easily pushed back. You will come across as that you don't do any work previously.`
- 评价：✅ `align with` 使用。🔴 `come across as that...` — `as` 后不能接 `that` 从句。❌ `don't do...previously` 时态冲突。⚠️ `align with the business` 比分拆更简洁。

#### Round 3（特殊疑问句）— ⚠️ 词汇偏差
- 中文：在实际项目开始前，你会怎么去对齐业务方的预期？总得有个计划吧。
- 学生：`Before the project starts, how will you align with the business in terms of the anticipation? You should have a plan, all right?`
- 评价：✅ `align with the business` 正确。⚠️ `anticipation` = 期待/预料（情感色彩浓）→ `expectations`（职场标准用词）。**学生主动问** `align with sb on sth` 用法确认——导师确认 `.on + 具体事项` 是固定搭配。

#### Round 4（反义疑问句）— 🔴 `come across as` 结构错误 #3
- 中文：你平时和业务方对接得挺频繁的，对吧？但你给人的感觉是不太喜欢这个过程。
- 学生：`You usually work with the business so frequently, don't you? but you come across as unlike this process.`
- 评价：✅ Tag `don't you?` 正确。🔴 `come across as unlike this process` — `unlike` 是介词（≠不喜欢），不能放 `as` 后跟介词短语。应：`come across as not liking this process`。❌ `usually...so frequently` 冗余。

**穿插 `come across as` 结构速查表**：`as` + 形容词 / 名词短语 / `like`+名词 / `if` 从句 / 动名词（否定）。

#### Round 5（选择疑问句）— ⚠️ 间接疑问句语序复发
- 中文：你觉得在日常工作中，是和业务方日常对接更重要，还是定期对齐目标和预期更重要？说说你的想法。
- 学生：`Which one is more important you think: working with the business on a daily basis or aligning with them on goals and expectations? Please state your thoughts.`
- 评价：✅ `work with the business` + `align with...on` 🏆 双点同时用上。⚠️ `Which one is more important you think` → `Which one do you think is more important`（间接疑问句语序复发）。⚠️ `state your thoughts` → `share your thoughts`。

#### Round 6（虚拟语气 Type 3）— 🏆 满分
- 中文：如果当初我们在一开始就对齐了业务方的预期，这些需求变更就不会看起来像是我们在凭空想象了。
- 学生：`If we had aligned with the business on expectations at the beginning, the requirement changes would not have looked like requests just due to our imagination.`
- 评价：✅ `had aligned with the business on expectations` Type 3 完美融入。✅ 虚拟语气结构完全正确。⚠️ `just due to our imagination` 偏书面 → `just made up` / `pulled out of thin air` 更口语。

#### Quick Fire
- 场景：新功能方案，技术 OK 但不确定业务需求。决定约业务方聊。
- 学生：`Well, I'm going to align with the business on their real requirements.`
- 评价：✅ `align with the business on` 精准，反应快 🏆。

**LP 状态**：🟡 复用中。6 句式全覆盖。Type 3 满分。`come across as` 连续 3 次结构错误（`as like` / `as that` / `as unlike`），在第 5 次（LP 5 R3）最终修复。

**历史词组植入**：`come across as` ❌❌❌（3 次结构错误）

---

### LP 5: `for + noun`（表目的）— ⏭️ 用户跳过

学生说：跳过 + 指出中文句子太长，违反 GEMINI.md 字数限制。AI 承认。

---

### LP 6: `every + 数字 + 时间单位` — ⏭️ 用户跳过

---

### LP 7: `the same thing happens with` — 24BEC 新学 🆕

**来源**：24BEC 原文 `the same thing happens with the technical service stuff`
**含义**：`the same thing happens with + 名词` = 同样的情况也发生在…/…也是同理。用于 A 如此，B 也一样。
**训练句式**：5/6（虚拟语气跳过 + QF）

#### Round 1（肯定陈述句）— AI 自检：植入失职 #4
- 中文：业务方收集需求是这样，技术侧也一样。
- 学生：`The way that the business collects requirements is like this. The same thing happens with the technical side.`
- 评价：✅ `the same thing happens with` 精准。⚠️ `is like this` 偏中式直译。🔴 **AI 自检失职 #4**：声明植入 `come across as` 但中文没有。**学生问** `that's how it works with` 中 `it` 指向 → 导师解释 `it` = 事情/流程本身。

#### Round 2（否定陈述句）— 出题失误
- 第 1 版中文被学生指出语义不匹配（"显得不怎么配合" ≠ "同样的事不发生"）。AI 承认。
- 第 2 版中文：销售团队每周复盘，但研发就没这个习惯。
- 学生：`The sales team does reviews every week. however, the same thing doesn't happen with the development team.`
- 评价：✅ 语义完全匹配 🏆。⚠️ `does reviews` → `holds reviews`；`however` 首字母应大写。🔴 **AI 自检失职 #5**：再次声明植入 `come across as` 但再次放空。

#### Round 3（特殊疑问句）
- 中文：为什么设计评审推进顺畅，代码评审就不行？
- 学生：`Why can the design review be moving so smoothly? but the same thing doesn't happen with the code review.`
- 评价：✅ `the same thing doesn't happen with` 正确。⚠️ `can be moving` → `does go`（情态+进行时叠加奇怪）。

#### Round 4（反义疑问句）— 第 1 版被学生质疑用不上 LP，重出
- 重出版：测试这边漏了很多 bug，安全审计也一样，对吧？
- 学生：`There are a lot of bugs that have not been tested. The same thing happens with the security check, doesn't it?`
- 评价：✅ `the same thing happens with` + Tag `doesn't it?` 正确。⚠️ `have not been tested` ≠ "漏了"（`missed` / `let slip through`）。**学生问** `testing` 含义 → 导师解释 = 测试环节/阶段（流程作主语）。

#### Round 5（选择疑问句）— 🔴 `Does...happens` 主谓不一致
- 中文：是前端这块反复出问题，还是后端也一样？
- 学生：`Does this problem happens just with the front end again and again, or does this same thing happen with the back end also?`
- 评价：✅ `does the same thing happen with` 正确。🔴 `Does...happens` → `does` 后必须用动词原形 `happen`。⚠️ `also` 句末略生硬。

**句式 6（虚拟语气）**：⏭️ 跳过。描述事实性类比，不适合 Type 3 假设。

#### Quick Fire
- 场景：代码质量讨论——前端 code review 意见多，后端一样。
- 学生：`Well, we always come up with many reviews after doing the code review on the frontend. And the same thing happens with the backend.`
- 评价：✅ `the same thing happens with the backend` 自然。✅ `many` 正确（非 `too more`）。⚠️ `come up with reviews` 搭配不当（`come up with` + ideas/solutions，不接 reviews）。

**LP 状态**：🟡 复用中。5/6 全覆盖。关键性错误 1 次（`Does...happens` 主谓不一致）。AI 出题设计失误 2 次（否定句、反义疑问句第 1 版不兼容 LP）。

**历史词组植入**：无成功植入（AI 连续 5 次声称植入 `come across as` 但未写入中文）。

---

### 🎭 Micro Role-play 2（整合 LP 4 + LP 7）

**场景**：Tech Lead 和 PM 聊代码质量。融入 `align with the business` 和 `the same thing happens with`。

- 学生：`Well, after doing the code review on the front end, we've found out a lot of problems, and the same thing happens with the back end. however, the root cause we think is that they have not aligned with the business.`
- 评价：✅ `the same thing happens with` + `aligned with the business` 双 LP 融入 🏆。⚠️ `found out` → `found`/`flagged`（`find out` = 查明事实）；`the root cause we think is that` → `we think the root cause is`；`they` 指代不明。

**Micro RP 结果**：✅ 通过。两 LP 同时用上，逻辑链完整。

---

### LP 8: `development stream` — 24BEC 新学 🆕

**来源**：24BEC 学生问 `It gets put into the development stream` 中 `development stream` 含义
**含义**：`development stream` = 开发流程/开发流水线。`stream` 比喻流程像水流一样连贯推进。
**训练句式**：5/6（虚拟语气跳过 + QF）

#### Round 1（肯定陈述句）— AI 自检：植入失职 #6 ← 实际是同一轮 session 中的连续失职
- 中文：审批过的需求才会进入开发流程。
- 学生：`Only the requirements that have been approved can go into the development stream.`
- 评价：✅ `go into the development stream` 精准，零瑕疵 🏆。

#### Round 2（否定陈述句）— 🏆🏆🏆 `come across as` 结构突破！
- 中文：没对齐业务方的需求不要进开发流程，给人感觉很不靠谱。
- 学生：`Requirements that have not aligned with the business cannot go into the development stream. If we do so, that will come across as unreliable.`
- 评价：✅ `go into the development stream` 精准。🏆🏆🏆 **`come across as unreliable` — `as` 直接加形容词，结构完全正确！** 这是本 session 第 5 次尝试（`as like` → `as that` → `as unlike` → `as if` → **`as adj`**），终于在否定陈述句的语境下修成正果。✅ `align with the business` 跨 LP 自发使用。

#### Round 3（特殊疑问句）— ⚠️ `Who's the boss?`
- 中文：哪些需求应该先进开发流程？谁说了算？
- 学生：`Which requirements should go into the development stream? Who's the boss?`
- 评价：✅ `go into the development stream` 正确。⚠️ `Who's the boss?` = 问组织架构 → `Who gets the final say?` / `Who decides?`。学生修正后 `Who decides?` ✅。

#### Round 4（反义疑问句）— 🏆 零瑕疵
- 中文：这需求已经进了开发流程，对吧？
- 学生：`This requirement has gone into the development stream, hasn't it?`
- 评价：✅ `has gone` 现在完成时正确（强调"已进且就在里面"）。Tag `hasn't it?` 极性/时态/代词全对。🏆 零瑕疵。

#### Round 5（选择疑问句）
- 中文：这需求是先进开发流程，还是先给架构评审？
- 学生：`Should this requirement go into the development stream first, or should it have an architectural review?`
- 评价：✅ `go into the development stream` 精准。✅ 平行结构 `Should...or should...` 对称。⚠️ `have an architectural review` → `go through an architecture review` 更自然。

**句式 6（虚拟语气）**：⏭️ 跳过。流程名词难以自然放入 Type 3 假设。

#### Quick Fire — 🏆 跨 LP 自发融合
- 场景：PM 催紧急需求，你拦住说不该太快。
- 学生：`Well, we should not move this requirement too fast because we should have to align with the business first before going into the development stream.`
- 评价：✅ `go into the development stream` 自然使用。🏆 `align with the business`（LP 4）无提示自发融入。⚠️ `should have to` 冗余（两词均表义务，择一即可）。

**LP 状态**：🟡 复用中。5/6 全覆盖。连续 5 句式零失误。`come across as` 在第 2 轮完成结构突破 🏆🏆🏆。`development stream` 搭配稳定。

**历史词组植入**：`come across as` 🏆🏆🏆（结构突破）/ `align with the business` 跨 LP 复用 🏆

---

### LP 9: 进行时表常态化工作流程 — 24BEC 新学 🆕

**来源**：24BEC 学生问首句为什么用 `You're talking to the business`（为什么是进行时）
**核心**：现在进行时不仅表"此刻正在做"，职场口语中还用来描述**常态化/反复发生的工作流程**，比一般现在时更鲜活有场景感。
**训练句式**：6/6（全部覆盖 + QF）

#### Round 1（肯定陈述句）— 🏆 `on a cadence` 3 月+ 未碰，首次即用
- 中文：我们现在按每两周的节奏发版。
- 学生：`We are releasing versions on a two-week cadence.`
- 评价：✅ 进行时表常态化正确。🏆 `on a two-week cadence` 超 3 月未碰，首次尝试即精准。零瑕疵 🏆。

#### Round 2（否定陈述句）— 🏆 `cadence` 双杀
- 中文：我们现在没有按季度评审需求——改成每月了。
- 学生：`We're not reviewing requirements on a quarterly cadence. we have switched to a monthly cadence.`
- 评价：✅ 进行时表常态化正确。🏆 `on a quarterly cadence` + `a monthly cadence` 双 `cadence` 用上。`switched to` 自主使用，地道度加分。

#### Round 3（特殊疑问句）— ⚠️ 语序偏书面
- 中文：你们现在按什么节奏对接业务方？
- 学生：`on what cadence are you aligning with the business?`
- 评价：✅ 进行时表常态化 + `cadence` + `align with the business` 🏆 跨 LP 三杀。⚠️ `On what cadence` 偏书面 → 口语中 `How often` 更自然。

#### Round 4（反义疑问句）— 🏆 零瑕疵
- 中文：你们现在每天站会，对吧？
- 学生：`You're doing the stand-up on a daily cadence, aren't you?`
- 评价：✅ 进行时表常态化 + `on a daily cadence` 连续 4 句式成功。Tag `aren't you?` 三要素全对。零瑕疵 🏆。

#### Round 5（选择疑问句）— 🔴 `have catch up` 冠词遗漏
- 中文：你们是每天复盘，还是有问题才临时碰一下？
- 学生：`Are you reviewing on a daily cadence, or do you just have catch up when having issues?`
- 评价：✅ 进行时表常态化正确。🔴 `have catch up` → `have **a** catch-up`（名词需冠词）或 `just catch up`（动词）。⚠️ `when having issues` → `when something comes up` 更自然。

#### Round 6（虚拟语气 Type 3）— 🔴 目标结构未使用 + 🔴 `there would not have had` → 加练
- 中文：如果我们当初是按每周的节奏对接，这些需求偏差早就被发现了。
- 学生：`If we had worked on a weekly cadence at that time, the bias on the requirements would have been found already.`
- 评价：✅ `on a weekly cadence` 正确。🔴 **目标结构未使用**：`had worked`（一般完成）→ 应为 `had been aligning`（进行时）。⚠️ `bias` = 偏见 → `requirement gaps` / `misalignment`。⚠️ `at that time` 冗余。**本轮加练**。

- **加练轮**：如果我们当初一直在按每周的节奏对齐，就不会出现这些需求偏差了。
- 学生：`If we had been aligning on a weekly cadence, there would not have had requirement gaps.`
- 评价：✅ `had been aligning` 🏆 进行时成功融入 Type 3。🔴 `there would not have had` → `there would not have **been**`（`there be` 完成体虚拟）。⚠️ `gaps` ✅（修正了 `bias`）。

**句式 6 小结**：加练 1 轮后进行时结构正确，但 `there be` + `have` 混淆新缺口暴露。

#### Quick Fire — 🔴 目标结构回避
- 场景：新同事问你们如何同步进度。
- 学生：`Well, we do standups on a daily cadence to sync up our progress with each other.`
- 评价：✅ `on a daily cadence` + `sync up` ✅。🔴 `do standups`（一般现在时）→ 该用 `are doing standups`（进行时表常态化）。场景是"问他平时怎么做"需要进行时的画面感。

**LP 状态**：🟡 复用中。6 句式全覆盖。在 4/6 句式（肯定/否定/特殊/反义）中连续正确，选择疑问句和虚拟语气出现错误。`cadence` 在 6 句式全覆盖中无缝复用。Quick Fire 中目标结构回避。

**历史词组植入**：`on a cadence` 🟢（连续 6 句式均自发使用）🏆

---

## 3. 📊 不足汇总 (Improvement Areas)

### 3.1 语法层痛点

| # | 缺口 | 严重度 | 首次出现 | 今日复发 | 详情 | 位置 |
|:---:|:---|:---:|:---|:---:|:---|:---|
| 1 | 🔴 **Tag 代词匹配** | 🔴 | 2026-05-05 | **再次复发** | `your team...haven't you?` ❌ → `haven't they?` ✅。主句主语第三人称（team），Tag 用了第二人称（you）。加练后修复 | FC R1 |
| 2 | 🔴 **`many/much` 复发** | 🔴 | 2026-06-06 | **再次复发** | `so much issues` ❌ → `so many issues` ✅。Flash Correct 中正确，但在 LP 3 虚拟语气复杂句压力下回退 | LP 3 R6 |
| 3 | 🔴 **`come across as` 结构（连续 3 次错误 → 第 4 次修复）** | 🔴 | 2026-06-20 | **今日新暴露** | R1 `as like you seems` ❌ → R2 `as that you don't do` ❌ → R4 `as unlike this process` ❌ → **R7 `as unreliable` ✅**（LP 8 R2 突破） | LP 4 R1/R2/R4, LP 8 R2 |
| 4 | 🔴 **`there would not have had`** | 🔴 | 2026-06-20 | **今日新暴露** | `there would not have had requirement gaps` ❌。`there be` 完成体虚拟是 `there would have been`，不是 `there would have had` | LP 9 R6 加练 |
| 5 | 🔴 **间接疑问句语序** | 🔴 | 2026-06-16 | **再次复发** | `Which one is more important you think` ❌ → `Which one do you think is more important` ✅ | LP 4 R5 |
| 6 | 🟡 **`Does...happens` 主谓不一致** | 🟡 | 2026-06-20 | 新暴露 | `Does this problem happens` ❌ → `does` 后必须跟动词原形 `happen` | LP 7 R5 |
| 7 | 🟡 **`have catch up` 冠词遗漏** | 🟡 | 2026-06-20 | 新暴露 | `have catch up` ❌ → `have **a** catch-up` ✅ | LP 9 R5 |
| 8 | 🟡 **`can be moving` 情态+进行时叠加** | 🟡 | 2026-06-20 | 新暴露 | `can the design review be moving` ❌ → `does the design review go` ✅ | LP 7 R3 |
| 9 | 🟡 **`should have to` 冗余** | 🟡 | 2026-06-20 | 新暴露 | `we should have to align` — `should` 和 `have to` 均表义务，叠用冗余 | LP 8 QF |

### 3.2 词汇/搭配层痛点

| # | 缺口 | 严重度 | 详情 | 位置 |
|:---:|:---|:---:|:---|:---|
| 10 | 🟡 **`high points` → `key points`** | 🟡 | `high points` = 亮点/高光时刻，`key points` = 重点/要点 | LP 1 R5 |
| 11 | 🟡 **`anticipation` → `expectations`** | 🟡 | `anticipation` = 期待/预料（情感浓），`expectations` = 预期（职场标准） | LP 4 R3 |
| 12 | 🟡 **`unlike` ≠ "不喜欢"** | 🟡 | `unlike` 是介词（不同于），不能当"不喜欢"用 | LP 4 R4 |
| 13 | 🟡 **`bias` → `misalignment` / `gap`** | 🟡 | `bias` = 偏见/偏心，需求偏差 = `gaps` / `misalignment` / `discrepancies` | LP 9 R6 |
| 14 | 🟡 **`maintainer` → `ops`** | 🟡 | `maintainer` = 开源项目维护者，运维 = `ops guy` / `ops team` | FC R2 (组3) |
| 15 | 🟡 **`Who's the boss?` → `Who decides?`** | 🟡 | `Who's the boss?` = 问组织架构，`Who decides?` = 问决策权 | LP 8 R3 |
| 16 | 🟡 **`found out` → `found` / `flagged`** | 🟡 | `find out` = 查明某个事实，不用于"发现代码问题" | Micro RP 2 |
| 17 | 🟡 **`haven't been tested` → `missed`** | 🟡 | "测试漏了 bug" 是 `missed`（没测出来），不是 `haven't been tested`（没测过） | LP 7 R4 |
| 18 | 🟡 **`come up with reviews` 搭配不当** | 🟡 | `come up with` 搭配 ideas/solutions/suggestions，不接 reviews | LP 7 QF |
| 19 | 🟡 **`don't want to` → `don't plan to`** | 🟡 | "不打算"偏"计划/意图"非"意愿" | FC R2 (组1) |
| 20 | 🟡 **`bugs with the feature` → `bugs in this feature`** | 🟡 | `with` 不如 `in` 自然 | FC R1b (组2) |
| 21 | 🟡 **`formal launch` → `official launch`** | 🟡 | `formal` = 庄重的/正式的，`official` = 官方的发布 | LP 3 R4 |
| 22 | 🟡 **`completely keep silent` 生硬** | 🟡 | → `just stay quiet` / `simply remain silent` | LP 1 R2 |
| 23 | 🟡 **逗号连接独立句** | 🟡 | `as a result` / `, we don't have...` 需分号/句号/连词 | FC R2 (组2) |

### 3.3 学生亮点 🏆

1. **主动质疑 ×5** 🏆：
   - LP 1 R3 质疑中文句不适合使用 `if you wish`（正确！）
   - LP 1 R5 质疑选择疑问句 3 次"别扭"（连续指出出题失败）
   - LP 7 R2 质疑中文句语义不匹配 `the same thing happens with`（正确！）
   - LP 7 R4 质疑中文句用不上 LP（正确！）
   - 指出中文句子字数超出 GEMINI.md 规定的 20 字限制（正确！）
2. **`come across as unreliable` — 第 5 次尝试结构突破** 🏆🏆🏆：从 `as like` → `as that` → `as unlike` → 最终 `as adj`，在 LP 8 R2 独立修复完成。
3. **跨 LP 复用 ×3** 🏆：`align with the business` 在 LP 8 QF 自发使用；`on a cadence` 在 6 个句式全覆盖中持续自发使用；`align with the business` 在 LP 9 R3 中与 `cadence` 同时出现。
4. **`cadence` 3 月+ 未碰，首次尝试即精准** 🏆
5. **Type 3 虚拟语气 LP 4 R6 满分** 🏆（`had aligned with...on...` 完美融入）
6. **`development stream` 连续 5 句式零失误** 🏆
7. **主动追问语法细节 ×3**：`go over vs go through`、`ground` 隐喻义、`testing` 作主语、`align with sb on sth`

### 3.4 本轮 AI 执行问题

| # | 问题 | 严重度 | 详情 |
|:---:|:---|:---:|:---|
| 1 | **历史词组植入失职（连续 5 次）** | 🔴 | 连续 5 轮声明植入 `come across as`（用"给人感觉"），但中文句中无对应措辞。LP 1 R2/R3、LP 3 R1/R4/R5、LP 7 R1/R2 合计 7 轮植入失职 |
| 2 | **`if you wish` 选择疑问句出题 ×3 失败** | 🟡 | `if you wish` 和选择疑问句的兼容性差，AI 连续 3 次出题被学生指出"别扭"。根本原因：`if you wish` = 给予单方面选择权，选择疑问句 = 两个选项平级提问，语义不兼容 |
| 3 | **汉字数超限** | 🟡 | LP 5 中文句子超过 GEMINI.md 规定的 20 字，被学生当场指出 |
| 4 | **`the same thing happens with` 否定句/反义疑问句初版出题不兼容** | 🟡 | 两次出题（"显得不怎么配合"/"A 和 B 一样"）语义不匹配 LP 结构，被学生指出后重出 |
| 5 | **提取非学生疑问的 LP (`while + doing`)** | 🟡 | 被学生当场质疑"这是学生提问中涉及到的吗？"，AI 承认不属实，停止训练 |

---

## 4. 🛠️ 会话末检查清单

### 4.1 本次新学语言点初始状态

| 语言点 | 状态 | 判定依据 |
|:---|:---:|:---|
| `if you wish`（补 23BEC） | 🟡 | 补齐至 5/6+QF；核心结构正确；选择疑问句兼容性差（AI 出题责任）|
| `have + 时间 + to do` | 🟡 | 6/6+QF；目标结构不稳（R3 `need` 回避 + R3b `have to` 歧义）；`many/much` 复发 1 次；关键性错误 1 次→加练 |
| `work with / align with the business` | 🟡 | 6/6+QF；Type 3 满分；连续 3 次 `come across as` 结构错误（最终 LP 8 中修复）；间接疑问句语序复发 1 次 |
| `the same thing happens with` | 🟡 | 5/6+QF；关键性错误 1 次（`Does...happens` 主谓不一致）；AI 出题 2 次被驳回 |
| `development stream` | 🟡 | 5/6+QF；连续 5 句式零失误；`come across as` 🏆 结构突破；跨 LP 自发复用 |
| 进行时表常态化工作流程 | 🟡 | 6/6+QF；`cadence` 6 句式全覆盖正确；关键性错误 2 次（R5 冠词+R6 目标结构回避）；`there be`+`have` 混淆新缺口 |

### 4.2 `come across as` 结构修复追踪 ⭐

本 session 最重要的突破：

| 轮次 | 位置 | 尝试 | 结果 |
|:---:|:---|:---|:---:|
| 1 | LP 4 R1 | `came across as like you seems` | ❌ 时态+双层介词+主谓一致 |
| 2 | LP 4 R2 | `come across as that you don't do` | ❌ `as that` 从句违规 |
| 3 | LP 4 R4 | `come across as unlike this process` | ❌ `unlike` 是介词 |
| 4 | LP 4 R5（速查表） | — | 📖 导师出结构速查表 |
| **5** | **LP 8 R2** | **`come across as unreliable`** | **✅🏆 突破！`as + adj`** |

从 `as like` → `as that` → `as unlike` → **`as adj`**。这是本 session 最有价值的单人突破。

### 4.3 24BEC 未练语言点

| # | 语言点 | 状态 |
|:---:|:---|:---:|
| LP 5 | `for + noun`（表目的） | ⏭️ 跳过（学生嫌中文太长） |
| LP 6 | `every + 数字 + 时间单位` | ⏭️ 跳过 |
| — | 现在进行时 vs 一般现在时（深度辨析） | ✅ 已自然融入 LP 9 训练中 |

---

*本笔记由 AI 在 2026-06-20 会话结束后生成。*
