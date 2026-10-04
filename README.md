<h1 align="center">Hi, I'm 林锦浩</h1>

<p align="center">
  软件工程本科在读 · AI 应用开发方向 · 正在寻找 AI 应用开发 / AI Agent 开发实习机会
</p>

<p align="center">
  <a href="https://github.com/vitacool/campus-ai-agent">校园智能问答 Agent</a>
  ·
  <a href="https://github.com/vitacool/campus-notice-classifier">校园通知文本分类系统</a>
  ·
  <a href="https://github.com/vitacool/resume-jd-matcher">智能简历匹配系统</a>
  ·
  <a href="https://github.com/vitacool/doc-rag-qa-system">AI 知识库问答系统</a>
</p>

---

### 关于我

- 软件工程本科，关注 **AI 应用开发、RAG、Agent 工具路由、后端 API 与数据闭环**
- 能够使用 **Python / FastAPI / PyTorch / SQLite / HTML / CSS / JavaScript** 完成小型 AI 应用从后端到页面的闭环实现
- 正在补强方向：向量检索、模型评估、工程化部署、AI 产品中的反馈与纠错机制

### 技术栈

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=222)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

### 重点项目

#### [校园智能问答 Agent](https://github.com/vitacool/campus-ai-agent)

面向校园通知、部门电话、宿舍报修、教务流程等高频问题的智能问答系统。

- 使用 **FastAPI** 构建后端接口和 Agent 核心逻辑
- 支持 **RAG 知识库检索、向量检索、关键词 fallback、后台知识库管理**
- 使用 **SQLite** 记录问答日志与用户反馈，具备基础可维护性
- 可接入通知分类服务，实现“先识别意图，再路由 Agent 工具”

#### [校园通知文本分类与 Agent 路由系统](https://github.com/vitacool/campus-notice-classifier)

基于 PyTorch 的校园通知文本分类系统，可作为 Agent 的前置意图识别模块。

- 自建校园通知数据集，覆盖 **教务、讲座、竞赛、后勤、社团活动** 5 类场景
- 使用 **PyTorch** 训练字符级文本分类模型，输出分类结果与置信度
- 提供 **FastAPI 分类接口、Agent 路由接口、SQLite 预测记录、用户纠错、后台管理页面**
- 增加模型评估页，展示准确率、Precision、Recall、F1、混淆矩阵等指标

#### [智能简历匹配与岗位分析系统](https://github.com/vitacool/resume-jd-matcher)

面向学生求职场景的 AI 应用，输入简历文本和岗位 JD，自动输出匹配度、缺失关键词和修改建议。

- 使用 **FastAPI** 提供简历分析、历史记录和关键词接口
- 基于关键词抽取、文本向量化和余弦相似度计算岗位匹配分
- 使用 **SQLite** 保存历史分析记录，支持查看和删除
- 前端页面支持示例填充、匹配结果展示、缺失能力提醒和简历修改建议

#### [AI 知识库文档问答系统](https://github.com/vitacool/doc-rag-qa-system)

面向企业内部知识库和校园文档的 RAG 问答系统，支持文档入库、向量检索、引用来源和反馈闭环。

- 支持 TXT、Markdown、CSV、JSON、PDF 文档上传和手动新增知识
- 实现文档解析、chunk 切分、Hashing Vector、余弦相似度检索和引用来源展示
- 使用 **FastAPI + SQLite** 管理文档、文本块、问答日志和用户反馈
- 提供知识库后台、问答页面和日志反馈页面，预留 FAISS/Chroma/Embedding 升级方向

### 我正在学习和实践

- RAG 与向量数据库在真实应用中的落地方式
- AI Agent 的工具调用、意图识别与任务路由
- 从 Demo 到可维护系统的后台管理、日志记录、反馈闭环
- 机器学习模型训练、评估和 Web 服务化

---

<p align="center">
  <sub>希望把 AI 能力做成真正可用、可维护、能解决实际问题的小系统。</sub>
</p>
