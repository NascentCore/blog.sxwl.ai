# blog.sxwl.ai

算想未来博客

## 技术栈

- Docusaurus: 一个基于 React 的静态网站生成器，用于构建文档网站和博客。
- React: 用于构建用户界面的 JavaScript 库。
- TypeScript: 一种静态类型检查的 JavaScript 超集。

## 安装和使用

node 版本 >= 18

```bash
yarn install # 安装依赖包
yarn start # 启动开发服务器
yarn build # 打包
```

## 博客使用方式

1：进入博客目录

首先，进入项目中用于存放博客文章的目录。这个目录名为 blog，可以使用终端进入该目录：

```
cd blog
```

2：创建博客文章文件

在博客目录中，需要为每篇博客文章创建一个单独的 Markdown 文件。文件名通常包括日期和标题，以确保博客文章可以按时间顺序排列。可以使用文本编辑器创建一个新文件，或者使用命令行创建。以下是一个示例命令：

```
touch 2023-11-08-my-blog-post.md
```

这将创建一个名为 2023-11-08-my-blog-post.md 的新博客文章文件。

3：编辑博客文章内容

打开博客文章文件，使用 Markdown 编写博客文章的内容。在文件的开头，可以使用 YAML 头信息来指定文章的元数据，例如标题、作者和日期。示例：

```
---

title: My Blog Post
author: John Doe
date: 2023-11-08

---

# 博客文章标题

这里是博客文章的内容。可以在这里使用标准的 Markdown 语法编写文章，包括标题、段落、列表、链接、代码块等。

博客文章内容可以是要分享的任何信息，包括技术教程、新闻、个人见解等。
```

确保在 YAML 头信息的分隔符 (---) 之后添加一个空行，然后开始编写文章的正文内容。

4：保存和关闭文件

完成了博客文章的编辑，保存文件并关闭文本编辑器。

5：本地预览

在终端中，返回到项目根目录并运行以下命令，以启动本地开发服务器以预览博客文章：

```
yarn start
```

在浏览器中访问 http://localhost:3000，能够看到新创建的博客文章。

6：部署博客文章

希望将其发布到网站上，运行以下命令来构建静态文件：

```
yarn build
```

生成的静态文件将存储在 build 文件夹中。可以将这些文件部署到静态文件托管服务上，在互联网上分享博客文章。
