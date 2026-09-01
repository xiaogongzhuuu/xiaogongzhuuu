# Siyuan Cao

**AI 应用开发 · LLM Agent · RAG**

上海大学人工智能专业本科生。主要使用 Python 和 FastAPI 构建大模型应用，关注 Agent、知识检索与 AI 产品工程。

我也在记录技术浪潮如何进入真实世界，以及身处其中的人如何理解自己的位置。

## Projects

### [AI 智能选校测评](https://github.com/xiaogongzhuuu/study-abroad-evaluation)

**DeepSeek · FastAPI · SQLite · Docker**

面向留学咨询业务的轻量 AI 应用，将背景测评、报告解锁、线索沉淀和顾问跟进连接成完整流程。

- 对模型生成的档位、数量、空值和重复院校进行结构化校验
- 通过服务端报告 ID 关联测评结果与联系方式
- 支持顾问后台、CSV 导出、企业微信和邮件通知
- 提供自动化测试、接口限流、数据库备份与 HTTPS 部署模板

### [MDT 医疗多智能体平台](https://github.com/xiaogongzhuuu/mdtagentplatform)

**LangGraph · LangChain · pgvector · PostgreSQL**

参与医学文献知识检索与知识图谱功能开发，将 RAG 能力接入多智能体协作和病例评测流程。

- 实现医学 PDF 分块、Embedding、pgvector 索引与语义检索
- 将文献检索封装为可由 Host Agent 调用的工具
- 结合向量检索、全文检索与 RRF 融合，并支持检索降级
- 参与文献知识图谱、证据浏览和平台功能迭代

### [智能选校 Agent](https://github.com/xiaogongzhuuu/tucebida-study-abroad)

**DeepSeek · BGE-M3 · ChromaDB · FastAPI**

面向留学顾问的 RAG 选校原型，探索如何把院校项目资料和历史案例转化为推荐依据。

- 整理并统一 116 个研究生项目，覆盖英港新 33 所院校
- 结合向量检索、元数据过滤与规则评分召回候选项目
- 实现学生画像提取、冲刺 / 匹配 / 保底分级和 SSE 流式报告

### [医学知识图谱与 RAG 问答](https://github.com/xiaogongzhuuu/data-mining-course)

**Neo4j · ChromaDB · PyTorch · LLM**

从文本分类、实体关系抽取和知识图谱构建，到中医文档检索问答的一组实践。

## Tech Stack

**AI Application**

LLM · RAG · Agent · LangGraph · ReAct · Tool Calling · Evaluation

**Backend & Retrieval**

Python · FastAPI · PostgreSQL · SQLite · pgvector · ChromaDB · FAISS

**Product & Delivery**

SSE · JavaScript · Docker · Git

## Elsewhere

[博客：一只老红薯](https://xiaogongzhuuu.github.io/) · [小红书：一只老红薯](https://www.xiaohongshu.com/user/profile/6301d55f0000000012001c6a)

写技术，也记录 AI 浪潮之下尚未想明白的问题。
