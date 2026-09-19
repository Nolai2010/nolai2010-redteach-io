# 学习帮（redteach）

一个纯静态的研学打卡单页，主题为理论学习与阅读成就记录。

## 页面内容

- **index.html**：主页面，含 12 项成就按钮（如「做到品学兼优」「学习马克思主义」「阅读共产党宣言」等），点击跳转对应学习资料链接并在新标签页打开
- **law.html**：声明页「禁止非法操作」

## 技术说明

- 纯 HTML / CSS / JavaScript 单页，无构建、无依赖、无后端
- 成就数据以 `achievements` 对象在页面内维护
- 按钮由 `createButton()` 动态生成，链接与文案集中在 `initialButtons` 数组中配置

## 使用方式

无需安装任何依赖，直接用浏览器打开 `index.html` 即可。

## 文件结构

```
├── index.html        # 主页面（成就打卡 + 学习资料链接）
├── law.html          # 声明页
├── icon.png          # 站点图标
├── button.jpg        # 按钮背景图
├── container-bg.png  # 容器背景图
└── stop.png          # 声明页图片
```
