---
title: 关于markdown的语法
date: 2025-08-20 22:24:35
tags:
---
# 关于标题
#的数量决定是几级标题
{% codeblock %}
# 一级标题
## 二级标题
### 三级标题
{% endcodeblock %}
用html里的h1,h2,h3也有同样的效果
{% codeblock %}
<h1>一级标题</h1>
<h2>二级标题</h2>
<h3>三级标题</h3>
{% endcodeblock %}
<!-- more -->
# 关于文本格式
你可以在markdown里使用加粗，斜体和删除线
{% codeblock %}
**这是加粗**
*这是斜体*
~~这是删除线~~
{% endcodeblock %}
效果如下:
**这是加粗**
*这是斜体*
~~这是删除线~~
# 列表
markdown里的两种列表
## 无序列表
无序列表用-即可
{% codeblock %}
- project1
- project2
- project3
{% endcodeblock %}
效果如下:
- project1
- project2
- project3
## 有序列表
有序列表用数字+.
{% codeblock %}
1. project1
2. project2
3. project3
{% endcodeblock %}
效果如下:
1. project1
2. project2
3. project3
# 链接与图片
{% codeblock %}
[链接文字](https://duckduckgo.com)
![图片描述]{tall_white_fountain.jpg}
{% endcodeblock %}
效果如下:
这是来自pixiv的画师[airfish空气鱼](https://www.pixiv.net/en/users/67512705)的作品
{% asset_img tall_white_fountain.jpg %}
# 引用文字
{% codeblock %}
> 这是一个引用
>> 这是一个嵌套引用
{% endcodeblock %}
效果如下:
> 这是一个引用
>> 这是一个嵌套引用
# 代码引用
\```
print("hello world")
\```
效果如下:
{% codeblock %}
print("hello world")
{% endcodeblock %}
# 表格
{% codeblock %}
| 姓名 | 年龄 | 城市 |
|------|------|------|
| 张三 |  25  | 北京 |
| 李四 |  30  | 上海 |
{% endcodeblock %}
效果如下:
| 姓名 | 年龄 | 城市 |
|------|------|------|
| 张三 |  25  | 北京 |
| 李四 |  30  | 上海 |
# 分割线
{% codeblock %}
---
{% endcodeblock %}
效果如下:
---
# 任务清单
{% codeblock %}
- [x] 已完成
- [ ] 未完成
{% endcodeblock %}
效果如下:
- [x] 已完成
- [ ] 未完成
# 结语
这便是较为常用的markdown语法，初次写blog真的写了很久，期间也遇到不少问题，不过能写完感觉还是不错的:p
