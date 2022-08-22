需求：配置 MiniExtractCssPlugin插件到第一天的作业里
本插件会将 CSS 提取到单独的文件中，为每个包含 CSS 的 JS 文件创建一个 CSS 文件，并且支持 CSS 和 SourceMaps 的按需加载。
本插件基于 webpack v5 的新特性构建，并且需要 webpack 5 才能正常工作。

当前版本 ："webpack": "^5.73.0",
1.  没有node_modules --yarn 下载需要的包
2.  查看文档 yarn add -D mini-css-extract-plugin 下载插件
3.  下载成功 查看如何配置