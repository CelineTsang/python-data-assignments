DianPing Dataset
====

Data Source
----

This dataset contains some most popular restaruants in HongKong on DianPing.com 
website starting page:http://www.dianping.com/hongkong/food

Data fields
----

`names` - String. e.g. 魔厨

`tags` - String. e.g. 标签：中餐

`address&tel` - String&Int. e.g.地址：铜锣湾登龙街1-29号金朝阳中心2期midtown25楼 +852-23410999

`average` - Int. e.g. ¥200

`features` - String. e.g.特色：黑豚叉烧 锅贴大虾多士

Data Volume
----
130 rows × 5 columns

Obstacles and solution
----
1.我尝试了使用beautifulsoup和selenium两种不同的方法，但我个人感觉后者更加的便捷（针对大众点评这一类时刻更新数据的网站来说）。

2.爬取出的数据不能有序分组显示（已解决）。

future work
----
1.与openrice上人气商家进行比对（观察香港本土软件的推荐与内地推荐的餐厅之间的偏差/菜系以及消费等，本地人与游客会有不一样吗？）

2.希望能够优化代码，以节省爬取数据的时间。

License
----
CC 4.0

Bonus: Enrich your dataset
----
1.API（Application Programming Interface,应用程序编程接口）是一些预先定义的函数，目的是提供应用程序与开发人员基于某软件或硬件得以访问一组例程的能力，而又无需访问源码，或理解内部工作机制的细节。（from 百度百科）

2.丰富数据集的方法：
（1）考虑增添中国其他城市的热门餐厅，集中比对消费偏好与消费水平。

（2）拓展类目，除了热门餐厅再添加其他的内容，例如景点或是热门消费场所。

    在http://www.dianping.com 内还有许多值得考虑的数据可进行爬取。

