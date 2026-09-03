# Codex Personal Skills

这个私有仓库保存两个可复用的 Codex 技能：

- `debug-mode`：基于运行时证据定位复杂缺陷，完成最小修复、验证和临时插桩清理。
- `vibe-grilling`：通过需求拷问、变更提案、确认关卡、实现验证和台账回写管理开发任务。

两个技能支持联动：当由 `vibe-grilling` 管理的任务使用 `debug-mode` 时，调试证据、根因、修复和验证结果会回写到对应提案、项目台账与会话摘要。

## 目录

```text
debug-mode/
vibe-grilling/
```

每个技能目录可单独放入 Codex 的个人技能目录中使用。
