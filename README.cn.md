# Awesome-Graphs

🌐️ 中文 | [English](README.md)

> 以图的方式思考图计算。

![](docs/images/awesome-graphs.jpg)


## 简介

**Awesome-Graphs**旨在收录图计算系统相关的论文和产品，并以图谱的形式描绘它们之间的衍生关系，帮助研究者和开发者快速熟悉图计算领域。

## 快速开始

下载并在浏览器中访问文件`index.html`。


## 功能介绍

* 当下收录了图计算系统发展十余年的论文，并以图谱的形式描绘了论文的引用关系。
* 检索/点击图计算系统节点实现引用链路分析，并区分直接、间接、双向引用关系。
* 拖曳图计算系统节点查看引用和被引用关系。
* 收录了部分图计算系统产品，统一挂载到根节点`Graph Database`下。
* 查看图计算系统原始论文或产品官网。【待开发】
* 更丰富的数据和交互形态。【待开发】

## 代码贡献

* 项目只依赖前端组件[vis.js](https://visjs.org/)，要对图谱数据进行调整，只需要修改`index.html`文件中`nodes`和`edges`的定义。
* 新增图计算系统产品节点只需要标记`_type`属性为`db`即可，如`{id: 'TuGraph', label: 'TuGraph', color: 'white', _type: 'db'},`。
* 双向引用的图计算系统论文只需添加一条边，并标记为红色双向箭头格式。如`{from:'GraphChi',to:'PowerGraph',color:'red',arrows:{to:{enabled:true,scaleFactor:1},from:{enabled:true,scaleFactor:1}}},`表示`GraphChi`和`PowerGraph`存在互相引用（同时发表于OSDI-2012）。
* 受人工整理限制，数据中难免出现错误和遗漏，欢迎大家一起贡献勘误和未录入的论文和产品信息。


## 联系我们

加入[TuGraph](https://github.com/TuGraph-family)社区，一起讨论并完善[Awesome-Graphs](https://github.com/TuGraph-family/Awesome-Graphs)！

![](docs/images/contacts.cn.png)

