# Markdown基本语法指南

---

教程视频：
<iframe src="//player.bilibili.com/player.html?isOutside=true&aid=327623069&bvid=BV1JA411h7Gw&cid=171385214&p=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"></iframe>

---

这是几种标题：
# 标题1
## 标题2
### 标题3
#### 标题4

---

<br><b>首先，Markdown是兼容Html语法的!</b>

---

一对星号表示*斜体*<br>
两对星号表示**粗体**<br>
一对反引号表示行内代码，比如`printf("Hello World"\n)`<br>
<u>下划线</u>需要使用Html语法<br>
表情符号是一对冒号加表情名称，比如 :smile:<br>
一对dollar符号表示行内公式，比如 $a^2 = \sqrt{b}$<br>
一对波浪号表示下标，比如 H~2~O<br>
一对脱字符表示商标，比如 Coca Cola^TM^<br>
两对等号表示高亮，比如 ==高亮字段==<br>

---

>这是一个引用：
《瓦尔登湖》是由美国作家梭罗在马萨诸塞州的瓦尔登湖湖畔写作的一部经典作品。

---

<br>这是一个有序列表：
1. 你好
2. 这是一份笔记
3. 记录了Markdown的相关知识
   1.这是一个子分支
---

<br>这是一个无序列表：
- 你好呀
- 你好！
- 你过得怎么样？
- 我很好，谢谢你！
* （使用星号也可以写无序列表）

---

<br>这是一个待办复选框：
- [ ] 买胡萝卜
- [ ] 买花菜
- [ ] 买咖喱
- [ ] 买无糖可乐
- [x] 中括号中间写一个x就可以把复选框变成打勾状态的了（当然也可以手动点击复选框）

---

<br>这是一个代码块：
```c
int main(void)
{
    printf("Hello World!"\n);

    reutrn 0;
}
```

---

这是一个数学公式：

$$
勾股定理： \sqrt{a^2+b^2} =\sqrt{c^2}
$$

---

这是一个表格：

冒号在哪边表示在哪边对齐，两边都有冒号表示居中。<b>注意表格的第二行不要省略，至少要有两个横杠！</b>

|学号|姓名|年龄|
|:--|--:|:--:|
|01|张三|18|
|02|李四|19|
|03|王五|20|

---

这是一个脚注用法：

2023年大中华区[^大中华区]营销总额为268亿元[^元]

[^大中华区]:通常指中国大陆、中国香港、中国澳门、中国台湾、新加坡等地区；
[^元]:单位为人民币。

---

这是引用链接的用法：

[Google](www.google.com "全球通用的搜索引擎")
[Baidu][id1],[百度][id1],[度娘][id1]

[id1]:www.baidu.com "中国访问量最大的搜索引擎"

点击此处[转到本文档开头](#markdown基本语法指南) 本方法可转到任一标题

---

这是一个URL：

www.google.com
或者写全：https://www.google.com

---

这是一个链接图片：

![Google](https://www.google.com/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png "Google's logo")

---

这是缩略的用法：

很久很久以前，有一个 HTML 文档……
*[HTML]: Hyper Text Markup Language
