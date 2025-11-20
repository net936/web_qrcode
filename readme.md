# 在线二维码生成器

<div align="center">

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?logo=bootstrap&logoColor=white)

**快速、简单、免费的在线二维码生成工具**

[在线演示](https://qrcode.gitapp.cn) | [问题反馈](https://github.com/net936/web_qrcode/issues)

</div>

---

## 📖 项目简介

这是一个功能强大的在线二维码生成器，采用纯前端技术实现，无需后端服务器。用户可以快速将文本、网址、电话号码等信息转换为二维码图片，并支持实时预览和下载保存。

本工具基于 QRCode.js 库开发，界面简洁美观，操作简单便捷，适合个人和商业使用。

## ✨ 主要特性

### 🚀 核心功能
- **即时生成**：输入内容后即时生成二维码，无需等待
- **高清画质**：生成 256x256 像素高清二维码图片
- **多种格式**：支持文本、网址、电话、邮箱等多种数据格式
- **实时预览**：右侧实时显示二维码预览效果
- **一键下载**：右键点击二维码即可保存到本地

### 🎯 工具优势
- ✅ **完全免费**：无需注册登录，无使用次数限制
- ✅ **隐私安全**：纯前端本地生成，数据不上传服务器
- ✅ **快速高效**：无需等待，即时生成高质量二维码
- ✅ **多端适配**：支持电脑、手机、平板等各种设备
- ✅ **纠错机制**：采用高级别纠错算法（Level H）
- ✅ **开源免费**：MIT 许可证，可自由使用和修改

## 🛠️ 技术栈

- **HTML5** - 页面结构
- **CSS3** - 样式设计（渐变、动画、响应式）
- **JavaScript** - 交互逻辑
- **Bootstrap 3.3.7** - 响应式布局框架
- **jQuery 1.11.3** - DOM 操作
- **QRCode.js** - 二维码生成核心库
- **Font Awesome 4.7** - 图标库

## 📦 快速开始

### 在线使用

直接访问部署后的网站即可使用，无需安装任何软件。

### 本地部署

1. **克隆项目**
```bash
git clone https://github.com/net936/web_qrcode.git
cd web_qrcode
```

2. **启动服务**

由于项目为纯静态网页，可以使用任何 Web 服务器运行：

**方法一：使用 Python 内置服务器**
```bash
# Python 3.x
python -m http.server 8080

# Python 2.x
python -m SimpleHTTPServer 8080
```

**方法二：使用 Node.js http-server**
```bash
# 安装 http-server
npm install -g http-server

# 启动服务
http-server -p 8080
```

**方法三：使用 VS Code Live Server**
- 安装 Live Server 扩展
- 右键点击 index.html
- 选择 "Open with Live Server"

3. **访问应用**

打开浏览器访问：`http://localhost:8080`

## 📝 使用说明

### 基本使用

1. **输入内容**：在左侧文本框中输入您想要转换的内容

2. **生成二维码**：点击"生成二维码"按钮

3. **预览查看**：在右侧实时查看生成的二维码

4. **保存使用**：右键点击二维码图片，选择"图片另存为"即可保存到本地

### 高级功能

二维码采用 **Reed-Solomon 纠错算法**（Level H），即使二维码部分损坏（最多30%）也能正常扫描识别。

## 📂 项目结构

```
web_qrcode/
├── index.html                 # 主页面
├── readme.md                  # 项目说明文档
├── .gitignore                # Git 忽略文件配置
├── favicon.ico               # 网站图标
├── favicon_32x32.png         # 32x32 图标
├── favicon_114x114.png       # 114x114 图标（Apple Touch Icon）
├── static/                   # 静态资源目录
│   ├── style/               # 样式文件
│   │   └── tool.css        # 工具样式
│   ├── script/              # JavaScript 文件
│   │   ├── jquery-1.11.3.min.js      # jQuery 库
│   │   ├── bootstrap.min.js           # Bootstrap JS
│   │   ├── qrcode.js                  # 二维码生成库
│   │   ├── tool.js                    # 工具函数
│   │   └── pcjs/                      # 其他工具脚本
│   │       └── barcode.js             # 条形码相关
│   └── images/              # 图片资源
│       ├── qrcode-demo1.webp         # 演示图片1
│       └── qrcode-demo2.webp         # 演示图片2
```

## 🎨 界面预览

### 主界面
- 现代化的紫色渐变背景
- 清晰的四步使用说明
- 六大工具优势展示
- 响应式设计，适配所有设备

### 核心区域
- 左侧：大文本输入框
- 右侧：二维码实时预览
- 底部：操作按钮（生成、清空）

## 🌟 功能特点

### 二维码技术
- **编码模式**：支持数字模式、字符模式
- **纠错等级**：Level H（高级别，可恢复约30%损坏）
- **尺寸规格**：256x256 像素
- **颜色配置**：黑白经典配色，确保最佳识别率

### 应用场景
- 网址分享（社交媒体、营销推广）
- 名片制作（联系方式快速交换）
- 产品标签（商品信息、溯源）
- 活动签到（会议、展会）
- 文件分享（下载链接、文档地址）
- Wi-Fi 配置（网络名称和密码）

## 🤝 贡献指南

欢迎各种形式的贡献，包括但不限于：

- 🐛 提交 Bug 报告
- 💡 提出新功能建议
- 📝 改进文档
- 🔧 提交代码改进

### 贡献步骤

1. Fork 本仓库
2. 创建特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 提交 Pull Request

## 📄 开源协议

本项目采用 [MIT License](LICENSE) 开源协议。

您可以自由地：
- ✅ 商业使用
- ✅ 修改源代码
- ✅ 分发
- ✅ 私人使用

唯一的限制是：
- ❗ 需要保留原作者的版权声明

## 🔗 相关链接

- [QRCode.js 官方文档](https://davidshimjs.github.io/qrcodejs/)
- [Bootstrap 官方文档](https://getbootstrap.com/docs/3.3/)
- [二维码标准规范](https://www.iso.org/standard/62021.html)

## 📮 联系方式

- **项目地址**：[https://github.com/net936/web_qrcode](https://github.com/net936/web_qrcode)
- **问题反馈**：[Issues](https://github.com/net936/web_qrcode/issues)


## 💝 支持项目

如果这个项目对您有帮助，请给它一个 ⭐️ Star！

您的支持是我们持续改进的动力。

---

<div align="center">

**Made with ❤️ by net936**

Copyright © 2025 程序设计在线工具集

</div>
