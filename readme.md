# 中文文本多层分类数据集

这是[另一个数据集](https://github.com/fateleak/toutiao-text-classfication-dataset)的加强版，为多级分类，分类更全（含1000+多级分类），量更大。



数据来源：

今日头条客户端



文本多层分类的概念见下图

![](mlc.png)



数据格式：

```
6552431613437805063_!_102_!_news_entertainment_!_谢娜为李浩菲澄清网络谣言，之后她的两个行为给自己加分_!_佟丽娅,网络谣言,快乐大本营,李浩菲,谢娜,观众们
```

每行为一条数据，以`|,|`分割的各字段，从前往后分别是 新闻ID，分类代码，新闻字符串（仅含标题），新闻关键词，新闻label



所有分类的目录见 `all_cat.txt`



数据规模：

共2914000条，分布于1000+个多层的类别中。



采集时间：

2018年06月



为什么放出这个数据集：

因为爬数据真的是太无聊了！！！




加我微信：
![](http://fate2.oss-cn-shanghai.aliyuncs.com/weixin2.jpeg)

