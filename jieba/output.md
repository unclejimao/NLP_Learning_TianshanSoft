# jieba_demo.py:
C:\Users\HY\anaconda\envs\tensorflow\python.exe D:/Users/HY/NLP_Learning_TianshanSoft/jieba/jieba_demo.py

jieba分词全模式：
Building prefix dict from the default dictionary ...
Loading model from cache C:\Users\HY\AppData\Local\Temp\jieba.cache
Loading model cost 0.630 seconds.
Full mode: 我/来到/北京/清华/清华大学/华大/大学
Prefix dict has been built succesfully.
分词后的结果seg_list本质是： <generator object Tokenizer.cut at 0x000001D54F08D468>
seg_list 数据类型： <class 'generator'>

jieba分词精确模式（默认模式）：
Default mode: 我/来到/北京/清华大学
Default mode: 他/来到/了/网易/杭研/大厦
seg_list 数据类型： <class 'generator'>

jieba分词搜索引擎模式：
Search engine mode: 小明，硕士，毕业，于，中国，科学，学院，科学院，中国科学院，计算，计算所，，，后，在，日本，京都，大学，日本京都大学，深造
分词后的结果seg_list本质是： <generator object Tokenizer.cut_for_search at 0x000001D54F08D468>
seg_list 数据类型： <class 'generator'>

# pos_seg.py:
C:\Users\HY\anaconda\envs\tensorflow\python.exe D:/Users/HY/NLP_Learning_TianshanSoft/jieba/pos_seg.py
4月24日，期待已久的《复仇者联盟4》终于在各大院线上映跟观众见面

标注返回结果的数据类型:  <class 'generator'>

jieba词性标注结果：
Building prefix dict from the default dictionary ...
Loading model from cache C:\Users\HY\AppData\Local\Temp\jieba.cache
4 m
Loading model cost 0.606 seconds.
月 m
24 m
日 m
， x
Prefix dict has been built succesfully.
期待已久 i
的 uj
《 x
复仇者 n
联盟 j
4 x
》 x
终于 d
在 p
各 r
大院 n
线 n
上映 v
跟 p
观众 n
见面 n

Process finished with exit code 0````