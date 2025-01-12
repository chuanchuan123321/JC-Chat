# 基于python的多功能gpt-web网页

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Python](https://img.shields.io/badge/python-3.9+-blue.svg)
![Flask](https://img.shields.io/badge/flask-2.0.1-green.svg)

基于 ChatGPT API 开发的在线智能对话系统,支持代码实时运行的全国首创平台。

## 🌟 特性

### 核心功能
- 💬 智能对话:基于 GPT-4 的自然语言交互
- 🚀 代码实时运行:支持 Python、JavaScript、HTML 等语言
- 📝 Markdown 支持:结构化展示对话内容
- 📊 图表生成:支持数据可视化
- 📁 文件处理:支持 DOCX、PDF 文件解析
- 👥 用户系统:完整的注册登录功能
- 💎 会员系统:灵活的付费方案

### 技术亮点
- 🔒 安全沙箱:Docker 隔离的代码运行环境
- ⚡ 实时响应:流式传输的动态对话
- 🎨 优雅界面:响应式设计与动画效果
- 💾 数据存储:基于文件系统的 JSON 存储

## 🛠️ 技术栈

### 前端
- HTML5 + CSS3
- JavaScript
- Markdown 渲染
- 代码高亮
- 响应式设计

### 后端
- Python 3.9+
- Flask 框架
- OpenAI API
- Docker

## 🚀 快速开始

### 环境要求
- Python 3.9 或更高版本
- Node.js 环境
- Docker(可选,用于代码沙箱)

### 安装步骤

1. 克隆仓库

## 📚 功能模块

### 用户系统
- 注册/登录
  - 用户名密码登录
  - 记住登录状态
  - 登录状态验证
  - 会话管理
- 用户管理
  - 管理员权限控制
  - 用户账号激活
  - 用户信息存储

### 对话系统
- 对话管理
  - 创建新对话
  - 加载历史对话
  - 删除对话
  - 重命名对话
  - 对话列表展示
- 消息功能
  - 发送消息
  - 接收 AI 回复
  - 停止生成
  - 消息历史记录
  - 消息时间显示
  - 支持 Markdown 格式
- 代码处理功能
  - 代码高亮显示
  - 代码复制功能
  - 代码编辑功能
  - 实时代码运行
  - 运行结果展示

### 文件处理
- 文件上传
  - 支持 DOCX 文件
  - 支持 PDF 文件
  - 文件内容提取
  - 错误处理
- 文件导出
  - 图片下载功能
  - HTML预览导出
  - Python图表导出

### 会员系统
- 月度会员
  - 无限对话次数
  - GPT-4 模型支持
  - 优先响应
  - 7×24小时服务
- 年度会员
  - 包含月度会员所有功能
  - 更优惠的价格
  - 额外特权如更高并发限制
- 终身会员
  - 一次付费永久使用
  - 专属客服
  - 自定义模型训练

## 🔒 安全特性

### 密码加密存储
- 采用 bcrypt 加密算法
- 定期更新哈希算法
- 防止数据库泄露风险

### 会话验证
- 带过期时间的令牌机制
- 每次操作验证
- 防止会话劫持

### API 密钥保护
- 环境变量存储
- 权限管理审计
- 防止未授权调用

### 代码执行沙箱
- Docker 容器隔离
- 资源使用限制
- 文件系统访问控制
- 网络连接限制

## ⚡ 性能优化

### 动态加载
- 分页加载对话记录
- 滚动加载历史内容
- 减轻初始加载压力

### 缓存控制
- 静态资源缓存
- 用户配置缓存
- 模型调用结果缓存
- Redis 高效缓存服务

### 响应式设计
- CSS3 和 Flexbox 技术
- 多设备适配
- 一致的用户体验

### 错误处理机制
- 详细错误分类
- 友好错误提示
- 特定错误处理策略

## 🎯 开发计划

### 已实现功能
- [x] 基础对话功能
- [x] 代码实时运行
- [x] 文件处理
- [x] 会员系统
- [x] Markdown 支持
- [x] 代码高亮
- [x] 图表生成
- [x] 安全沙箱

### 待开发功能
- [ ] 语音输入
- [ ] 图片生成
- [ ] 多语言支持
- [ ] 移动端适配
- [ ] 主题定制
- [ ] 插件系统
- [ ] 团队协作功能
- [ ] API 接口开放

## 📄 许可证

本项目采用 MIT 许可证 - 详见 [LICENSE](LICENSE) 文件

## 🤝 贡献指南

1. Fork 本仓库
2. 创建特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 开启 Pull Request

## 📞 联系方式

- 作者: chuanchuan
- Email: [your-email@example.com]
- GitHub: [@chuanchuan123321](https://github.com/chuanchuan123321)

## 🙏 致谢

感谢以下开源项目:
- OpenAI GPT API
- Flask
- Docker
- Marked.js
- KaTeX
- Highlight.js

## 📜 更新日志

### v1.0.0 (2024-03-20)
- 初始版本发布
- 实现基础对话功能
- 支持代码实时运行
- 添加文件处理功能
- 集成会员系统

### v1.1.0 (计划中)
- 添加语音输入功能
- 优化移动端体验
- 增加主题定制选项
- 支持插件扩展

## 🌐 相关链接

- [项目文档](docs/README.md)
- [API 文档](docs/api.md)
- [部署指南](docs/deployment.md)
- [常见问题](docs/faq.md)
