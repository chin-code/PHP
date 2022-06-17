# PHP

php program language



# 1. Laravel 教程 - Web 开发实战入门

## 第一章 基础信息

<hr />

**培养自行解决问题的能力**

我们程序员，是问题的解决者。

当你在学习本课程遇到问题时，建议自己先尝试解决问题。培养自己独立思考，检索信息能力，**能让你在工作中得心应手**（那个时候没有人能帮你）。

**如何自己动手来解决问题？**

- 第一步：自检
- 第二步：文章下方讨论
- 第三步：搜索论坛文章
- 第四步：认真提问



## 第二张 开发环境布置

<hr />



如果你在 Mac 上开发并且已经安装了 [Docker Desktop](https://www.docker.com/products/docker-desktop)，你可以使用一个简单的终端命令来创建一个新的 Laravel 项目。 例如，要在名为「example-app」的目录中创建一个新的 Laravel 应用程序，您可以在终端中运行以下命令：

```
curl -s "https://laravel.build/example-app" | bash
```

创建项目后，您可以导航到应用程序目录并启动 Laravel Sail。Laravel Sail 提供了一个简单的命令行界面，用于与 Laravel 的默认 Docker 配置进行交互：

```
cd example-app

./vendor/bin/sail up
```

启动应用程序的 Docker 容器后，您可以在 Web 浏览器中访问应用程序： [localhost](http://localhost/) 。

**注意：** `sail up` 命令运行成功后，会一直显示软件的实时日志界面。

此时你可以 `ctrl+c` 中断运行，再次运行时，可以使用 `-d` 参数让 `sail up` 命令在后台运行：

```
./vendor/bin/sail up -d
```



















