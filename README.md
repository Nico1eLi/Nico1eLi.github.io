# Guo LI - Personal Academic Website

这是我的个人学术网站，使用Hugo构建，部署在GitHub Pages上。

## 🚀 网站特性

- 响应式设计，支持移动端和桌面端
- 个人介绍和研究经历展示
- 学术成果和会议参与记录
- 教育背景和简历下载
- 暗黑模式支持（可配置）

## 🛠️ 技术栈

- **静态网站生成器**: Hugo
- **主题**: hugo-profile
- **部署平台**: GitHub Pages
- **自动化部署**: GitHub Actions

## 📁 项目结构

```
.
├── .github/workflows/    # GitHub Actions配置
├── content/              # 内容文件
├── layouts/              # 自定义布局
├── static/               # 静态资源
├── themes/               # Hugo主题
├── config.yaml           # 网站配置
└── public/               # 构建输出（自动生成）
```

## 🚀 本地开发

1. 安装Hugo
   ```bash
   # Windows (使用Chocolatey)
   choco install hugo-extended
   
   # 或下载二进制文件
   # https://gohugo.io/installation/
   ```

2. 克隆项目
   ```bash
   git clone https://github.com/Nico1eLi/Nico1eLi.github.io.git
   cd Nico1eLi.github.io
   ```

3. 启动开发服务器
   ```bash
   hugo server -D
   ```

4. 访问 http://localhost:1313

## 🚀 部署

网站通过GitHub Actions自动部署：

1. 推送代码到`main`分支
2. GitHub Actions自动构建Hugo网站
3. 自动部署到GitHub Pages
4. 访问 https://Nico1eLi.github.io

## 📝 更新内容

要更新网站内容，只需：

1. 修改`content/`目录下的Markdown文件
2. 修改`config.yaml`中的配置
3. 提交并推送到GitHub
4. 等待自动部署完成

## 🔧 自定义配置

主要配置在`config.yaml`文件中：

- 个人信息和介绍
- 研究经历和成果
- 教育背景
- 社交媒体链接
- 主题设置

## 📞 联系方式

- 邮箱: nico1elee@outlook.com
- GitHub: [Nico1eLi](https://github.com/Nico1eLi)

## �� 许可证

本项目使用MIT许可证。
