## 你好 👋 / Hi there 👋

<!--
**johnnyjly/johnnyjly** 是一个 ✨ _特殊的_ ✨ 仓库，因为它的 `README.md`（本文件）会显示在你的 GitHub 个人主页上。
**johnnyjly/johnnyjly** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

以下是一些帮助你开始完善主页的建议：
Here are some ideas to get you started:

- 🔭 我目前正在开发……
  I’m currently working on ...
- 🌱 我目前正在学习……
  I’m currently learning ...
- 👯 我希望参与合作……
  I’m looking to collaborate on ...
- 🤔 我正在寻求有关……的帮助。
  I’m looking for help with ...
- 💬 可以向我询问……
  Ask me about ...
- 📫 联系我的方式：……
  How to reach me: ...
- 😄 人称代词：……
  Pronouns: ...
- ⚡ 关于我的趣事：……
  Fun fact: ...
-->

我叫 **Johnny Jiang**，目前就读于香港中文大学人工智能硕士，本科是加拿大多伦多大学。

My name is **Johnny Jiang**. I'm currently a graduate student of Chinese University of Hong Kong (MSc in AI) and I had my undergrad study in University of Toronto in Canada (CS).

<picture>
<!--   <img align="right" width="50%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=johnnyjly&layout=compact&hide_title=1&card_width=300" alt="我的仓库中使用最多的编程语言 / Top language used in my repos" /> -->
<!--   <img align="right" width="40%" src="https://github-readme-stats.vercel.app/api?username=johnnyjly&show_icons=true&hide=stars,issues" /> -->
</picture>

* 🧐 对全栈开发感兴趣，近期专注于 **Agent** 开发。<br>
  Interested in full stack development. Recently focus on **Agent** Stack.
* :pencil2: 技术栈：Python、Java、JavaScript、SQL、FastAPI、Node.js、Spring Boot、REST、GraphQL。<br>
  Tech stack: Python、Java、JavaScript、SQL、FastAPI、Node.js、Spring Boot、REST、GraphQL.
* 🎓 计算机科学荣誉理学学士，平均绩点 3.95/4.00。<br>
  Honours Bachelor of Science in Computer Science GPA 3.95/4.00.
