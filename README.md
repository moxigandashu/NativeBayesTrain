# NativeBayesTrain

## 1说明
### 目标：训练朴素贝叶斯分类器模型，来实现对新闻的分类
### 主要步骤：
1. **爬虫爬去数据**：包括爬去文本，并打上新闻分类的标签
2. **分词**：将文本分词
3. **转换成词向量**
4. **训练朴素贝叶斯模型**
5. **分类和预测**

## 2环境说明
1. Python3.6
2. 包：
- urlib 请求网页爬取网页
- BeautifulSoup 对网页解析提取文本
- pandas:数据处理，
- jieba：用于分词
![introdution](https://raw.githubusercontent.com/moxigandashu/NativeBayesTrain/master/%E6%9C%B4%E7%B4%A0%E8%B4%9D%E5%8F%B6%E6%96%AF%E5%AF%B9%E5%86%85%E5%AE%B9%E7%9A%84%E8%AF%84%E4%BC%B0.png)

## 文件说明
1. class_craw.py:爬虫
2. bayes.py:分词，转化词向量，训练贝叶斯模型
3. stop_words_tw.txt:停用词表
4. class_feeds_data.csv：示例数据，爬去的带标签的新闻

