# 从零开始的 JSON 库
教程：https://github.com/miloyip/json-tutorial 作者：Milo Yip

## 特性及涉及知识

从零开始写一个 JSON 库，其特性如下：

* 符合标准的 JSON 解析器和生成器
* 手写的递归下降解析器（recursive descent parser）
* 使用标准 C 语言（C89）
* 跨平台／编译器（如 Windows／Linux／OS X，vc／gcc／clang）
* 仅支持 UTF-8 JSON 文本
* 仅支持以 `double` 存储 JSON number 类型
* 解析器和生成器的代码合共少于 500 行

涉及知识：

* 测试驱动开发（test driven development, TDD）
* C 语言编程风格
* 数据结构
* API 设计
* 断言
* Unicode
* 浮点数
* Github、CMake、valgrind、Doxygen 等工具
