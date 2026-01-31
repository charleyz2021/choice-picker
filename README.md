# Choice Picker / 随机选择器

A simple web-based random choice picker with rolling animation.
一个带滚动动画的网页随机选择小工具。

This project is designed to help decide what to do next by randomly picking
a category first, then a sub-task.
这个项目用于在多个选项中随机决定“接下来做什么”，
会先抽取一个大类，再抽取对应的小项。

---

## ✨ Features / 功能特点

- Pure HTML + CSS + JavaScript
  纯前端实现，无需任何依赖
- Rolling text animation
  滚动文字动画，而不是直接跳结果
- Works on desktop and mobile browsers
  支持电脑和手机浏览器
- Easy to customize
  修改数据即可自定义内容

---

## 🚀 How to Use / 使用方式

1. Open `index.html` in your browser
   在浏览器中打开 `index.html`
2. Click the button to start picking
   点击按钮开始抽选
3. Wait for the rolling animation to finish
   等待滚动动画结束即可看到结果

---

## 🛠 Customization / 自定义内容

You can edit the `data` object in `index.html` to change categories and tasks.
你可以直接修改 `index.html` 中的 `data` 对象来自定义内容。

Example / 示例：

```js
const data = {
  Work: ["Coding", "Editing", "Design"],
  Life: ["Cleaning", "Cooking", "Organizing"]
};
```

---

## 📌 Status / 当前状态

This project is currently in an early stage and mainly intended for personal use.
The core functionality is usable, but the structure and features may still evolve.

该项目目前处于早期阶段，主要用于个人使用。
功能已经可用，但整体结构和交互仍可能继续调整和优化。

---

## 📄 License / 开源协议

MIT License

This project is licensed under the MIT License.
You are free to use, modify, and distribute it, as long as the original license
and copyright notice are included.

本项目使用 MIT 开源协议。
你可以自由使用、修改和分发，但需保留原始版权声明和协议文本。
