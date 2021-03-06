双周简报编写指南
=======================================

CNRV双周简报是CNRV平均每两周编辑和整理的，一个以报导为主的新闻归纳页面。
报道时主要以简略和客观的方式报道新闻，捎带讲解和普及知识点。

## 工作流程

1. 建立一个新分支，使用模板建立下一期简报的初始页面。
2. 建立新分支的PR页面。
3. 搜集可以报道的新闻，将新闻列入PR的说明页。
4. 按照自愿领取或分配的方式，分工新闻条目到各简报编辑。
5. 简报编辑阅读新闻，撰写简报条目。
6. 通过直接修改或者PR的方式将编写的条目汇总到下一期简报中。
7. 审查简报格式，内部审阅简报预发布版本。
8. 发布简报（cnrv.io和微信平台）
9. 更新cnrv主页和简报存档页。

## 简报条目撰写规范

1. 尽量理解新闻的内容，然后归纳总结。
2. 可以摘抄较重要的原文。
3. 每一个条目需要给出至少一处的原文出处。

## Markdown语法和使用惯例

请参考官方[Markdown Syntax](https://daringfireball.net/projects/markdown/syntax)或者[中文翻译](http://wowubuntu.com/markdown/)来学习如何正确使用Markdown。

使用Markdown的核心思想有几点：

- 编辑方便，学习简单
- 要将内容和样式/排版分开，让更多的精力集中在内容本身，而非不断排版的过程。
- 使用Markdown要注意即使是在原始的文本编辑器中，也要尽可能的保持良好的可读性。（你可以打开这篇文章的源代码来查看器可读性）

以下是几点常见使用惯例或不好的地方。

### 引文和常见写法

为了阅读方便和有据可循，我们要求简报的每一个片段末都附有参考链接。

**重要的一点是，请尽可能使用最原始的文章，而非翻译过或者转发过的，请正确使用Google等搜索引擎保证文章来源是否位初始来源，而非经过演绎或修改。**

关于引文，有以下两种写法。

第一种，只有一条引文，请这样写

```
Link: [引文的文章全名，尽可能详细，或者是邮件列表中邮件的Title等](URL)
```

第二种，如果有多条引文，请注意Link和无序列表有一行空行，切无序列表和后面URL有一个空格。

```
Link:

- [FULL TITLE 1](URL 1)
- [FULL TITLE 2](URL 2)

```

### 段落的分隔

如果你要表达的是两段的内容，请在当中多加一行。否则会被Markdown解析器视为一段

请比较：

```
### 这是文章标题（下面还要有一行空行)

这是本段第一句，
这是本段第二句。
```

和

```
### 这是文章标题（下面还要有一行空行)

这是本段唯一一句话。

请注意这是另一段。
```

----

CNRV编辑部

----

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/3.0/cn/"><img alt="知识共享许可协议" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/3.0/cn/80x15.png" /></a><br />本作品采用<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/3.0/cn/">知识共享署名-非商业性使用-相同方式共享 3.0 中国大陆许可协议</a>进行许可。

