*
Title: 文档标题

Description: 文档概要描述

Author: 作者

Date: 创建时间

*

#目录

[文档结构](#a1)

[格式段](#a2)

[修订日志](#a3)


<div id="a1"></div>


#一级标题

xxxx

##二级标题

xxxxxxx

###三级标题

1.xxxx

2.xxxxxx

3.xxxxxxxxxxx


****

<div id="a2"></div>

**链接**

可以这样声明一个URL链接：[百度](http://www.baidu.com "悬停提示")

也可以声明一个文档内的链接：[格式段](#a2)

**列表**

- 列表项1

- 列表项2

**区块**

    参数1：xxxx
	参数2：xxxxx
	参数3：xxxxxx

**代码段**
```xml
<xml name="sample">
	<param name="param1" value="aaa" />
	<list name="list1" >
	    <item name="item1" value="bbb" />
    </list>
</xml>
```

```java
public class HelloWorld{ 

public static void main(String[] args) {
    System.out.println("Hello World!");
    }
}
```

**纯文本段**

如果文本中有"_"或者类似< tag>这样的内容，markdown会进行格式化转义，显示效果会混乱。如果希望符号都按照原有的样子显示，在文本段前后加上`，可以指定原样输出：

`xxx_<dev>_<tag>`

**图片**

方式1：
![Alt text](http://pic.baike.soso.com/p/20131203/20131203160644-1827129775.jpg)

方式2（可以指定图片高度）：
<img height="50" alt="Alt text" src="http://pic.baike.soso.com/p/20131203/20131203160644-1827129775.jpg"/>

****

<div id="a3"></div>

#修订日志

**2015.3.1**

- 添加说明
- 修正错误

**2015.2.1**

- 初稿



