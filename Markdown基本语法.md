# Markdown基本语法

## 目录

- [段落格式](#段落格式)
- [列表](#列表)
- [区块](#区块)
- [代码](#代码)
- [链接](#链接)
- [图片](#图片)
- [表格](#表格)
- [高级技巧](#高级技巧)

## 段落格式

两个空格加回车  
可实现换行

也可以在段落后使用一个空行来表示重新开始一个段落


---
👆这个是分割线

_斜体文本_  
__粗体文本__  
___粗斜体文本___  
~~删除线~~  
<u>下划线</u>

脚注  
脚注是对文本的补充说明。  
创建脚注格式类似这样 [^脚注]。

[^脚注]: Hello World!

## 列表

- 无序列表
- 无序列表
- 无序列表

1. 有序列表
2. 有序列表
3. 有序列表

列表嵌套
1. 第一级
    - 第二级
        - 第三级

## 区块

> 区块引用  
> 区块引用  
> 区块引用
---
> 第一级
>> 第二级
>>> 第三级
---
- 第一项(列表中使用区块)
    > Hello World!  
    > Hello World!
- 第一项(列表中使用区块)
---
> 区块中使用列表
> 1. 第一项
> 2. 第二项
> - 第一项
> - 第二项

## 代码

`Console.ReadLine()`函数  

可以用 ``` 包裹一段代码，并指定一种语言（也可以不指定）：
```Javascript
$(document).ready(function () {
    alert('Hello World!');
});
```
```C#
public vido printText(){
    Console.WriteLine("Hello World!");
}
```

## 链接

[链接名称](https://docs.microsoft.com/zh-cn/) 

or

<https://docs.microsoft.com/zh-cn/>

高级链接
链接也可以用变量来代替，文档末尾附带变量地址：  
这个链接用 a 作为网址变量 [Google][a]  
这个链接用 GitHub 作为网址变量 [GitHub][GitHub]  
然后在文档的结尾为变量赋值（网址）

  [a]: http://www.google.com/
  [GitHub]: https://github.com/

## 图片

图片语法:
```
![alt 属性文本](图片地址)
![alt 属性文本](图片地址 "鼠标悬置于图片上会出现的标题文字，可不写")
```

![GitHub图标](https://github.com/LDDZ/Notes/blob/master/Images/GitHub.png "这是GitHub图标")

Markdown 还没有办法指定图片的高度与宽度，如果你需要的话，你可以使用普通的 `<img>` 标签。  
<img src="https://github.com/LDDZ/Notes/blob/master/Images/GitHub.png" width="20%">

## 表格

| 表头 | 表头 |
| ---- | ---- |
| 单元格 | 单元格 |
| 单元格 | 单元格 |

| 左对齐 | 右对齐 | 居中对齐 |
| :-----| ----: | :----: |
| 这是一个单元格 | 这是一个单元格 | 这是一个单元格 |
| 这是一个单元格 | 这是一个单元格 | 这是一个单元格 |

## 高级技巧

反斜杠转义特殊字符：  
_斜体文本_  
\_正常显示底线_  

目前支持的 HTML 元素有：`<kbd> <b> <i> <em> <sup> <sub> <br>`等 ，如：  
使用<kbd>Ctrl</kbd>+<kbd>C</kbd>复制选中文本

<b>加粗文字</b>  
<i>斜体</i>  
<em>强调内容</em>  
这是<sup>上标文本</sup>。  
这是<sub>下标文本</sub>。

可用`<br>`来换行<br>喔

__[🚀回到顶部](#Markdown基本语法)__
