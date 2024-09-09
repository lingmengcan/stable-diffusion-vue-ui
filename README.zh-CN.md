<h1 align="center">一个开源的参考stable diffusion web ui 的vue3 前端</h1>
<p align="center"><a href="README.md">English</a> | 中文</p>

The source code is in my another AI full-stack open-source project lingmengcan-ai (https://github.com/lingmengcan/lingmengcan-ai), and an independent pure front-end project for aigc will be separated out later.

lingmengcan-ai 是一个基于大模型的 ai 系统，目前提供大语言模型对话、模型管理、文生图和后台角色管理等等功能。使用的技术栈，包括 stable deffusion、openai、chatgpt、LangChainJS 作为 ai 层，Vue 3、Naive UI 和 Tailwind CSS 构建 UI 层，以及 NestJS、LangChainJS、MySQL 为服务层，chromadb 为向量数据库。该项目是一个可以实现**完全本地化**推理的知识库增强方案，同时提供 AIGC 功能， 重点解决数据安全保护，私域化部署的企业痛点。

AIGC 文生图，通过调用 stable diffusion webui 接口（后续加入其他多模态大模型的接口），生成图片和视频。
![效果如下](images/txt2img.png)
