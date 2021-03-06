Change History
==============

v1.1.9
---
* [Feature] 支持 SPA 下多个路由路径拥有各自的 Skeleton

v1.1.8
---
* [Fix] 针对`entry`名称中包含连字符的情况，增加`[nameHash]`占位符

v1.1.7
---
* [Fix] 由于不是所有编辑器都在文件末尾自动添加空行。Loader 为路由文件添加 import 语句时插入换行符。[ISSUE#5](https://github.com/lavas-project/vue-skeleton-webpack-plugin/issues/5)

v1.1.6
---
* [Feature] 支持新参数 quiet，在服务端渲染时是否需要输出信息到控制台
* [Fix] 服务端渲染组件完成后，自动关闭 webpack 对内存文件系统的监听

v1.1.4
---
* 支持 webpack 3.0.0 以上，修复了不填写 entry 名称导致的 bug

v1.1.2
---
* 增加多页应用开发模式下，自动插入各个页面skeleton对应的路由
* 增加loader多种参数配置
