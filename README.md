# 冰学无止尽

兴趣是最好的老师，我用冰学学text analysis \## 学习资料 [Text Mining with R](https://www.tidytextmining.com/)

## 一、词频统计

![Top 20 word freq](https://github.com/claregogo/bigice/blob/main/top20word_freq.png) 过滤单个汉字，仅保留有意义的词组 ![Top 20 word freq update](https://github.com/claregogo/bigice/blob/main/top_word_freq_update.pnggit)

## 二，分析大冰四本巨作：《乖，摸摸头》，《好吗，好的》，《你坏》，《我不》
首先合并四本巨著，使用jiebaR以及4个中文常用停用词表对四本冰书进行清理。 使用lda对四本本书做主题分类，四个主题下最常见的10个词组分别为： ![Top 20 word freq: big ice collection](https://github.com/claregogo/bigice/blob/main/bigice_collection.png) 如果我们随机抽取一页冰字，能不能把他放回到正确的冰书中呢？ ![find right icebook](https://github.com/claregogo/bigice/blob/main/findrighticebook.png) 通过分析我们发现，《好吗好的》，和《你坏》具有主题上的高度相似性，共享topic1；《我不》展示了他的独一无二性，《乖，摸摸头》在主题上有些不鲜明，但是在四本冰书中具有一定的原创性。 整体来看，随机挑选10个有意义的词组，无法判断它们来自那本冰书。

## 三，未来展望
1. 如何制作分章csv？目前只会本办法：epub转csv，也不会删除版权信息等与研究无关的文字。
2. 情感分析，学习中
3. 词性分析，学习中
。。。冰学大世界，学吧，学无止尽！