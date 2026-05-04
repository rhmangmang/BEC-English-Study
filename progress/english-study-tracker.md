# BEC English Study Progress Tracker

本文件是进度追踪的**总索引**，各区块内容已拆分到独立文件。每次会话开始时先读此索引定位所需信息，然后打开对应的子文件。

---

## 文件结构与职责

| 区块 | 文件 | 内容 | 查询时机 | 维护时机 |
| :--- | :--- | :--- | :--- | :--- |
| 🔄 **复用候选词组库** | [`active-pool.md`](./active-pool.md) | 近 14 天活跃词组，含 SRS 状态 🟢/🟡/🔴 | 出题前扫描历史词组、检查复用候选 | 每次会话结束时 AI 自动维护（升降级、归档） |
| 📚 **核心语言点掌握情况** | [`mastered-points.md`](./mastered-points.md) | 所有已掌握语言点的完整归档（练习次数、掌握程度） | 查询某个语言点的历史表现、归档验证 | 新语言点学完后或状态变更时追加 |
| 📅 **学习记录概览** | [`session-overview.md`](./session-overview.md) | 每次会话的日期、主要内容和状态 | 回顾学习历程、确认哪些 BEC 单元已完成 | 每次会话结束时追加新行 |
| 🎯 **待解决的知识缺口** | [`knowledge-gaps.md`](./knowledge-gaps.md) | 所有已知知识缺口，分 🔴 Active / 🟡 Monitoring / ✅ Archived 三级 | Flash Correct 选题、话题构建训练的薄弱项推荐 | 发现新缺口 / 缺口修复后变更状态 |
| 📋 **下一步计划** | [`next-steps.md`](./next-steps.md) | 短期行动项，聚焦待推进的 BEC 单元和高优缺口 | 每次会话开始前查看当前优先级 | 完成行动项后标记 `[x]`，新增行动项时追加 |

---

## 关键维护规则

1. **复用候选库上限 80 个**，超出优先归档最早的 🟢 词组到 `mastered-points.md`
2. **知识缺口 Active 区控制在 20 条以内**，超出移入 Monitoring
3. **每次会话结束**时 AI 依次维护：`active-pool.md` → `session-overview.md` → `knowledge-gaps.md` → `next-steps.md`
4. **每次首次会话**：从 `knowledge-gaps.md` 的 Archived 区随机抽查 2-3 条
5. **`mastered-points.md` 只追加不删除**，是完整的历史归档
