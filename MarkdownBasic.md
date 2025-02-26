# Markdown 基本语法

## Heading 标题
# level 1
##  level 2
###  level 3
####  level 4
##### level 5
###### level 6
level 1
==
level2
--
## 段落
I reallu like using Markdown.

I think I'll use it to format all of my documents from now on.
## 换行
在一行的末尾添加两个或多个空格，然后按回车键,即可创建一个换行
This is the first line.  
And this is the second line
##  强调语法
**bold**
__bold__
love**is**bold
*cat is meow*
_cat is meow_
A*cat*meow
This text is ***really important***.
This text is ___really important___.
This text is __*really important*__.
This text is **_really important_**.
##  引用
> 您好

> Hello
> 
>> Bye

> #### The quarterly results look great!
>
> - Revenue was off the chart.
> - Profits were higher than ever.
>
>  *Everything* is going according to **plan**.
## 列表
1.
1.
1.
or

1.
2.
3.

-
-
-

*
*
*

+
+
+

- First
- Second
    - intend 1
    - intend 2
- Third

*  This is the first list item.
*  Here's the second list item.

    > A blockquote would look great below the second list item.

*   And here's the third list item.

1. Open the file
2. Find the following code block

        &lt;html>
            &lt;head>
                &lt;title>Test&lt;/title>

3.Update the title to match the name

1. First item
2. Second item
3. Third item
    - Indented item1
    - Indented item2
4. Forth item  

## 代码语法
At the command prompt, type `nano`.

At the command prompt, type <code>nano</code>.

``Use `code` in your Markdown file.``

<code>Use \`code\` in your Markdown file.</code>

要创建代码块，请将代码块的每一行缩进至少四个空格或一个制表符。

        &lt;html>
            &lt;head>
        &lt;title>Test&lt;/title>
## 分割线语法
Try to put

---

...and

Try to put

***

...and

Try to put

___

...and

## 链接语法
[超链接显示名](链接地址 "超链接title")
<a href="超链接地址" title="超链接title">超链接显示名</a>

这是一个链接 [Markdown语法](https://markdown.com.cn)

这是一个链接 <a href="https://markdown.com.cn" title="Hello">Markdown语法</a>

这是一个链接 [Markdown语法](https://markdown.com.cn "最好的markdown教程")。

尖括号把url或者email变成可点击链接

<https://markdown.com.cn>

<fake@example.com>

I love supporting the **[EFF](https://eff.org)**.

This is the *[Markdown Guide](https://www.markdownguide.org)*.

See the section on [`code`](#code).

[hobbit-hole][1]
[hobbit-hole] [2]
[hobbit-hole][2]
[hobbit-hole][3]
[hobbit-hole][4]
[hobbit-hole][5]
[hobbit-hole][6]
[hobbit-hole][7]


[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle
[2]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle "Hobbit lifestyles"
[3]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle 'Hobbit lifestyles'
[4]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle (Hobbit lifestyles)
[5]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> "Hobbit lifestyles"
[6]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> 'Hobbit lifestyles'
[7]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> (Hobbit lifestyles)

## 图片
![图片alt](图片链接 "图片title")
<img src="图片链接" alt="图片alt" title="图片title">

![这是图片](https://markdown.com.cn/assets/img/philly-magic-garden.9c0b4415.jpg "Magic Gardens")

给图片增加链接

[![沙漠中的岩石图片](https://markdown.com.cn/assets/img/shiprock.c3b9a023.jpg "Shiprock")](https://markdown.com.cn)

## 区块标签
区块元素`<div>`、` <table>` 、`<pre>`、 `<p>`，必须在前后行加上空行，而且这些元素的开始和结尾标签，不可以用tab或是空白来缩进。

This is a regular paragraph.

<table>
    <tr>
        <td>Foo</td>
        <td>Hell</td>
    </tr>
</table>

## 特殊字符转义
`<`和`&`

`&lt;`和`&amp;`

&copy;

AT&T

AT&amp;T

## 表格
(---)创建每列的标题，并使用|分割每列

|Syntax|Description|
|---|-----------|
|Header|Title|
|Paragraph|Text|

对齐

左侧（:---）
右侧（---:）
居中（:---:）

|Syntax|Description|Test Text|
|:---|:---:|---:|
|Paragraph|Title|Here's this|
|Header|Text|And|
|`code`|[Hello](https://markdown.com.cn/extended-syntax/tables.html)|**_ok_**|
|&#124;|&#124;|&#124;|

可以添加（`code`）与链接

## 围栏代码块
```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```


```json
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

## 脚注

Here's a simple footnote,[^1] and here's a longer one.[^bignote]

[^1]: This is the first footnote.

[^bignote]: Here's one with multiple paragraphs and code.

    Indent paragraphs to include them in the footnote.

    `{ my code }`

    Add as many paragraphs as you like.