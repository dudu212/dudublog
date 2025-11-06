在同一个GitHub仓库中，如果你有两个分支（比如main和gh-pages）都配置了GitHub Pages，那么它们会使用相同的URL（例如https://dudu212.github.io/dudublog/）来访问。但是，实际上GitHub Pages只能选择一个分支作为发布源。
当你进入仓库的Settings -> Pages，在“Branch”下拉框中你选择的分支就是GitHub Pages用于构建和发布的分支。

因此，无论你仓库里有多少个分支，只有被你设置为GitHub Pages源的那个分支会被部署到该仓库的Pages网址上。
如果你需要同时展示两个不同的页面，你可以考虑以下方法：

创建两个不同的仓库，每个仓库部署一个分支，这样就有两个不同的URL。

在同一个仓库中，利用GitHub Pages支持子目录的特性，例如将两个分支的内容分别放在不同的子目录中，然后通过不同的URL路径来访问。但是，GitHub Pages默认不支持在一个仓库中同时发布多个分支的内容。每个仓库只能有一个发布分支。
