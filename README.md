# 核辐射探测器复习题答案共建

文件 `question_pool.md` 即为题库文件，汇总复习题及对应答案。

目前各题答案基本补充完毕。想帮助创建更易读的 PDF 的同学可参加 [Overleaf](https://www.overleaf.com/8747925855fwbdrnvjyryr) 编辑用于阅读的 PDF 版。

下面为此库及相关工具的使用说明，以帮助参与共建时遇到障碍的同学。如有使用说明未涵盖的问题，请提 issue 要求补充。

## 使用说明

说明共分为三个部分，分别为：答案格式、如何提交答案或修正答案（Github 相关功能使用）及相关 Markdown 介绍。即使你熟悉相关操作，也建议阅读 “答案格式” 一节。

### 答案格式

题库文件中已附上第一题答案，作为答案格式示例。若觉得其内容需要更改，按正常方式更改即可；若对其格式有意见建议，请提 issue 讨论。下面介绍答案格式。

建议提交答案时包含如下三部分：答案正文、来源和讨论。“答案正文” 即为考试时应填写的内容。“来源” 为答案正文的具体出处，每一点都应标注各自来源。若来源于某书，请具体到页数；若来源于课程视频，请具体到节数及分钟；若来源于网页，请附上网址……“讨论” 不是必填项，如想针对答案添加备注或评论，请添加于此处。

题库文件为 Markdown 格式的文本文件，但参与共建不需要任何 Markdown 基础。如果你以前未接触过 Git 或 Github，那么可能需要浏览下方 “如何提交答案或修正答案” 一节以了解必备知识。在网页端即可完成所有操作。

### 如何提交答案或修正答案

通过如下三、四个步骤即可编辑题库文件 `question_pool.md` 并提交修改。

- 第零步：打开题库文件

点击上方的 “question_pool.md” 即可打开并浏览题库。

- 第一步：点击笔状 “编辑” 按钮

![README_howtoedit_step_1](https://user-images.githubusercontent.com/95536266/144718431-49d710b7-8366-41c5-a7f0-dd011e23c49b.png)

点击显示着文档内容的框右上角的笔状按钮，即上图红框内的按钮。之后，页面将跳转到编辑页面，可以开始更改文档内容了！

- 第二步：保存所编辑的内容

![README_howtoedit_step_2](https://user-images.githubusercontent.com/95536266/144718554-6be38aef-4d42-44a5-baab-6c9908ca14a3.png)

完成编辑后，当然是要 “保存”。滚动页面至底部，你会看到 “Propose changes” 框。框中有一上一下两个文本输入栏，在上方的栏中请简要输入此次编辑所作的更改，例如 “增加第 2 题的答案”，或 “改进第 2 题的答案”；下方的栏是选填项，其中可填入具体的编辑事项，例如 “纠正核乳胶的缺点中某点，因为……”。填写完成后，再点击如上图所示的绿色按钮 “Propose changes” 即可。

- 第三步：提交所作修改

![README_howtoedit_step_3](https://user-images.githubusercontent.com/95536266/144718842-6ce9205d-c984-4401-a80b-e3a2b4dcc27a.png)

编辑完仅 “保存” 的话，你修改过的版本仅你自己拥有。要提交到当前项目中来和别人分享，需发送一个 “合并请求”，要求将自己做出的修改施加到当前项目中的文档上来。这是因为点击 “编辑” 按钮时你将此文档（乃至整个项目）复制了一份给自己，之后只是对自己所拥有的那一份复制件进行修改。

上一步点击完绿色按钮 “Propose changes” 后，跳转到的是让你查看所作的修改的页面，再点击如上图所示的绿色按钮 “Create pull request” 就能跳转到创建合并请求的页面。类似保存所编辑的内容，填写合并请求的标题和内容并提交后，等待别人来确认合并即可。欢迎有意参与处理合并请求的同学提 issue 报名。

### 相关 Markdown 语法

上面 “不需要任何的 Markdown 基础” 当然不是骗人的，但若你想写数学公式，可能得了解一下相关 Markdown 语法。而且，实际上只需了解 Markdown （Github） 插入数学公式的方法这一点。

在标准 Markdown 语法中，把 “$” 当括号将 LaTeX 格式的数学公式 “括” 起来即可。不过，Github 不支持此特性，我们必须使用一些额外的手段。若需在 Github 的 Markdown 预览里插入公式，将 LaTeX 格式的公式放在 `<img src="https://render.githubusercontent.com/render/math?math=">` 这一链接里的等号之后即可。这样，就以图片形式插入了对应的数学公式。例如，文本 `<img src="https://render.githubusercontent.com/render/math?math=\pi \neq 0">` 在预览中会被替换为 <img src="https://render.githubusercontent.com/render/math?math=\pi \neq 0">。

顺便介绍一下，`**示例文本**`（**示例文本**） 用两个星号 “`**`” 将内容 “括” 起来代表加粗。有兴趣的同学可以直接查阅 [Github 官方的格式语法指南](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)。

## 其他事项

- 在 Github 以 Markdown 显示物理文档还是有点勉强，或许应该用在线 LaTeX 文档协作工具 [Overleaf](https://www.overleaf.com/)，不过我会每隔一段时间更新一个 PDF 版并上传，以方便有需要的同学。
