简历网站模板 - 项目概述
项目简介
这是一个现代化、响应式的个人简历网站模板，专为开发人员、设计师和创意专业人士设计。该模板结合了优雅的视觉设计、流畅的动画效果和完整的简历内容模块，帮助用户快速创建专业且令人印象深刻的在线简历。

🌟 现代化设计
深色主题与蓝色渐变：专业感十足的配色方案

响应式布局：完美适配桌面、平板和移动设备

优雅的动画效果：滚动动画、悬停效果和技能进度条动画

📄 完整简历模块
个人信息展示区

专业技能展示（带进度条）

工作经验时间线

教育背景

项目作品集展示

联系表单和信息

⚡ 技术亮点
纯HTML/CSS/JS实现：无需复杂依赖

性能优化：轻量级代码，快速加载

交互功能：

平滑滚动导航

动态技能进度条

表单验证

响应式设计

🌐 社交整合
社交媒体链接

联系表单集成

下载简历功能

使用方式
下载模板：

bash
git clone https://github.com/yourusername/resume-template.git
cd resume-template
修改内容：

打开 index.html 文件

根据个人情况修改内容：

个人信息（姓名、职业等）

工作经验

技能列表

项目展示

联系信息

自定义样式：

打开 <style> 标签内的 CSS 代码

修改颜色变量（:root 部分）：

css
:root {
  --primary: #2563eb; /* 主色调 */
  --primary-dark: #1d4ed8; /* 主色调深色 */
  --secondary: #10b981; /* 辅助色调 */
  --dark: #0f172a; /* 深色背景 */
  --light: #f8fafc; /* 浅色文字 */
}
添加个人照片：

替换 profile-img::before 中的背景图片URL：

css
.profile-img::before {
  background: url('path/to/your/photo.jpg') center/cover;
}
部署网站：

可直接上传到 GitHub Pages、Netlify 或任何静态网站托管服务

或直接在浏览器中打开 index.html 查看效果

项目结构
plaintext
resume-template/
├── index.html               # 主页面文件
├── assets/                  # 资源文件夹（可选）
│   ├── images/              # 图片资源
│   ├── css/                 # 样式文件（如分离）
│   └── js/                  # JavaScript文件（如分离）
自定义选项
内容配置
个人信息：修改 hero-text 部分

工作经验：更新 timeline-content 部分

技能：调整 skills-container 中的技能名称和百分比

项目：编辑 portfolio-grid 中的项目卡片

功能定制
联系表单：修改表单字段或添加后端集成

动画效果：调整 @keyframes 动画参数

导航菜单：添加或修改导航链接

浏览器支持
Chrome (最新版本)

Firefox (最新版本)

Safari (最新版本)

Edge (最新版本)

移动端浏览器

贡献指南
欢迎提交问题和拉取请求！请确保：

遵循现有代码风格

添加有意义的注释

测试所有更改

许可证
本项目采用 MIT 许可证

实时预览
点击查看在线演示
