---
title: 第一个md
date: 2019-09-21
tags:
 - holle word
categories: 
 - test
---


# 我的学习记录11111
## 学习一
[印象网站](https://yinxiang.com/new/hc/articles/%e5%8d%b0%e8%b1%a1%e7%ac%94%e8%ae%b0-markdown-%e5%85%a5%e9%97%a8%e6%8c%87%e5%8d%97/?utm_source=b1&utm_medium=b1&utm_term=sgls4)

![RUNOOB 图标](https://ss0.bdstatic.com/94oJfD_bAAcT8t7mm9GUKT-xh_/timg?image&quality=100&size=b4000_4000&sec=1587102212&di=811d7c42d1f07670c2379812c2844796&src=http://bbs.jooyoo.net/attachment/Mon_0905/24_65548_2835f8eaa933ff6.jpg "网图")


<p style="color:red">分割线</p>

<p style="color:red">***</p>

<m style="color:red">***</m>

~~张三李四王武~~

<d style="color:red">~~张三李四王武~~</d>

创建脚注格式类似这样 [^TTT]。

[^TTT]: 菜鸟教程 -- 学的不仅是技术，更是梦想！！！

生成一个脚注1[^3]

[^3]: 这里是 **脚注** 的 *内容*.

生成一个脚注2[^foot]

[^foot]: 这里是**脚注2**的*内容*.

这是一个脚注的例子[^1]

[^1]: 脚注5测试

***
* * *

*****

- - -

----------

| 序号 | 姓名 | 班级 | 年龄 | 爱好 |
| --- | --- | --- | --- | --- |
| 1 | 张三 | 三班 | 3 | 学习 |
| 2 | 张三 | 三班 | 3 | 学习 |

```chart
,Budget,Income,Expenses,Debt
June,5000,8000,4000,6000
July,3000,1000,4000,3000
Aug,5000,7000,6000,3000
Sep,7000,2000,3000,1000
Oct,6000,5000,4000,2000
Nov,4000,3000,5000,

type: pie
title: Monthly Revenue
x.title: Amount
y.title: Month
y.suffix: $
```
``

## 学习二
`教师的行风建设`
```math
e^{i\pi} + 1 = 0
```
```mermaid
graph TD
A[模块A] -->|A1| B(模块B)
B --> C{判断条件C}
C -->|条件C1| D[模块D]
C -->|条件C2| E[模块E]
C -->|条件C3| F[模块F]
```
```mermaid
sequenceDiagram
A->>B: 是否已收到消息？
B-->>A: 已收到消息
```
```mermaid
gantt
title 甘特图
dateFormat  YYYY-MM-DD
section 项目A
任务1           :a1, 2018-06-06, 30d
任务2     :after a1  , 20d
section 项目B
任务3      :2018-06-12  , 12d
任务4      : 24d
```

```mermaid
        gantt
        dateFormat  YYYY-MM-DD
        title 软件开发甘特图
        section 设计
        需求                      :done,    des1, 2014-01-06,2014-01-08
        原型                      :active,  des2, 2014-01-09, 3d
        UI设计                     :         des3, after des2, 5d
    未来任务                     :         des4, after des3, 5d
        section 开发
        学习准备理解需求                      :crit, done, 2014-01-06,24h
        设计框架                             :crit, done, after des2, 2d
        开发                                 :crit, active, 3d
        未来任务                              :crit, 5d
        耍                                   :2d
        section 测试
        功能测试                              :active, a1, after des3, 3d
        压力测试                               :after a1  , 20h
        测试报告                               : 48h
```

## 学习三
```java
public void trset(){
    sout
}
```
```html
<body>
    <div>
        123131231
    </div>
</body>
```