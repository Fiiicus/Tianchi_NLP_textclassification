# Tianchi_NLP_textclassification

对单词做 embedding 后加上 word2vec 得到词向量表示，对每个句子做 textCNN 加最大池化提取句子中的局部特征，再做双向 LSTM 得到句向量，对每篇文章的所有句向量做 self-attention，挖掘句间相关性，最后用全连接层加 softmax 分类。
