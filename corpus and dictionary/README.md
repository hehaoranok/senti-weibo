# 词典与数据集
## 测试集

选取了 COAE2014(Chinese Opinion Analysis Evaluation) 的 positive 和 negative 数据集作为测试集，由于无法找到已经标准好的 7000 篇样本，所以我们只能将能找到的，已经标注好的关于 `蒙牛` 话题的 2172 条微博（7000样本的子集）作为测试集，整理生成 [coae2014.csv](coae2014.csv) 。

[coae2014.csv](coae2014.csv) 中，一共有 2172 条微博，其中有 1168 条 情感消极的微博，992 条情感积极的微博，12 条中性的微博。csv 文件中的 `seged_weibo` 字段为经过清洗并分词后的微博，可以直接用来进行分类或训练。

## 词典

* 特殊字符集
* emoji
* NTUSD 情感词典

## 数据集资源

[github-weibo2018](<https://github.com/dengxiuqi/weibo2018>) 1W条中文微博语料库/情感极性标注