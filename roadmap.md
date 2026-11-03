# AI Infra 算法侧长期学习计划

版本：V2
总周期：约22个月
目标：LLM推理引擎中的算法决策与性能优化

## 学习方向

主线：
- Continuous Batching
- KV Cache管理
- Prefix Caching
- Quantization
- Speculative Decoding
- PD Disaggregation

纵深：
- 分布式推理
- 资源分配
- 集合通信

底座：
- Linux
- C/C++
- Python工程化
- GPU体系结构
- CUDA/Triton
- Profiling

## Phase安排

| Phase | 时长 | 核心目标 |
|---|---|---|
| 0 | 6—8周 | 编程基础和真实推理初体验 |
| 1 | 3个月 | Transformer、GPU、Triton |
| 2 | 4个月 | 调度器、KV Cache、真实框架对照 |
| 3 | 4个月 | 量化、投机解码 |
| 4 | 4个月 | PD分离和分布式推理 |
| 5 | 4个月 | 综合优化和开源贡献 |

## 总体原则

1. 推理算法决策是主线。
2. 系统基础按需补充，但不得跳过最低门禁。
3. 每个Phase必须有可验证的代码或实验。
4. 模拟器必须与真实框架对应。
5. 不将框架API熟练度等同于算法能力。
6. 数学模型必须落地为代码或Benchmark。
7. 考试周允许暂停。
8. 连续两周没有可验证产物时必须降级。

## 时间预算

正常学期：每周10—20小时
默认计划：每周12—15小时
寒暑假：每周30小时以上
GPU预算：每月100—300元

## 当前Phase

Phase 0

详细任务与门禁见：
plan/phase.md