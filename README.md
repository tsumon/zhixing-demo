# 知行 · 教育 AI 中台（在线交互演示版）

- **在线访问**：<https://tsumon.github.io/zhixing-demo/>
- **运行方式**：纯静态 GitHub Pages + Pyodide（WebAssembly 本地运行 Python 业务引擎、SQLite、Pydantic、SQLGlot 与状态编排），**零后端服务器、零外部大模型 API 调用、所有演示数据与状态均在访客浏览器本地沙盒内运行**。
- **涵盖模块**：
  1. 教研知识库问答与版本隔离（逐句引用核验 + 拒答）
  2. 240 题 RAG Harness 自动化评测回归门禁
  3. 作文 AI 初评、复核与三评路由
  4. 学情问数与 AST SQL 复算归因
  5. 教学干预多角色协作、减负红线校验与人工审批幂等执行
