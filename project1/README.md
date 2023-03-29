# projcet1:自然语言处理入门

tips：不懂就google

## task1:基于bert的文本分类

1.任务：基于bert模型对清华新闻数据集进行文本分类任务

2.参考：<u>[How to Fine-Tune BERT for Text Classification?](https://arxiv.org/abs/1905.05583)</u>

3.实现要求：torch

4.数据集地址：https://thunlp.oss-cn-qingdao.aliyuncs.com/THUCNews.zip

5.知识点：bert（MLM，NSP，pretrain，finetune，down_stream task）

提交要求：task1内放源码，附带结果

## task2:基于gpt的文本生成

1.任务：基于gpt2模型在清华新闻数据集进行预训练，并以此为基础生成新闻

2.参考：<u>[gpt2_chinese](https://github.com/Morizeyao/GPT2-Chinese)</u> /<u>[gpt2_NewsTitle](https://github.com/liucongg/GPT2-NewsTitle)</u>

3.实现要求：torch

4.数据集地址：https://thunlp.oss-cn-qingdao.aliyuncs.com/THUCNews.zip

5.知识点：gpt（文本生成，语言模型）

提交要求：task2内放源码，附带随机输入新闻头部文字的结果