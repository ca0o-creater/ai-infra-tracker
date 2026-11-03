# AI Infra Learning Tracker

## 项目定位

本项目用于追踪22个月AI Infra算法侧学习计划。

主攻：
LLM推理引擎算法决策。

不用于重新讨论职业方向或重新制定长期路线。

## 项目目标

1. 保存当前学习计划。
2. 记录每周学习产出。
3. 自动审计代码与实验。
4. 分派下周任务。
5. 累积历史学习档案。

## 核心文件

plan/roadmap.md
长期学习计划。

plan/phase.md
当前Phase任务与验收标准。

logs/weekly-log.md
每周实际学习情况。

archive/review-history.md
历史审计结果。

archive/next-week.md
当前下周任务。

AGENTS.md
审计规则。

automation/weekly-audit.md
固定自动审计指令。

## 每周使用流程

### 周一至周六

执行archive/next-week.md中的任务。

完成实验后提交代码和原始日志。

### 周日20:00前

更新logs/weekly-log.md。

填写本周完成事项与证据链接。

### 周日20:00

Codex Automation执行审计。

核查：
- Git提交
- 测试结果
- Benchmark
- 阶段产出
- 阻塞情况

### 审计结束

如果允许写入：

追加review-history.md。
覆盖next-week.md。

如果只读：

输出完整周报与任务。
用户手动保存。

## 降级规则

没有可验证产物：
触发红色标记。

同一核心产出连续两周未出现：
触发阻塞。

触发降级后：
下周只允许一个最小可验证目标。

## Phase切换

1. 完成当前Phase全部门禁。
2. 获得通过或有条件通过结论。
3. 更新phase-history.md。
4. 更新phase.md。
5. 保留历史证据。

不得由AI擅自修改长期方向。

## 数据保存

建议使用Git版本管理。

每周审计后提交一次档案更新。

## 资源限制

GPU预算：
每月100—300元。

考试周：
允许暂停项目。

自动审计不得擅自购买GPU资源或启动付费实例。