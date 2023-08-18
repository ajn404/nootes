# Toturial

mdBook 是一个使用 Markdown 创建书籍的命令行工具
它号称是 GitBook 的替代者，它是用 Rust 开发的文档构建工具，特别轻量，不依赖开发环境，仅仅一个可执行文件就能完成文档构建2。

在使用 mdBook 之前，请检查 Rust 环境是否安装。如果已安装，请跳过该步骤。接下来，您可以使用以下步骤安装和使用 mdBook：

安装：使用 `cargo install mdbook `命令安装 mdBook。
初始化：在当前文件夹下，初始化执行 mdbook init 指令，生成如下目录结构：
```
book-test/
├── book
└── src
    ├── chapter_1.md
    └── SUMMARY.md
```
启动：执行 `mdbook serve` 指令后，打开浏览器，输入：localhost:3000/ 即可看到渲染页面。
构建：使用 `mdbook build` 命令构建书籍。