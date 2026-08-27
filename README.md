# Siyuan Cao

**AI 应用工程师 · 独立开发者 | LLM Agents · RAG · AI 产品工程**

上海大学人工智能专业本科生。专注 LLM 应用开发，把 AI 能力变成真实场景里可用的工具；同时持续记录 AI 行业的落地观察与产品思考。

博客：[一只老红薯](https://xiaogongzhuuu.github.io/) · 小红书：[一只老红薯](https://www.xiaohongshu.com/user/profile/6301d55f0000000012001c6a)

---

## 项目

### [智能选校 Agent](https://github.com/xiaogongzhuuu/tucebida-study-abroad) — DeepSeek · RAG · FastAPI · SSE

面向留学顾问业务的 AI 选校推荐系统。

学生画像解析 → 混合检索（向量搜索 + 元数据过滤）→ 多阶段打分排序 → SSE 流式生成推荐报告。

- 116 个项目结构化入库，覆盖英港新 33 所院校
- 冲刺 / 匹配 / 保底三档分级
- 流式生成推荐报告

### [AI 智能选校测评](https://github.com/xiaogongzhuuu/study-abroad-evaluation) — DeepSeek · FastAPI · SQLite · JavaScript

面向留学业务的轻量测评与线索转化应用。学生约 30 秒填写申请背景，即可获得冲刺、匹配、保底三档共 6 所院校建议。

- 服务端保存报告并关联留资，形成测评 → 解锁 → 跟进闭环
- 企业微信群与邮件异步通知顾问
- 口令保护的线索管理后台，支持统计与 CSV 导出

### [医学知识图谱 + RAG 混合问答](https://github.com/xiaogongzhuuu/data-mining-course) — Neo4j · ChromaDB · LLM

面向中医名医经验传承场景。大模型实体抽取构建 Neo4j 知识图谱，结合 ChromaDB 向量检索，实现结构化推理与非结构化检索的混合问答。

### [RAG 文档问答助手](https://github.com/xiaogongzhuuu/rag-assistant) — GPT-4 · LangChain · FAISS · [Demo](https://huggingface.co/spaces/xiaogongzhuuu/rag)

面向企业私有知识库场景，构建文档解析 → 向量检索 → 上下文增强生成的完整 RAG 链路，支持 PDF / Markdown 上传与多轮对话。

## 其他实践

- [LLM 应用开发](https://github.com/xiaogongzhuuu/rag-agent-project)：API 调用 → Prompt Engineering → RAG → Agent ReAct 自主推理
- [ChatGLM LoRA 指令微调](https://github.com/xiaogongzhuuu/chatglm-lora-demo)：指令微调 + Streamlit 对话界面

---

## 技术栈

Python · JavaScript · DeepSeek · Qwen · GPT-4 · LangChain · FastAPI · FAISS · ChromaDB · Neo4j · Docker · Hugging Face Spaces

---

## 关注方向

LLM Agent · RAG · AI 产品工程化落地
