# Markdown 应用场景的实例
1. 博客平台
•
GitHub Pages：使用 Jekyll 或 Hugo 等静态站点生成器，结合 Markdown 编写博客文章。
•
WordPress：通过插件支持 Markdown 编写博客。
•
Medium：虽然不完全是 Markdown，但 Medium 的编辑器支持类似 Markdown 的简化语法。
2. 技术文档与API文档
•
Swagger：用于自动生成 RESTful API 的文档，结合 Markdown 描述 API 接口。
•
Read the Docs：一个在线文档托管平台，支持 Markdown 和其他标记语言编写的文档。
•
GitHub Readme：项目的 README 文件通常用 Markdown 编写，介绍项目的基本信息和使用方法。
3. 代码注释与Git仓库
•
GitHub、GitLab、Bitbucket：在代码仓库中，除了代码文件，Markdown 文件也常用于编写项目文档、更新日志和贡献指南。
•
VS Code、Sublime Text：这些编辑器支持 Markdown 预览，方便在代码项目中添加和查看 Markdown 文档。
4. 邮件编写
•
Gmail、Outlook（通过插件）：虽然原生不支持，但可以通过浏览器插件（如 Nimbus Notes、Markdown Here）将 Markdown 邮件转换为 HTML 格式发送。
5. 微信公众号
•
使用第三方工具（如秀米、135编辑器）将 Markdown 文档转换为适合微信公众号发布的格式。
6. 笔记与知识管理
•
Typora、Bear、Notion、Joplin：这些应用都支持 Markdown 语法，方便用户记录、整理和分享笔记。
7. 电子书与书籍编写
•
Pandoc：一个强大的文档转换工具，支持将 Markdown 文档转换为多种电子书格式（如 ePub、MOBI、PDF）。
•
GitBook：一个基于 Git 的电子书平台，支持 Markdown 编写并自动生成书籍网站。
8. 学术论文与研究报告
•
结合 Markdown 和 LaTeX，使用专门的工具（如 Pandoc、Markdown Editor for LaTeX）编写包含复杂公式和引用的文档。
9. 大模型对话与AI助手
•
ChatGPT、New Bing：在与这些 AI 模型的对话中，Markdown 可以用于格式化请求或响应，使内容更加清晰。
10. 演示文稿与幻灯片
• 
arp、Remark.js：这些工具允许用户使用 Markdown 编写幻灯片内容，并生成美观的演示文稿。
# 简要学习 Markdown 语法
 基本语法
•
标题：# 表示一级标题，## 表示二级标题，依此类推。
•
段落：直接编写文本即可，多个空行表示段落分隔。
•
列表：
•
无序列表：使用 -、+ 或 * 加空格。
•
有序列表：使用数字加英文句点 . 加空格。
•
代码：
•
行内代码：使用单个反引号 ` 包裹。
•
代码块：使用三个反引号 ````` ``` ```` 包裹，可指定语言进行语法高亮。
•
链接：[链接文本](链接地址 "可选标题")。
•
图片：![图片alt](图片地址 "可选标题")。
•
分隔线：三个或以上的 -、* 或 _ 单独成行。
进阶语法
•
表格：使用 | 分隔单元格，第一行使用 - 分隔表头和其他行，可指定对齐方式。
•
字体样式：
•
斜体：*文本* 或 _文本_。
•
粗体：**文本** 或 __文本__。
•
删除线：~~文本~~。
•
任务列表：在列表项前添加 - [ ]（未完成）或 - [x]（已完成）。
•
HTML 混用：Markdown 支持直接嵌入 HTML 代码。