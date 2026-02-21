# Authelia Fidrua Custom

自定义 Authelia 登录页主题 - 科技感毛玻璃风格

## 特性

- 🌌 深色科技感背景
- 💫 动态漂浮光团效果（青色、紫色、粉色）
- 🥃 毛玻璃登录卡片
- ✨ 渐变流动边框
- 🎨 渐变标题文字
- 💎 霓虹按钮效果
- 📱 响应式设计

## 自动构建

此仓库通过 GitHub Actions 自动跟随上游 Authelia 更新：

- 每天自动检查上游新版本
- 检测到新版本后自动构建
- 自动推送到 Docker Hub

## Docker 镜像

```bash
docker pull donma033x/authelia-fidrua:latest
```

## 使用方法

替换官方 Authelia 镜像即可：

```yaml
services:
  authelia:
    image: donma033x/authelia-fidrua:latest
    # ... 其他配置保持不变
```

## 自定义

- `custom/custom.css` - 自定义样式
- `custom/logo.png` - 自定义 Logo

## License

基于 [Authelia](https://github.com/authelia/authelia) 项目
