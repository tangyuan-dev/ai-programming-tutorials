# 03. 用自然语言写第一个程序

不需要懂编程，用自然语言也能写程序！

## 目标

用自然语言创建一个**计算器 Web 应用**

## 开始之前

确保已安装 OpenClaw：
```bash
npm install -g openclaw
openclaw start
```

## 第一步：描述需求

对 OpenClaw 说：
```
"帮我创建一个计算器 Web 应用，包含：
1. 加减乘除四个按钮
2. 显示结果的屏幕
3. 清除按钮
4. 现代化的深色主题设计"
```

## 第二步：AI 生成代码

OpenClaw 会：
1. 创建项目目录
2. 生成 HTML/CSS/JS
3. 完成后告诉你文件位置

## 第三步：测试运行

用浏览器打开生成的 HTML 文件即可使用。

## 进阶：添加功能

继续对话：
```
"添加科学计算功能，支持sin、cos、tan"
```

```
"添加历史记录功能"
```

## 代码示例

如果你想看生成的代码，可以直接打开文件：

```html
<!-- 生成的代码示例 -->
<div class="calculator">
  <div class="display">0</div>
  <div class="buttons">
    <button>7</button>
    <button>8</button>
    <button>9</button>
    <button>+</button>
    <!-- ... -->
  </div>
</div>
```

## 常见问题

**Q: 生成的文件在哪里？**
A: 当前目录下，或 OpenClaw 告诉你的路径

**Q: 不符合预期怎么办？**
A: 直接描述你的想法，AI 会修改

**Q: 不满意可以改吗？**
A: 可以，随时告诉 AI 你的修改需求

## 下一步

- [04. 用 AI 开发 Todo App](./04-todo-app.md)
