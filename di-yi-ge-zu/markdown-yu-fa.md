# Markdown语法

  大家在网络上写文章如果喜欢跨平台转载，那么用Markdown格式来写是一个非常好的选择，本文是对Markdown常用的格式的介绍。

* 标题
* 文字样式
* 引用
* 分割线
* 无序列表
* 代码块
* 图片
* 超链接
* 添加空格
* 表格
* 跳转

```java
public static
```

* 我的
* 我的
  * 无品牌的
    * 圣诞快乐发我我

![&#x73A9;&#x513F; &#x58EB;&#x5927;&#x592B;s&apos;d&#x6CD5;](../.gitbook/assets/image%20%281%29.png)



### 标题

'\#'是标题，一共6级，可以和其他样式混用

```text
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题
```

效果：

![20200731155141](https://cdn.jsdelivr.net/gh/leiyu1997/ImageHostingService@master/resources/blogs/20200731155141.png)

### 文字样式

```text
**文字加粗**

*文字倾斜*

***加粗&倾斜***

~~加删除线~~
```

效果：

**文字加粗**

_文字倾斜_

_**加粗&倾斜**_

~~加删除线~~

### 引用

```text
> 引用
> > 引用
> > > > >多级引用
```

效果：

> 引用
>
> > 引用
> >
> > > > > 多级引用

### 分割线

以下两种都可以

```text
***
---
```

效果：

### 无序列表

以下三种都可以，注意加空格

```text
* 无序列表
- 无序列表
+ 无序列表
```

效果：

* 无序列表
* 无序列表
* 无序列表

### 代码块

单行代码用“\`”,多行代码用“\`\`\`”

* 单行代码例子：

  ```text
    `单行代码`
  ```

  效果：

`单行代码`

* 多行代码例子：

  ![20200714170646](https://cdn.jsdelivr.net/gh/leiyu1997/ImageHostingService@master/resources/blogs/20200714170646.png)

效果：

```text
public static void main(String[] args) {
    system.out.println("Hello World!");
}
```

### 图片

```text
格式：![图片名](图片URL)

例子：
![你的名字](https://upload-images.jianshu.io/upload_images/22982124-07d686a87602657d.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
```

效果： ![&#x4F60;&#x7684;&#x540D;&#x5B57;](https://upload-images.jianshu.io/upload_images/22982124-07d686a87602657d.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

### 超链接

```text
格式：[链接名](链接URL)

例子：
[**百度**](http://www.baidu.com)
[*百度*](http://www.baidu.com)
[***百度***](http://www.baidu.com)
[~~百度~~](http://www.baidu.com)
```

效果：

[**百度**](http://www.baidu.com)

[_百度_](http://www.baidu.com)

[_**百度**_](http://www.baidu.com)

[~~百度~~](http://www.baidu.com)

### 添加空格

```text
半方大的空白&ensp;或&#8194;
全方大的空白&emsp;或&#8195;
不断行的空白&nbsp;或&#160;

例子：
&ensp;半方大的空白
&emsp;全方大的空白
&nbsp;不断行的空白
```

效果：

 半方大的空白

 全方大的空白

 不断行的空白

### 表格

```text
|表格以竖线划分|第一行是标题|~~可以加效果~~|
|:--|:-:|--:|
|第二行是格式|以-:设置对齐格式|总共不少于三个|
|左对齐|中间对齐|右对齐|
```

效果：

| 表格以竖线划分 | 第一行是标题 | ~~可以加效果~~ |
| :--- | :---: | ---: |
| 第二行是格式 | 以-:设置对齐格式 | 总共不少于三个 |
| 左对齐 | 中间对齐 | 右对齐 |

### 跳转

1. 同文件跳转

```text
[Markdown语法](#test) //目录位置

test>Markdown语法 //要跳转到的位置
```

效果：

Markdown语法

1. 不同文件跳转

采用相对路径来实现

```text
[Windows指令](./Windows教程/Windows指令.md)
```

