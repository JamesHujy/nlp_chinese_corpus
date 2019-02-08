# nlp chinese corpus

all kinds of Chinese Corpus for NLP 极大量中文自然语言处理语料

## 1.维基百科-中文简体-json版

#### 104万个词条(1,043,224条; 压缩文件519M；数据更新时间：2019.2.7)

<a href="https://pan.baidu.com/s/1uPMlIY3vhusdnhAge318TA">维基百科-中文简体-json版【下载】</a>

可能的用途：可以做为通用中文语料，做预训练的语料或构建词向量，也可以用于构建知识问答。

结构：

{"id":<id>,"url":<url>,"title":<title>,"text":<text>} 其中，title是词条的标题，text是正文；通过"\n\n"换行。

例子：

    {"id": "53", "url": "https://zh.wikipedia.org/wiki?curid=53", "title": "经济学", "text": "经济学\n\n经济学是一门对产品和服务的生产、分配以及消费进行研究的社会科学。西方语言中的“经济学”一词源于古希腊的。\n\n经济学注重的是研究经济行为者在一个经济体系下的行为，以及他们彼此之间的互动。在现代，经济学的教材通常将这门领域的研究分为总体经济学和个体经济学。微观经济学检视一个社会里基本层次的行为，包括个体的行为者（例如个人、公司、买家或卖家）以及与市场的互动。而宏观经济学则分析整个经济体和其议题，包括失业、通货膨胀、经济成长、财政和货币政策等。..."}

效果：

    经济学
    经济学是一门对产品和服务的生产、分配以及消费进行研究的社会科学。西方语言中的“经济学”一词源于古希腊的。
    经济学注重的是研究经济行为者在一个经济体系下的行为，以及他们彼此之间的互动。在现代，经济学的教材通常将这门领域的研究分为总体经济学和个体经济学。微观经济学检视一个社会里基本层次的行为，包括个体的行为者（例如个人、公司、买家或卖家）以及与市场的互动。而宏观经济学则分析整个经济体和其议题，包括失业、通货膨胀、经济成长、财政和货币政策等。
    其他的对照还包括了实证经济学（研究「是什么」）以及规范经济学（研究「应该是什么」）、经济理论与实用经济学、行为经济学与理性选择经济学、主流经济学（研究理性-个体-均衡等）与非主流经济学（研究体制-历史-社会结构等）。
    经济学的分析也被用在其他各种领域上，主要领域包括了商业、金融、和政府等，但同时也包括了如健康、犯罪、教育、法律、政治、社会架构、宗教、战争、和科学等等。到了21世纪初，经济学在社会科学领域各方面不断扩张影响力，使得有些学者讽刺地称其为「经济学帝国主义」。
    在现代对于经济学的定义有数种说法，其中有许多说法因为发展自不同的领域或理论而有截然不同的定义，苏格兰哲学家和经济学家亚当·斯密在1776年将政治经济学定义为「国民财富的性质和原因的研究」，他说：
    让-巴蒂斯特·赛伊在1803年将经济学从公共政策里独立出来，并定义其为对于财富之生产、分配、和消费的学问。另一方面，托马斯·卡莱尔则讽刺的称经济学为「忧郁的科学」（Dismal science），不过这一词最早是由马尔萨斯在1798年提出。约翰·斯图尔特·密尔在1844年提出了一个以社会科学定义经济学的角度：
    .....

<img src="https://github.com/brightmart/nlp_chinese_corpus/blob/master/resources/wiki_zh.jpg"  width="90%" height="90%" />



add your chinese corpus here by sending us an email  to brightmart@hotmail.com


## 2.百科类问答-json版

#### 150万个问答( 压缩文件663M；数据更新时间：2018年)

##### 数据描述

含有150万个问题和答案，每个问题属于一个类别。总共有492个类别，其中频率达到或超过10次的类别有434个。

数据集划分：数据去重并分成三个部分。训练集：142.5万；验证集：4.5万；测试集，数万，不提供下载。

可能的用途：可以做为通用中文语料，训练词向量或做为预训练的语料；也可以用于构建百科类问答；其中类别信息比较有用，可以用于做监督训练，从而构建

更好句子表示的模型、句子相似性任务等。

链接:https://pan.baidu.com/s/12TCEwC_Q3He65HtPKN17cA  密码:fu45

#####公开评测：

欢迎报告模型在验证集上的准确率。任务1： 类别预测。

报告包括：#1）验证集上准确率，#2）采用的模型、方法描述、运行方式（1页PDF），#3）可运行的源代码(可选)

基于#2和#3，我们会在测试集上做测试，并报告测试集上的准确率；只提供了#1和#2的队伍，验证集上的成绩依然可以被显示出来，但会被标记为未验证。

### Reference:

1. <a href='https://github.com/AimeeLee77/wiki_zh_word2vec'>利用Python构建Wiki中文语料词向量模型试验</a>

2. <a href='https://github.com/attardi/wikiextractor'>A tool for extracting plain text from Wikipedia dumps</a>

3. <a href='https://github.com/yichen0831/opencc-python'>Open Chinese convert (OpenCC) in pure Python:開放中文轉換</a>

4. <a href='https://dumps.wikimedia.org/zhwiki/latest/'>dumps of wiki, latest in chinese</a>


