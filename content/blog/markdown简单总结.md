---
title: markdown简单总结
date: 2025-02-04T00:28:03.272Z
---


# 目录
## 1.Markdown标题
## 2.Markdown段落格式
## 3.Markdown列表
## 4.Markdown区块
## 5.Markdown代码
## 6.Markdown链接
## 7.Markdown图片
## 8.Markdown表格
## 9.Markdown高级技巧


# 基础教程介绍
### markdown为什么这么欢迎

1. 可导出成多种文档：Markdown 编写的文档可以导出 HTML 、Word、图像、PDF、Epub 等多种格式的文档。
2. 应用广泛：当前许多网站都广泛使用 Markdown 来撰写帮助文档或是用于论坛上发表消息。例如：GitHub、简书、reddit、Diaspora、Stack Exchange、OpenStreetMap 、SourceForge等
3. 可以在线编辑以及结合思维导图：
如果你需要将 markdown 转为 PDF、图片、HTML 等格式也可以安装对应的插件来实现。
你也可以使用我们的在线编辑器来测试：https://www.jyshare.com/front-end/712。
MarkDown 思维导图工具：https://www.jyshare.com/front-end/9692/。



### 使用工具：
VScode 安装教程：https://www.runoob.com/w3cnote/vscode-tutorial.html
VScode 官网地址：https://code.visualstudio.com/


### vscode中预览功能
VSCode 实时预览还需要执行 Markdown: Open Preview to the Side 命令来实现。

在命令窗口输入 Markdown: Open Preview to the Side 命令：
![image.png](https://github.com/lovzjoyy/tinymind-blog/blob/main/assets/images/2025-02-04/1738627641770.png?raw=true)

最终结果：
![image.png](https://github.com/lovzjoyy/tinymind-blog/blob/main/assets/images/2025-02-04/1738627673540.png?raw=true)

### 如何结合插件进行导出
#### 测试实例：
1. 点击扩展，查找，点击安装
![image.png](https://github.com/lovzjoyy/tinymind-blog/blob/main/assets/images/2025-02-04/1738627997191.png?raw=true)
2.新建md文件代码
输入以下代码块：
【code】

右键以插件打开，
![image.png](https://github.com/lovzjoyy/tinymind-blog/blob/main/assets/images/2025-02-04/1738628181711.png?raw=true)
会看到这样的界面
![image.png](https://github.com/lovzjoyy/tinymind-blog/blob/main/assets/images/2025-02-04/1738628304899.png?raw=true)

然后，在预览框中右击鼠标还提供了各种导出功能：我们点击右键可以一键导出



# 1.Markdown标题
Markdown 标题有两种格式。
1. 使用 = 和 - 标记一级和二级标题
```
我展示的是一级标题
=================

我展示的是二级标题
-----------------

```
2. 使用 # 号标记
```
使用 # 号可表示 1-6 级标题，一级标题对应一个 # 号，二级标题对应两个 # 号，以此类推。
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题
```

# 2.Markdown段落格式
1. 基础换行段落
2. 字体
```
*斜体文本*
_斜体文本_
**粗体文本**
__粗体文本_
***粗斜体文本***
___粗斜体文本___
```
![image.png](https://github.com/lovzjoyy/tinymind-blog/blob/main/assets/images/2025-02-04/1738631947578.png?raw=true)
3. 分隔线
你可以在一行中用三个以上的星号、减号、底线来建立一个分隔线，行内不能有其他东西。你也可以在星号或是减号中间插入空格。下面每种写法都可以建立分隔线：
```
***

* * *

*****

- - -

----------
```
4.删除线
如果段落上的文字要添加删除线，只需要在文字的两端加上两个波浪线 ~~ 即可
```
RUNOOB.COM
GOOGLE.COM
~~BAIDU.COM~~
```
![image.png](https://github.com/lovzjoyy/tinymind-blog/blob/main/assets/images/2025-02-04/1738632114375.png?raw=true)
5.下划线
下划线可以通过 HTML 的 <u> 标签来实现
![image.png](https://github.com/lovzjoyy/tinymind-blog/blob/main/assets/images/2025-02-04/1738632222916.png?raw=true)
6. 脚注
脚注是对文本的补充说明。

Markdown 脚注的格式如下:
```
[^要注明的文本]
```

实际演示脚注的用法
```
[^要注明的文本]
创建脚注格式类似这样 [^RUNOOB]。

[^RUNOOB]:  zjoy 学的不仅是技术，更是梦想！！！
```
![image.png](https://github.com/lovzjoyy/tinymind-blog/blob/main/assets/images/2025-02-04/1738632494782.png?raw=true)


# Markdown列表
Markdown 支持有序列表和无序列表。

1. 无序列表使用星号(*)、加号(+)或是减号(-)作为列表标记，这些标记后面要添加一个空格，然后再填写内容：
```
* 第一项
* 第二项
* 第三项

+ 第一项
+ 第二项
+ 第三项


- 第一项
- 第二项
- 第三项
```
显示效果：
![image.png](https://github.com/lovzjoyy/tinymind-blog/blob/main/assets/images/2025-02-04/1738633062674.png?raw=true)
2.有序列表
有序列表使用数字并加上 . 号来表示，如：
```
1. 第一项
2. 第二项
3. 第三项
```
3.列表嵌套


显示效果：
```
1. 第一项
    - 第一个元素
      - 测试
    - 哈哈
2. 第二项
      - 第一个元素
3. 第三项
   1. 第一个元素

```
![image.png](https://github.com/lovzjoyy/tinymind-blog/blob/main/assets/images/2025-02-04/1738633314502.png?raw=true)




