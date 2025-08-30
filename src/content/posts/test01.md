---
title: 这是一个测试文章
published: 2025-08-28
pinned: false
description: A simple test.
tags: [Markdown, Blogging]
category: Demo
draft: false
---

Hello,欢迎来到Obsidian的世界.

这是一个示例文档~

这是你的新仓库。

写点笔记，[[创建链接]]，或者试一试[导入器](https://help.obsidian.md/Plugins/Importer)插件!
当你准备好了，就将该笔记文件删除，使这个仓库为你所用。

**Obsidian**是一款优秀的知识<font color=red>管理软件</font>


## 示例
这是一个C语言示例.
```c
#include<stdio.h>
int main(void){
	printf("Hello, World!\n");
	return 0;
}
```

## [[插件评级]]

# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题

## 图片演示
![碧蓝之海](/../src/assets/anime/blzh.webp)

## 表格演示
例:

```c
struct Data
{
  char a;
  short b;
  int c;
  char d;
  short e;
}
//sizeof(Data) = 12
```

内存结构如下:

|  a  |     |  b  |  b  |
| :-: | :-: | :-: | :-: |
|  c  |  c  |  c  |  c  |
|  d  |     |  e  |  e  |

## 注脚演示
注脚演示1[^1]

注脚演示2[^2]

## 支持的markdown扩展语法

### 嵌入github仓库卡片
```markdown
::github{repo="用户名/仓库名"}
```
::github{repo="ZhipingHuang/Blog-BlueArchive"}

### 注意框
使用 `> [!NOTE]、> [!TIP]、> [!WARNING]`等语法创建美观的注意框
> [!NOTE]
> 这是一个注意框~

> [!TIP]
> 这是一个Tips

> [!WARNING]
> 这是一个提醒

### 链接其它文章
<ul>
  <li><a href="/posts/markdown-tutorial/">Markdown指南</a></li>
  <li><a href="/posts/video/">页面中插入视频教程</a></li>
  <li><a href="/posts/guide/">Blog模板</a></li>
</ul>

### 插入视频演示
<iframe width="100%" height="468" src="//player.bilibili.com/player.html?isOutside=true&aid=1453536774&bvid=BV1gi421m7df&cid=1519880345&p=1&autoplay=0" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"></iframe>

### LaTex公式
使用`$inline$`和`$$block$$`语法编写LaTeX数学公式

行内公式: $ E = mc^2 $

块级公式: 
$$ 
  y = 3x^2 + 4x + 5 
$$

[^1]: Hello,这是1第一个注脚演示.
[^2]: Hi,又见面了,这是第2个注脚演示.
