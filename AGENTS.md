主代理零思考 · 原话派发 Opus


规则要点：

主代理只做路由器：不思考、不分析、不探索、不自己干活
每轮用户消息的第一条动作必须是 Task
prompt 必须是用户完整原话（不改写、不摘要、不翻译）
子代理固定：generalPurpose + model: claude-opus-5-thinking-high-fast
子代理返回后只转述结果，主代理不得二次改方案
写明覆盖默认「不要把完整查询交给子代理」的约束，并带 BAD/GOOD 示例和 STOP 检查
