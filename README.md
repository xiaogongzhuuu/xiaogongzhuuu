# Siyuan Cao

上海大学人工智能本科生，关注多智能体协作、RAG、Agent 工程与知识图谱。

<a href="https://www.xiaohongshu.com/user/profile/6301d55f0000000012001c6a"><img src="https://cdn.simpleicons.org/xiaohongshu/FF2442" alt="小红书" width="18" height="18"> 小红书</a>

## 项目

### [MDT 医疗多智能体平台](https://github.com/xiaogongzhuuu/mdtagentplatform)

**LangGraph · LangChain · pgvector · PostgreSQL**

参与医学文献检索与知识图谱开发，为多智能体协作和病例评测提供证据检索能力。

- 实现医学 PDF 分块、Embedding、pgvector 索引与语义检索
- 融合向量检索、全文检索与 RRF 排序，将检索封装为 Host Agent 工具并支持降级
- 参与文献知识图谱与证据浏览功能开发

### [智能选校 Agent](https://github.com/xiaogongzhuuu/tucebida-study-abroad)

**DeepSeek · BGE-M3 · ChromaDB · FastAPI**

面向留学顾问的 RAG 选校原型，结合院校项目资料和历史案例生成选校建议。

- 整理 116 个研究生项目，覆盖英港新 33 所院校
- 结合向量检索、元数据过滤与规则评分召回候选项目
- 实现学生画像提取、冲刺 / 匹配 / 保底分级和 SSE 流式报告

### [Agent Trace Lab](https://github.com/xiaogongzhuuu/agent-trace-lab)

**DeepSeek · Tool Calling · ReAct · Next.js · TypeScript**

用于学习 Tool Calling 和 ReAct 循环的交互实验台，展示模型请求、工具调用、执行结果与下一轮上下文。

- 支持自动运行与分步确认，逐轮查看请求和响应
- 调整工具描述与顺序，比较相同问题下的工具选择
- 使用 DeepSeek 生成工具调用，结合演示数据呈现完整执行循环
