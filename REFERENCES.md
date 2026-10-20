# 参考资料

以下链接用于后续实现、案例制作与行为核对。本仓库当前只提供初始化骨架和设计文档，未复制下列项目的实现代码，也没有据此声称完成相应功能。

开始实现时记录实际查阅日期、依赖版本、相关文档快照或内容哈希。官方文档可能更新；不能仅凭当前网页内容推定旧版工具具有相同行为。

## uv

| 来源 | 计划用途 |
| --- | --- |
| [Reproducible examples](https://docs.astral.sh/uv/reference/troubleshooting/reproducible-examples/) | 组织最小复现材料与环境信息 |
| [Build failures](https://docs.astral.sh/uv/reference/troubleshooting/build-failures/) | 参考构建错误排查思路；仅选入首版范围内可复现的问题 |
| [Locking and syncing](https://docs.astral.sh/uv/concepts/projects/sync/) | 区分依赖声明、锁定与环境同步，设计客观验证 |

这些文档是知识来源，不是现成的 EnvDesk 评测集。项目案例、参考原因和修复条件需要自行构造与人工核验。

## LangGraph

| 来源 | 计划用途 |
| --- | --- |
| [Workflows and agents](https://docs.langchain.com/oss/python/langgraph/workflows-agents) | 区分程序固定流程与模型动态工具选择 |
| [Persistence](https://docs.langchain.com/oss/python/langgraph/persistence) | 设计任务标识、检查点与跨进程继续 |
| [Interrupts](https://docs.langchain.com/oss/python/langgraph/interrupts) | 核对中断恢复及节点重入语义，设计人工确认边界 |

业务执行记录、重复请求处理与检查点分别验收，不把框架持久化能力直接表述为所有业务操作“恰好一次”。

## 参考使用与归属

- 引用知识时保留来源 URL、标题、片段位置、适用版本与采集记录。
- 不将参考答案混入 Agent 可检索的资料集合。
- 若后续引入第三方代码，记录来源、保留要求的署名与许可，并明确自行实现的部分。
- 当前未选择项目许可证；此文件不是第三方材料的重新授权。
