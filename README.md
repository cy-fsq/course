# 郑利娜老师个人页面

这是广东科学技术职业学院商学院商务数据分析与应用专业郑利娜老师的个人页面，展示个人简介和课程信息。

## 功能特点

- 个人简介：展示教师基本信息和专业背景
- 课程列表：包含Python基础、数据分析技术、数据采集与处理、供应链数据分析、数据库原理与应用等课程
- 联系方式：提供邮箱、电话和地址信息
- 响应式设计：适配桌面端和移动端
- 纯静态页面：使用HTML、CSS和JavaScript构建

## 技术栈

- 前端：纯静态HTML + CSS + JavaScript
- 样式框架：Tailwind CSS@3
- 图标库：Font Awesome
- 部署：Cloudflare Pages

## 部署到Cloudflare Pages

### 步骤1：准备文件

确保你的项目目录包含以下文件：
- `index.html` - 主页面文件
- `README.md` - 项目说明文件

### 步骤2：创建Cloudflare Pages项目

1. 登录 [Cloudflare Dashboard](https://dash.cloudflare.com/)
2. 点击左侧菜单中的 "Pages"
3. 点击 "Create a project"
4. 选择 "Direct Upload" 选项
5. 点击 "Upload assets"
6. 选择你的项目目录中的所有文件
7. 点击 "Deploy"

### 步骤3：配置域名（可选）

部署完成后，你可以：
1. 使用Cloudflare提供的默认域名（格式为 `your-project.pages.dev`）
2. 配置自定义域名，将你的域名指向Cloudflare Pages

## 后续更新

要更新页面内容：
1. 修改 `index.html` 文件
2. 重新上传到Cloudflare Pages
3. 部署新的版本

## 课程内容补充

后续可以为每个课程创建详细的内容页面，例如：
- `courses/python-basics.html` - Python基础课程详情
- `courses/data-analysis.html` - 数据分析技术课程详情
- `courses/data-collection.html` - 数据采集与处理课程详情
- `courses/supply-chain.html` - 供应链数据分析课程详情
- `courses/database.html` - 数据库原理与应用课程详情

然后更新 `index.html` 中的课程链接，指向这些详细页面。