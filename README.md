# 计算机科学与编程第一次作业
## 学号：2100012443 姓名：骆媛媛  
## 题目一
中国的有十四个省份分为两派，其中一派涌现出恐怖分子，而另一派则均为反恐精英，各个省份的恐怖分子或反恐精英的数量是随机生成的，7个恐怖分子阵营的省份会进攻7个反恐精英的省份（一一对应）。使用流向来表示进攻关系,从恐怖分子阵营流向反恐精英阵营。
[链接](https://sjanhk.github.io/chinamap.html)  

全世界八个国家发生动乱，其中四个国家被恐怖分子占领（随机），另外四个国家联手派出反恐精英，各个国家的恐怖分子或反恐精英的数量是随机生成的，以世界地图为基础，展示各个国家的恐怖分子或反恐精英数量。
[链接](https://sjanhk.github.io/counter_strike.html)
## 题目二
有两个商家销售各品种手机，其在某月的销售量使用柱形图和折线图利用tab选项卡组合呈现
[链接](https://sjanhk.github.io/tab_chart.html)
## 题目三
统计了《三体》中名词词性出现最多的前五百个词的词频（排除了一个字的、“作者”、“刘慈欣”等无用名词），并做成词云,字体大小按出现的的次数从大到小排列。
[链接](https://sjanhk.github.io/santi_wordcloud.html)  
# 计算机科学与编程入门课程第二次作业  
## 学号：2100012443 姓名：骆媛媛  
## 课堂练习  
一个简单的HTML页面示例，包含一个输入框、按钮和一些介绍文字。这个页面包含了一个输入框和一个按钮，用户在输入框中输入关键词并点击按钮时，会触发搜索功能。  
搜索功能只是简单地显示了一些预定义的搜索结果，可以根据实际情况替换成真实的搜索功能。  
[课堂练习链接](https://sjanhk.github.io/search_engine.html)  
## 课后习题  
绘制《三体》1-3的人物共现，网页设计时增加放大缩小按钮及文字描述
大概流程：  
绘制人物关系网络图，首先需要有网络节点数据

name 人物名称
desc 人物简介
stage 人物出现在三体小说的哪个阶段  

将节点数据依次在三体小说文本中按行进行检索，如果每行同时出现两个人物，两个人物会构建一个边。人物关系网络图可以用gephi软件进行绘制， 绘制需要两个csv文件，即

三体_nodes.csv
三体_edges.csv  
最后使用pyechart库实现不错的可视化效果。  
[课后习题链接](https://sjanhk.github.io/santi.html)  
备注：我在本地查看santi.html文件时并没有问题，但上传到github后出现404报错，查询github page规则并没有能够debug，麻烦老师能将文件下载到本地查看我的作业  
若无法下载到本地查看，此处是未经过网页设计的初版作业[课后习题初版](https://sjanhk.github.io/三体_graph.html)

