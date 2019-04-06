# <b>Markdown-Tutorial</b>
- [<b>Markdown-Tutorial</b>](#bmarkdown-tutorialb)
    - [<b>1.标题</b>](#b1标题b)
    - [<b>2.分级标题</b>](#b2分级标题b)
    - [<b>3.TOC</b>](#b3tocb)
    - [<b>4.引用</b>](#b4引用b)
        - [<b>(1)单行</b>](#b1单行b)
        - [<b>(2)多行</b>](#b2多行b)
        - [<b>(3)嵌套</b>](#b3嵌套b)
    - [<b>5.行内标记</b>](#b5行内标记b)
    - [<b>6.代码块</b>](#b6代码块b)
        - [<b>(1)```</b>](#b1b)
        - [<b>(2)Tab</b>](#b2tabb)
        - [<b>(3)自定义语法</b>](#b3自定义语法b)
## <b>1.标题</b>
注：#后面保持空格<br/>
[代码]<br/>
```
# h1
## h2
### h3
#### h4
##### h5
###### h6
####### h7      //不再是标题
```
[演示]<br/>
# h1
## h2
### h3
#### h4
##### h5
###### h6
####### h7      //不再是标题

## <b>2.分级标题</b>
注：=-最少可以只写一个，兼容性一般<br/>
[代码]<br/>
```
一级标题
=======
二级标题
-------
```
[演示]<br/>

一级标题
=======
二级标题
-------

## <b>3.TOC</b>
注：根据标题生成目录，兼容性一般<br/>
[代码]<br/>
```
[TOC]
```
需要安装插件<br/>
[演示]<br/>
见开头<br/>

## <b>4.引用</b>
### <b>(1)单行</b>
```
> hello world!
```
演示<br/>
> hello world!
### <b>(2)多行</b>
```
> hello world!<br/>
hello world!<br/>
hello world!<br/>
```
或<br/>
```
> hello world!<br/>
> hello world!<br/>
> hello world!<br/>
```
[演示]<br/>
> hello world<br/>
hello world<br/>
hello world<br/>
### <b>(3)嵌套</b>
> aaa
>> bbb
>>> ccc

## <b>5.行内标记</b>
注：用`标记代码块变成一行<br/>
[代码]<br/>
```
标记之外`
for(i = 0 ;i < n; i++)
    printf("hello world");
`标记之外
```
[演示]<br/>
标记之外`
for(i = 0 ;i < n; i++)
    printf("hello world");
`标记之外

## <b>6.代码块</b>
注：与上一行距离一空行<br/>
### <b>(1)```</b>
[代码]<br/>
````
```
<div>
    <div></div>
    <div></div>
    <div></div>
</div>
```
````
[演示]<br/>
```
<div>
    <div></div>
    <div></div>
    <div></div>
</div>
```
### <b>(2)Tab</b>
[代码]<br/>
```
    <div>
        <div></div>
        <div></div>
        <div></div>
    </div>
```
[演示]<br/>

    <div>
        <div></div>
        <div></div>
        <div></div>
    </div>

### <b>(3)自定义语法</b>
[代码]<br/>
````
```C
#include <stdio.h>
int main()
{
    return 0;
}
```
````
[演示]<br/>
```C
#include <stdio.h>
int main()
{
    return 0;
}
```
