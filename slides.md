---
theme: 'vuetiful'
clicks: 1
altCover: false 
---

# js 解析器实现
---
# 背景

解决column动态化小程序不能执行js的问题

---
# js 在浏览器运行过程

<img src="/img/ast.png">

---

# 编译器（编译原理）应用的场景

1. js的编译器（babel，eslint），例如：es6 语法编译成 es5的语法
2. ts编译
3. jsx， Less，vue文件编译成render函数， 等等的编译

---

# 常见的js编译器

1. babel(环境：node), ebuild(环境：go), swc(环境：rust)

2. js环境编译器， acorn（小巧，babel前期代码也是基于这个库），exprima 等等
<img src="/img/parser.png">

---

# 编译器一般的流程
<div class="pt-16">
<img src="/img/generatecode.png">
</div>


---

# 编译器tokenlizer 最小实现

<IframeCode url="https://codesandbox.io/embed/sweet-gagarin-rbx9j0?fontsize=14&hidenavigation=1&theme=dark"/>

---

# 编译器parser 最小实现

<IframeCode url="https://codesandbox.io/embed/suspicious-yonath-cc7dzp?fontsize=14&hidenavigation=1&theme=dark"/>

---

# 解析器runner 最小实现

<IframeCode url="https://codesandbox.io/embed/friendly-pike-dubzkn?fontsize=14&hidenavigation=1&theme=dark"/>

---


