# 《软件设计的哲学》中文翻译

在线阅读：https://Cactus-proj.github.io/A-Philosophy-of-Software-Design-zh/

<div style="inline">
  <img src="./docs/cover.jpeg" width="210px" height="280px" />
</div>


## 前言

斯坦福教授、Tcl 语言发明者 John Ousterhout 的著作《A Philosophy of Software Design》，自出版以来，好评如潮。按照 IT 图书出版的惯例，如果冠名为“实践”，书中内容关注的是某项技术的细节和技巧；冠名为“艺术”，内容可能是记录一件优秀作品的设计过程和经验；而冠名为“哲学”，则是一些通用的原则和方法论，这些原则方法论串起来，能够形成一个体系。正如”知行合一”、“世界是由原子构成的”、“我思故我在”，这些耳熟能详的句子能够一定程度上代表背后的人物和思想。用一句话概括《A Philosophy of Software Design》，软件设计的核心在于降低复杂性。


## 目录

- [前言](docs/preface.md)
- [第 1 章 介绍](docs/ch1.md)
- [第 2 章 复杂性的本质](docs/ch2.md)
- [第 3 章 工作代码是不够的](docs/ch3.md)
- [第 4 章 模块应该是深的](docs/ch4.md)
- [第 5 章 信息隐藏(和泄漏)](docs/ch5.md)
- [第 6 章 通用模块更深入](docs/ch6.md)
- [第 7 章 不同的层，不同的抽象](docs/ch7.md)
- [第 8 章 降低复杂性](docs/ch8.md)
- [第 9 章 在一起更好还是分开更好？](docs/ch9.md)
- [第 10 章 定义不存在的错误](docs/ch10.md)
- [第 11 章 设计它两次](docs/ch11.md)
- [第 12 章 为什么写评论呢？四个理由](docs/ch12.md)
- [第 13 章 注释应该描述代码中不明显的内容](docs/ch13.md)
- [第 14 章 选择的名字](docs/ch14.md)
- [第 15 章 先写评论](docs/ch15.md)
- [第 16 章 修改现有的代码](docs/ch16.md)
- [第 17 章 一致性](docs/ch17.md)
- [第 18 章 代码应该是显而易见的](docs/ch18.md)
- [第 19 章 软件发展趋势](docs/ch19.md)
- [第 20 章 设计性能](docs/ch20.md)
- [第 21 章 结论](docs/ch21.md)
- [总结](docs/summary.md)


## 本地开发 & 阅读

本项目基于 VuePress 进行开发，以提供比 Github Mardown 更佳的阅读体验

依赖于 [`node.js`][nodejs]、[`yarn`][yarn]、[`vuepress`][vuepress] 等环境

[nodejs]: https://nodejs.org/zh-cn/
[yarn]: https://yarnpkg.com/
[vuepress]: https://vuepress.vuejs.org/zh/


```sh
git clone https://github.com/Cactus-proj/A-Philosophy-of-Software-Design-zh.git
cd A-Philosophy-of-Software-Design-zh/
yarn install    # 安装 VuePress
yarn dev        # 编译并打开网页预览
```


## License

[MIT](./LICENSE)
