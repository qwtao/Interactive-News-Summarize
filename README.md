# Interactive-News-Summarize
News<br>

* 所有原始新闻的文件夹<br> 

Pretreatment<br>

* 预处理.py<br>
    * 处理原始新闻，得到每类新闻的词典dict.txt与分词表示.txt，放在Ngrams/Processed的对应文件夹下<br>

Ngrams<br>

* Processed目录<br>
*  feature目录<br>
    * 存放计算出的ngram特征<br>
* main.py
    * 得到ngrams和计算特征的主模块  
* onegram.py  
    * 定义了AGram的类，记录ngram；以及计算ngram的函数  
* news.py  
    * 定义了新闻类，主要根据1gram的tfidf来计算每篇新闻向量表示  
* punc.txt  
    * 标点符号  

Regression<br>

* regre.py  
    * 利用/feature中的特征，进行回归训练  
