# vite-plugin-vue2 源码解析文档

vite-plugin-vue2 源码解析沉淀文档。

通过源码调研，解决业务项目迁移 vite 过程中的问题：

1. template 编译失败
2. style 中，如果通过 @import 的方式引入了外部文件，在外部文件中，包含了 /deep/ 语法，vite:css 插件会报错