* :thought_balloon: 欢迎在[讨论区](https://github.com/johnnyjly/johnnyjly/discussions/new/choose)向我提问！<br>
  Ask me anything at [Discussions](https://github.com/johnnyjly/johnnyjly/discussions/new/choose)!

<hr>

**欢迎了解我的项目！**<br>
**Check out my projects!**

<details>
  <summary>🧠 <a href="https://github.com/johnnyjly/TraceMind">TraceMind</a> — 微服务故障诊断 / Microservice Incident Diagnosis — Python / FastAPI / LangGraph / MCP / OpenTelemetry</summary>
  <br>

* 基于指标、链路追踪和日志调查微服务故障，生成包含证据引用、假设和明确缺口的结构化诊断，并通过独立的只读 HTTP MCP 服务访问遥测数据。<br>
  Investigates microservice incidents using metrics, traces, and logs accessed through an independent read-only HTTP MCP service, then produces structured diagnoses with evidence references, hypotheses, and explicit gaps.
* 默认采用受预算约束的 LangGraph 单智能体，统一控制工具权限、模型与工具调用预算、上下文限制、有界重试和可选备用模型。<br>
  Defaults to a bounded LangGraph single agent with shared controls for tool permissions, model and tool call budgets, context limits, bounded retries, and optional fallback models.
* 提供可选的多智能体工作流，由协调者委派最多两个并发调查任务，并通过有限轮次的验证反馈检查结论依据与任务完成情况。<br>
  Offers an optional multi-agent workflow where a coordinator delegates up to two concurrent investigation tasks, with bounded verification feedback checking evidence support and task completion.
* 实现持久化任务队列、运行状态、检查点、取消与恢复，以及服务器发送事件（SSE）进度和事件后续追问；当前支持本地单工作进程部署。<br>
  Implements persistent task queues, run state, checkpoints, cancellation and recovery, Server-Sent Events (SSE) progress, and incident follow-up questions, with support for a local single-worker deployment.
* 支持可选的快照式检索增强生成（RAG），并结合 Langfuse 追踪与评估、脚本化回放和 OpenTelemetry Demo 可复现故障用例验证工作流。<br>
  Supports optional snapshot-based retrieval-augmented generation (RAG), alongside Langfuse tracing and evaluation, scripted replays, and reproducible OpenTelemetry Demo fault cases for workflow validation.
</details>

<details>
  <summary>✨ <a style="text-decoration:none;" href="https://github.com/johnnyjly/Astra">Astra</a> - Python / SQLAlchemy</summary>
  <br>

* 为 **QEYnet Inc.** 开发图形界面应用，帮助员工和客户读取卫星遥测数据、进行交互，并管理基于标签的告警。<br>
  A GUI-based application for **QEYnet Inc.**, enabling their employees and customers to read and interact with satellite telemetry data and manage tag-sensitive alarms.
* 使用 SQLAlchemy 设计并构建可靠的数据库，支持多种设备、告警和遥测数据的高效检索与存储。<br>
  Designed and engineered a robust database using SQLAlchemy for efficient data retrieval and storage across multiple devices, alarms, and telemetry data.
* 实现可靠且可扩展的文件读写机制，读取自定义遥测文件，确保跨会话的数据持久化，并兼容多种设备配置。<br>
  Implemented reliable and scalable file I/O mechanisms for reading custom telemetry files, ensuring data persistence across sessions and seamless integration with diverse device configurations.
* 在持续集成（CI）工作流中开展全面测试，确保数据完整性和应用可靠性。<br>
  Conducted comprehensive testing within a CI workflow, ensuring data integrity and application reliability.
* 在完整的敏捷开发周期中协作，通过 Notion 使用 Scrum 和看板方法，全面完成合作方的需求。<br>
  Collaborated within a full Agile development cycle using Scrum and Kanban methodologies via Notion, and perfectly accomplished all the partner’s requirements.
</details>

<details>
  <summary>🌱 <a href="https://github.com/johnnyjly/Petpal">Petpal</a> - HTML / CSS / Django REST / JavaScript / React.js</summary>
  <br>

* 一个完整的宠物领养平台：领养申请者可以搜索宠物并提交申请，送养方可以创建收容所、发布宠物信息并管理领养审批。<br>
  A comprehensive pet adoption platform that enables pet seekers to search and apply for pets, while allowing shelter operators to establish shelters, list pets, and manage adoption approvals.
* 前端：使用 React 开发动态、响应式用户界面，通过 React Hooks 高效管理状态，使用 React Router 实现客户端路由，并提供直观的导航体验。<br>
  Frontend - Developed a dynamic and responsive user interface using React, incorporating React Hooks for efficient state management, React Router for seamless client-side routing, and intuitive navigation features.
* 后端：使用 Django REST Framework 构建可靠的 RESTful API，结合模型、序列化器和增删改查（CRUD）视图处理数据操作，并通过基于 JWT 的令牌认证保护用户数据。<br>
  Backend - Constructed a robust RESTful API with the Django REST Framework, utilizing models and serializers alongside CRUD Views to handle all data operations effectively. Implemented token-based authentication using JWT to secure user data.
</details>

<details>
  <summary>🔭 <a href="https://github.com/johnnyjly/NLP-Research-Project">基于 BERT 模型的实证研究 / Empirical Study on BERT-based model</a> - PyTorch / 深度学习（Deep Learning）</summary>
  <br>

* 基于真实招聘数据集中的预处理文本，为数据分析师岗位开发基于 BERT 的薪资预测模型，测试准确率达到 84%。<br>
  Developed a BERT-based salary prediction model for Data Analyst on real job datasets (information with texts after preprocessing) with an 84% test accuracy.
* 开展实证研究，比较增强的预训练 BERT 模型、循环神经网络（RNN）模型和梯度提升决策树（GBDT，基线模型）在表格数据上的表现。<br>
  Conducted an empirical study that compares the performance among the augmented pre-trained BERT model, RNN model and the gradient-boosted decision tree (GBDT/baseline) on tabular data.
</details>

<hr>

<p align="center">
  <a href="https://www.linkedin.com/in/johnnyjiangly/"><img src="https://img.shields.io/badge/LinkedIn-blue?logo=linkedin&logoColor=white&labelColor=light%20blue" alt="领英个人主页 / LinkedIn profile"/></a>
  <a href="https://github.com/johnnyjly/"><img src="https://img.shields.io/badge/GitHub-black?logo=github&logoColor=white" alt="GitHub 个人主页 / GitHub profile"/></a>
  <a href="mailto: johnny.lingyunjiang@gmail.com"><img src="https://img.shields.io/badge/Gmail-red?logo=gmail&logoColor=white" alt="电子邮箱 / Email"/></a>
</p>
