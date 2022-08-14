## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.

## github pages
* HTML 生成和部署
执行mkdocs build会新建site目录，并将 markdown 文件构建为 html 文件。

* 执行mkdocs gh-deploy就可以site中的 html 内容提交到代码仓库的gh-pages分支上，你要在 Github 上 代码库的配置中起用 Pages 才可以看见站点，地址是 https://<你的用户名>.github.io/<你的代码仓库> 。