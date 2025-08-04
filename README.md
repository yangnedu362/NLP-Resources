# NLP Resources 

This repository is curated and maintained by Prof. Yang Li's Group at Northeast Electric Power University (NEEPU), China.

🌐 Visit our academic portal: [https://CausalNLP.ai](https://CausalNLP.ai)  
📚 Focus: Causal NLP · Trustworthy AI · Privacy-Preserving Models

## 🔍 Overview

This repository compiles high-quality NLP resources for research and development, including toolkits, corpora, learning materials, and technology summaries.

We aim to:
- Provide a one-stop reference for NLP learners and researchers.
- Promote open-access and reproducible research.
- Foster collaboration in trustworthy and responsible AI.
  
  
## Contents  
目录  

- [NLP Toolkits 自然语言处理工具包](#nlp-toolkits-自然语言处理工具包)  
  - [Toolkits 工具包](#toolkits)  
  - [Small Tools 小工具](#small-tools)  

- [NLP Corpus 自然语言处理语料库](#nlp-corpus-自然语言处理语料库)  
  - [Corpus Collection 语料采集](#corpus-collection)  
  - [Corpus Construction 语料构建](#corpus-construction)  

- [Learning Materials 学习资料](#learning-materials-学习资料)  
  - [DL Framework 深度学习框架](#dl-f)  
  - [ML Resources 机器学习书籍与资料](#ml-books-resources)  
  - [NLP Resources NLP书籍与资料](#nlp-books-resources)  
  - [Blogs and Courses 博客与课程](#blogs-courses)  

- [NLP Technology 自然语言处理相关技术](#nlp-technology-自然语言处理相关技术)  
  - [BERT Model BERT模型](#bert-model)  
  - [Text Modeling and Analysis 文本建模与分析](#text-modeling-and-analysis)  
  - [Text Similarity 文本相似度](#text-similarity)  
  - [Text Disambiguation 消歧义处理](#text-disambiguation)  
  - [Information Extraction 信息抽取](#information-extraction)  
  - [Text Generation 文本生成](#text-generation)  
  - [Sequence Labeling 序列标注](#sequence-labeling)  
  - [Reading Comprehension 阅读理解](#reading-comprehension)  
  - [QA System 问答系统](#qa-system)  
  - [Knowledge Graph 知识图谱](#knowledge-graph)  
  - [Relation Extraction 关系抽取](#relation-extraction)  

- [NLP Organizations 学术组织与研究机构](#nlp-organizations-学术组织)  
  - [Mainland China 中国大陆高校/研究所](#china-school)  
  - [Chinese Companies 中国大陆企业](#china-company)  
  - [Hong Kong / Macau / Taiwan 港澳台地区](#china-hmt)  
  - [Singapore / Japan / Israel / Australia 新加坡/日本/以色列/澳大利亚](#east-asia)  
  - [North America 北美地区](#north-america)  
  - [Europe 欧洲地区](#europe)  

- [Reference 参考资料](#reference)
  
  
## NLP Toolkits 自然语言处理工具包  
<a name="toolkits"></a>

This section introduces widely used NLP libraries and toolkits, covering both English and Chinese processing, implemented in various languages such as Python, Java, and C++.  
本节整理了常用的自然语言处理工具包，涵盖英文与中文处理，支持多种编程语言如 Python、Java、C++ 等。

### Toolkits 工具包

- [CoreNLP](https://github.com/stanfordnlp/CoreNLP): Java-based NLP toolkit from **Stanford**, providing robust syntactic and semantic analysis tools.  
  由斯坦福开发的 Java 自然语言处理工具集，支持句法与语义分析。

- [NLTK](http://www.nltk.org/): A classic **Python** NLP toolkit offering corpora, lexical resources, and text processing functions.  
  Python 编写的老牌 NLP 工具包，内含语料库、词汇资源与处理接口。

- [gensim](https://radimrehurek.com/gensim/) | [GitHub](https://github.com/RaRe-Technologies/gensim): Topic modeling and document similarity library in **Python**.  
  Python 编写的主题建模、文本相似度与向量空间工具库。

- [LTP](https://github.com/HIT-SCIR/ltp) | [官网](http://ltp.ai/): Language Technology Platform from HIT, supporting **Java & Python**.  
  哈工大开发的中文语言技术平台，支持词法与句法分析。

- [jieba](https://github.com/fxsjy/jieba): The most popular **Python** Chinese word segmentation library, widely used across platforms.  
  主流 Python 中文分词工具，适配多平台环境。

- [jieba_fast](https://github.com/deepcs233/jieba_fast): Optimized version of `jieba` using Cython for faster DAG and Viterbi computation.  
  用 Cython 优化 DAG 与 Viterbi 计算，大幅提升性能的 `jieba` 版本。

- [NLPIR](https://github.com/NLPIR-team/NLPIR): Chinese lexical analysis toolkit by CAS/BIT, supporting **Java**, with **Python** wrapper [PyNLPIR](https://github.com/tsroten/pynlpir).  
  中科院/北理工开发的中文 NLP 工具，Java 实现，支持 Python 接口。

- [HanLP](https://github.com/hankcs/HanLP): Industrial-grade Chinese NLP toolkit supporting **Java & Python**, with pretrained models.  
  商用级中文 NLP 工具包，支持多任务与预训练模型。

- [THULAC](http://thulac.thunlp.org/): Efficient Chinese lexical analyzer by Tsinghua, supporting **C++**, **Java**, and **Python**.  
  清华大学开发的高效中文词法分析工具，跨平台支持。

- [pkuseg](https://github.com/lancopku/pkuseg-python): Domain-specific Chinese segmentation toolkit from Peking University.  
  北大开发的多领域中文分词库，适用于新闻、电商、医疗等领域。

- [FudanNLP](https://github.com/FudanNLP/fnlp): NLP toolkit with datasets and ML algorithms in **Java**, from Fudan University.  
  复旦大学发布的 NLP 工具与算法平台，提供数据集支持。

- [Apache OpenNLP](https://opennlp.apache.org/): A **Java** toolkit for tokenization, POS tagging, NER, chunking, parsing, and coreference resolution.  
  Apache 出品的 Java 工具包，涵盖 NLP 主要任务。

- [SnowNLP](https://github.com/isnowfy/snownlp): Chinese NLP toolkit with support for segmentation, POS tagging, sentiment analysis, keyword & summary extraction (TextRank), etc.  
  支持分词、情感分析、拼音/简繁转换、关键词提取等中文处理功能。

- [Ansj Seg](https://github.com/NLPchina/ansj_seg): Java-based Chinese segmentation library using n-gram and CRF models.  
  Java 实现的中文分词工具，支持多种算法模式。


<a name="small-tools"></a>

### Small Tools 小工具

This section lists lightweight tools useful for Chinese linguistic processing, including pronunciation conversion, component lookup, error correction, and visualization.  
本节汇总了一些轻量级中文处理工具，如拼音转换、部首拆解、查询纠错及可视化工具等。

- [Chinese Cixing](https://github.com/liuhuanyong/ChineseCixing): Chinese character stroke decomposition, radical query, and pinyin conversion.  
  中文词语笔画拆解、偏旁部首查询与拼音转换。

- [Chai Zi](https://github.com/kfcd/chaizi): A decomposable Chinese character dictionary database with component-level data.  
  拆字字典数据库，可用于部件级别的字旁查询。

- [python-pinyin](https://github.com/mozillazg/python-pinyin): Convert Chinese characters to **Pinyin**, useful for phonetic annotation, sorting, and search.  
  汉字转拼音，可用于注音、排序与检索。

- [Nstools - zhTools](https://github.com/skydark/nstools/tree/master/zhtools): Simplified-Traditional Chinese character conversion.  
  中文繁简体互转工具。

- [QueryCorrection](https://github.com/liuhuanyong/QueryCorrection): Query spelling correction using pinyin similarity and edit distance.  
  基于拼音相似度与编辑距离的查询纠错工具。

- [50 Essential Matplotlib Visualizations](http://mob.dataguru.cn/mportal.php?mod=view&aid=14479): Most valuable Matplotlib visualizations (in Chinese).  
  Matplotlib 最有价值的可视化图例整理。

---

## NLP Corpus 自然语言处理语料库  
<a name="corpus-collection"></a>

This section collects widely used Chinese NLP corpora, including general-purpose, domain-specific, dialogue, lexicons, and pretrained embeddings.  
本节收录常用中文语料资源，涵盖通用语料、垂直领域、对话语料、词典与词向量等。

### Corpus Collection 语料集合

- [Wikipedia 中文版](https://dumps.wikimedia.org/zhwiki/): 中文维基百科全文 dump 数据。

- [NLP Corpus Collection](https://github.com/SimmerChan/corpus): NLP and KG-related datasets, organized by tasks.  
  自然语言处理与知识图谱语料集，按任务分类整理。

- [人民日报 1998 标注语料](https://pan.baidu.com/s/10_CQck5mKsKyfpA08slyFA): 标注版本人民日报中文语料。

- [Sogou Labs Datasets](http://www.sogou.com/labs/resource/list_pingce.php): Sogou provides Chinese collocation, news, and web-scale corpora.  
  搜狗实验室资源：中文搭配库、新闻数据与互联网语料。

- [Chinese Dialogue Corpus](https://github.com/codemayq/chaotbot_corpus_Chinese): Includes Chatterbot, Douban, PTT, Weibo, TV scripts, forums, etc.  
  中文多轮对话语料，覆盖豆瓣、微博、小黄鸡等。

- [THUOCL](https://github.com/thunlp/THUOCL): Domain-specific Chinese lexicons (e.g. IT, law, food, idioms).  
  清华开放中文词库，覆盖多个垂直领域。

- [Chinese Lexicon](http://www.hankcs.com/nlp/corpus/tens-of-millions-of-giant-chinese-word-library-share.html): Word lists including people names, organizations, etc.  
  各类中文词库，如人名、机构名等。

- [Chinese Dependency Treebank](http://www.hankcs.com/nlp/corpus/chinese-treebank.html): Provided by NLP&CC 2013 technical evaluation.  
  中文依存句法树库。

- [WeChat Public Corpus](https://github.com/nonamestreet/weixin_public_corpus): Crawled articles from public WeChat accounts.  
  微信公众号语料库。

- [Chinese Rumor Dataset](https://github.com/thunlp/Chinese_Rumor_Dataset): Fake news dataset from Sina Weibo.  
  新浪微博谣言数据集。

- [Tencent AI Embedding Corpus](https://ai.tencent.com/ailab/nlp/embedding.html): Chinese word and phrase embeddings.  
  腾讯 AI 实验室中文词向量。

- [Word2Vec Slim](https://github.com/eyaler/word2vec-slim): Slimmed version of Google News Word2Vec embeddings.  
  Google News 词向量简化版。

- [Chinese Word2Vec Models](https://github.com/to-shimo/chinese-word2vec): Pretrained Chinese embeddings.  
  中文 Word2Vec 预训练模型。

- [Chinese Word Vectors](https://github.com/Embedding/Chinese-Word-Vectors): Multiple pretrained embeddings in Chinese.  
  中文词向量集合。

- [nlp_chinese_corpus](https://github.com/brightmart/nlp_chinese_corpus): Includes Wikipedia, news, QA, and translation corpora.  
  包含百科、问答、翻译等多样语料。

- [Chinese Classical Poetry Corpus](https://github.com/chinese-poetry/chinese-poetry): A comprehensive Chinese poetry and literature database.  
  中文古典诗词数据库。

- [Chinese RC Dataset](https://github.com/ymcui/Chinese-RC-Dataset): Reading comprehension dataset in Chinese.  
  中文阅读理解数据集。

- [Chinese WOE Correction Corpus](http://nlg.csie.ntu.edu.tw/nlpresource/woe_corpus/): Word ordering error detection corpus.  
  中文语序纠错语料库。

- [THUCNews](http://thuctc.thunlp.org/): 740,000 categorized Chinese news articles from Sina RSS feeds (2005–2011).  
  THU 新闻文本分类数据集。

- [Company Name Corpus](https://github.com/wainshine/Company-Names-Corpus): Chinese company and organization name datasets.  
  公司、机构、品牌等名称词库。

- [Chinese Name Corpus](https://github.com/wainshine/Chinese-Names-Corpus): People name datasets (common, ancient, foreign).  
  中文人名、古人名、翻译人名等集合。

- [Abbreviation Dataset](https://github.com/zhangyics/Chinese-abbreviation-dataset): Chinese abbreviation wordlists.  
  中文简称词典。

- [Chinese-Xinhua](https://github.com/pwxcoo/chinese-xinhua): Xinhua dictionary data, idioms, proverbs, characters.  
  中华新华字典，含歇后语、成语、词语与汉字释义。

- [Couplet Dataset](https://github.com/wb14123/couplet-dataset): Chinese couplet data.  
  对联生成数据集。

- [5156Edu Tools](http://jyc.5156edu.com/): Chinese synonym/antonym/pinyin converters (in Chinese).  
  在线近义词、反义词与拼音转换工具。

- [EmotionLexicon](https://github.com/songkaisong/EmotionLexicon): Fine-grained emotion and sentiment dictionaries.  
  情感词典、网络词汇与停用词典。

- [Chinese Dictionary](https://github.com/guotong1988/chinese_dictionary): Synonym, antonym, and negation lists.  
  中文同义词、反义词、否定词等词表。

- [Synonyms](https://github.com/huyingxi/Synonyms): Chinese synonym toolkit.  
  中文近义词处理工具。

- [Chinese NLP Corpus](https://github.com/liuhuanyong/ChineseNLPCorpus): Semantic words, domain consensus, diachronic data, and evaluation corpora.  
  中文 NLP 通用/垂直/历时/评测语料集合。

- [CEC-Corpus](https://github.com/shijiebei2009/CEC-Corpus): Chinese Emergency Corpus for sudden event detection.  
  中文突发事件语料库。

- [HardNLU (NLP太难了系列)](https://github.com/fighting41love/hardNLU): Curated complex NLP tasks and resources.  
  面向复杂任务的中文 NLP 数据集合集。

<a name="corpus-construction"></a>

- Corpus Construction 语料构建工具

  - [Opencc Python](https://github.com/yichen0831/opencc-python) — Python-based converter between Traditional and Simplified Chinese.  
    Python 简繁体中文转换工具。

  - [Pinyin Python](https://github.com/mozillazg/python-pinyin) — Chinese-to-Pinyin converter in Python.  
    汉字转拼音的 Python 工具。

  - [Python模拟登陆](https://github.com/CriseLYJ/awesome-python-login-model) — Simulated login scripts for popular websites using Python.  
    使用 Python 模拟登录大型网站的工具集合。

  - [Baidu Baike Spider](https://github.com/jia-zh/Baidu-Baike-Spider) — Python-based crawler for Baidu Baike entries.  
    使用 Python 抓取百度百科词条的爬虫工具。

  - [Sina Weibo Spider](https://github.com/jia-zh/Sina-Weibo-Spider) — Java-based crawler for Sina Weibo content.  
    使用 Java 实现的新浪微博内容采集工具。

  - [Sougou Words Collector](https://github.com/liuhuanyong/SougouWordsCollector) — Tool for extracting and converting Sogou Input Method dictionaries.  
    搜狗输入法词库抓取与格式转换工具。

  - [Baike Knowledge Schema](https://github.com/liuhuanyong/BaikeKnowledgeSchema) — Crawler for extracting conceptual classification systems from Baidu and Hudong Baike.  
    面向百度百科与互动百科的概念分类体系抓取脚本。

  - [Baike Info Extraction](https://github.com/liuhuanyong/BaikeInfoExtraction) — Extracts structured infobox information from various Chinese encyclopedias.  
    对百科词条中的 infobox 结构化信息进行抽取与融合。

  - [Baidu Index Spyder](https://github.com/liuhuanyong/BaiduIndexSpyder) — Automatically collects historical Baidu search index data by keyword.  
    按关键词抓取百度搜索指数数据的自动化工具。

  - [Ali Index Spyder](https://github.com/liuhuanyong/AliIndexSpyder) — Crawler for Alibaba commodity indices including procurement and supply.  
    抓取阿里商品指数数据，包括淘宝与1688的采购和供应指数。

  - [新闻搜索引擎新闻爬取](https://github.com/jia-zh/News-Spider) — News crawler based on Scrapy framework, supporting Baidu, Sogou, Sina, 360, and Xinhua.  
    支持多家新闻搜索引擎的 Scrapy 框架爬虫。

  - [通用新闻类网站分布式爬虫](https://github.com/liubo0621/distributed-spider) — Distributed crawler for general news websites; extracts title, time, author, and content.  
    可提取新闻标题、时间、作者、正文等内容的通用分布式爬虫。

## Learning Materials 学习资料

<a name="dl-f"></a>

- Deep Learning Frameworks 深度学习框架

  - Keras [Official Docs](https://github.com/keras-team/keras), [Chinese Docs](https://keras-cn.readthedocs.io/en/latest/), [Examples](https://github.com/keras-team/keras/tree/master/examples)  
    Keras 官方文档、中文文档与示例代码。

  - TensorFlow [Official Docs](https://github.com/tensorflow/tensorflow), [Chinese Docs](http://www.tensorfly.cn/), [Tutorial in Chinese](https://github.com/CreatCodeBuild/TensorFlow-and-DeepLearning-Tutorial), [Examples](https://github.com/aymericdamien/TensorFlow-Examples), [Cookbook](https://github.com/taki0112/Tensorflow-Cookbook)  
    TensorFlow 全套资源，包括官方文档、中文教程与代码示例。

  - PyTorch [Official Docs](https://github.com/pytorch/pytorch), [Chinese Docs](https://pytorch.apachecn.org/#/), [Examples](https://github.com/yunjey/pytorch-tutorial), [Resources](https://github.com/bharathgs/Awesome-pytorch-list), [Practical Guide](https://zhuanlan.zhihu.com/p/29024978), [Awesome PyTorch](https://github.com/bharathgs/Awesome-pytorch-list), [PyTorch Tutorial](https://github.com/yunjey/pytorch-tutorial)  
    PyTorch 资源大全，包括中文手册、示例教程与高质量仓库列表。

  - [Deploying PyTorch Models via Flask](https://zhuanlan.zhihu.com/p/35879835) — REST API deployment example with Flask; applicable to other DL models.  
    使用 Flask 部署 PyTorch 模型教程，可推广至其他深度学习模型部署场景。

<a name="ml-books-resources"></a>

- ML Resources 机器学习书籍与资料

  - [Statistical Learning Methods](https://github.com/jia-zh/NLP-Resources/blob/master/books/%E7%BB%9F%E8%AE%A1%E5%AD%A6%E4%B9%A0%E6%96%B9%E6%B3%95_%E6%9D%8E%E8%88%AA.pdf) — A rigorous, foundational Chinese ML textbook, by Hang Li.  
    《统计学习方法》，经典教材，公式推导与定理逻辑严谨。

  - [Machine Learning (Zhou Zhihua)](https://github.com/jia-zh/NLP-Resources/blob/master/books/%E6%9C%BA%E5%99%A8%E5%AD%A6%E4%B9%A0_%E5%91%A8%E5%BF%97%E5%8D%8E.pdf) — Widely known as “The Watermelon Book,” a go-to for ML beginners.  
    周志华老师《机器学习》，入门必读教材。

  - [Deep Learning (Chinese Translation)](https://github.com/jia-zh/NLP-Resources/blob/master/books/%E6%B7%B1%E5%BA%A6%E5%AD%A6%E4%B9%A0%20%E4%B8%AD%E6%96%87%E7%89%88%20.pdf) — Chinese version of the book by Ian Goodfellow, Yoshua Bengio, and Aaron Courville. [GitHub source](https://github.com/exacity/deeplearningbook-chinese)  
    深度学习领域权威教材中文版，免费开源。

  - [Machine Learning Code Examples](https://github.com/wepe/MachineLearning) — Implementation of common ML algorithms.  
    常见机器学习算法的实现示例合集。

  - [Deep Learning 500 Questions](https://github.com/scutan90/DeepLearning-500-questions) — Q&A-style guide to DL/ML/linear algebra/probability/CV topics.  
    问答形式讲解概率论、线性代数、机器学习、深度学习与计算机视觉等内容。

  - [Neural Networks and Deep Learning](https://nndl.github.io/) — Covers CNN, RNN and applications in NLP and CV, by Xuipeng Qiu.  
    邱锡鹏老师编写的《神经网络与深度学习》，系统介绍主流模型与应用。

  - Andrew Ng's Notebooks: [ML Notes](https://github.com/fengdu78/Coursera-ML-AndrewNg-Notes), [Deep Learning Notes](https://github.com/fengdu78/deeplearning_ai_books)  
    吴恩达机器学习与深度学习课程笔记合集。

  - [Machine Learning Yearning](https://github.com/xiaqunfeng/machine-learning-yearning) — Practice-focused ML guidance by Andrew Ng.  
    强调实践经验的机器学习策略指导手册，作者：Andrew Ng。

<a name="nlp-books-resources"></a>

- NLP Resources 自然语言处理书籍与资料

  - [The Beauty of Mathematics in Computer Science](https://github.com/jia-zh/NLP-Resources/blob/master/books/%E6%95%B0%E5%AD%A6%E4%B9%8B%E7%BE%8E_%E5%90%B4%E5%86%9B.pdf) — A popular science book introducing NLP ideas, by Jun Wu.  
    吴军《数学之美》，NLP 入门经典，通俗易懂。

  - [Statistical Natural Language Processing](https://github.com/jia-zh/NLP-Resources/blob/master/books/%E7%BB%9F%E8%AE%A1%E8%87%AA%E7%84%B6%E8%AF%AD%E8%A8%80%E5%A4%84%E7%90%86%E7%AC%AC%E4%BA%8C%E7%89%88_%20%E5%AE%97%E6%88%90%E5%BA%86.pdf) — Comprehensive NLP theory and methodology, by Chengqing Zong.  
    宗成庆《统计自然语言处理》第二版，覆盖基础与最新进展。

  - [Neural Network Methods for NLP](https://github.com/jia-zh/NLP-Resources/blob/master/books/Neural%20Network%20Methods%20for%20Natural%20Language%20Proces_Yoav%20Goldberg.pdf) — Techniques in NLP with neural networks, by Yoav Goldberg.  
    Yoav Goldberg 所著神经网络 NLP 方法书籍。

  - [Report on Chinese Information Development](https://cips-upload.bj.bcebos.com/cips2016.pdf) — 2016 overview by Chinese Information Processing Society.  
    中国中文信息学会发布的 NLP 发展概览。

  - [Speech and Language Processing (3rd Edition)](https://web.stanford.edu/~jurafsky/slp3/) — Classic NLP textbook by Dan Jurafsky and James H. Martin.  
    NLP 权威教材，Jurafsky 与 Martin 合著。

  - [Deep Learning for NLP (CityU Lecture)](http://nlp.fudan.edu.cn/xpqiu/slides/20160618_DL4NLP@CityU.pdf) — Application of DL in NLP, by Xuipeng Qiu.  
    邱锡鹏老师关于深度学习与 NLP 的讲义。

  - [NLP Reading List (2019)](https://zhuanlan.zhihu.com/p/58874484) — Introductory NLP book recommendations by Zhiyuan Liu.  
    刘知远老师推荐的 NLP 入门阅读清单（2019年版）。

  - [nlp](https://github.com/duoergun0729/nlp) — An open-source NLP introduction book.  
    一本结构清晰的开源 NLP 入门书。

<a name="blogs-courses"></a>

- Blogs and Courses 博客和课程

  - NLP Chinese Blogs 中文博客：
    - [52NLP](http://www.52nlp.cn/)
    - [Hankcs 码农场 (Hankcs' Coding Farm)](http://www.hankcs.com/)
    - [剑指汉语自然语言处理 (Targeting Chinese NLP)](https://blog.csdn.net/FontThrone/column/info/16265)

  - NLP English Blogs 英文博客：
    - [Natural Language Processing Blog](https://nlpers.blogspot.com/)
    - [Language Log (UPenn)](http://languagelog.ldc.upenn.edu/nll/)
    - [Jay Alammar's Visual Blog](http://jalammar.github.io/)

  - AI Blog 人工智能博客：
    - [Google AI Blog](https://ai.googleblog.com/)

  - Stanford NLP Courses 斯坦福NLP课程资源：
    - [CS224n course homepage (课程主页)](http://web.stanford.edu/class/cs224n/)
    - [CS224d 2015 (YouTube)](https://www.youtube.com/playlist?list=PLmImxx8Char8dxWB9LRqdpCTmewaml96q)
    - [CS224d 2016 (YouTube)](https://www.youtube.com/playlist?list=PLmImxx8Char9Ig0ZHSyTqGsdhb9weEGam)
    - [CS224n Winter 2017 (YouTube)](https://www.youtube.com/playlist?list=PL3FW7Lu3i5Jsnh1rnUwq_TcylNr7EkRe6)

  - Oxford NLP Courses 牛津大学 NLP 课程：
    - [Oxford CS Deep NLP 2017 GitHub](https://github.com/oxford-cs-deepnlp-2017)

  - Stanford ML/DL Courses 斯坦福机器学习与深度学习课程：
    - [CS 229: Machine Learning (机器学习)](https://stanford.edu/~shervine/teaching/cs-229/)
    - [CS 230: Deep Learning (深度学习)](https://stanford.edu/~shervine/teaching/cs-230/)

  - Georgia Tech NLP Class 佐治亚理工 NLP 课程：
    - [GT CS 4650 / 7650](https://github.com/jacobeisenstein/gt-nlp-class)

  - YSDA NLP Course 俄罗斯高等经济学院 NLP 课程：
    - [NLP Course by Yandex (Yandex课程)](https://github.com/yandexdataschool/nlp_course)

---

## NLP Technology 自然语言处理相关技术

- [NLP Progress](https://github.com/yuquanle/NLP-progress)  
  Repository to track progress in NLP, including datasets and state-of-the-art results for various tasks.  
  跟踪 NLP 最新研究进展和主流任务的 SOTA 性能与数据集的项目。

- [Everything You Need to Know About Text Processing in NLP and ML](https://mp.weixin.qq.com/s?__biz=MzI1MjQ2OTQ3Ng==&mid=2247495751&idx=1&sn=f2fd87880418e994f5503c426185e9a0&chksm=e9e1f9ccde9670dad7a7cbc7cbd557fbf589c241a391af9a7afbb43899ee1bb1f2a91bf9f026&mpshare=1&scene=1&srcid=#rd)  
  A WeChat article introducing common text preprocessing methods in NLP and ML.  
  自然语言处理与机器学习中常见文本预处理方法汇总文章。

<a name="bert-model"></a>

- BERT Model 相关资源

  - [From Word Embedding to BERT: A History of Pretraining in NLP](https://www.jiqizhixin.com/articles/2018-12-10-8) by 张俊林  
    A historical overview of pretrained models in NLP, from word embeddings to BERT.  
    NLP 预训练模型发展简史，从词向量到 BERT 的演进。

  - [BERT GitHub (Google Research)](https://github.com/google-research/bert)  
    Official TensorFlow implementation and pretrained models by Google.  
    Google 官方发布的 BERT TensorFlow 实现及预训练模型。

  - [Awesome BERT](https://github.com/Jiakui/awesome-bert)  
    A curated list of papers, applications, and resources related to BERT.  
    BERT 相关论文、应用与资源整合列表。

  - [Awesome BERT NLP](https://github.com/cedrickchee/awesome-bert-nlp)  
    Resources focused on BERT, attention mechanisms, Transformers, and transfer learning.  
    聚焦 BERT、注意力机制、Transformer 和迁移学习的精选资源。

  - [The Illustrated BERT, ELMo, and co.](https://jalammar.github.io/illustrated-bert/)  
    Visual and intuitive explanation of BERT and ELMo by Jay Alammar.  
    Jay Alammar 用可视化方式通俗解释 BERT 和 ELMo 模型。

  - [BERT as a Service](https://github.com/hanxiao/bert-as-service)  
    Use BERT as an encoder service to generate fixed-length sentence embeddings.  
    将 BERT 模型作为服务使用，生成句子向量表示。

  - [PyTorch Pretrained BERT](https://github.com/huggingface/pytorch-pretrained-BERT)  
    PyTorch implementation and pretrained BERT models by HuggingFace.  
    HuggingFace 提供的 PyTorch 版本 BERT 实现与预训练模型。

  - [BERT Classification Tutorial](https://github.com/Socialbird-AILab/BERT-Classification-Tutorial)  
    Practical tutorial on using BERT for text classification.  
    使用 BERT 进行文本分类的实战教程。

  - [BERT Utils](https://github.com/terrifyzhao/bert-utils)  
    Utilities for sentence embeddings, classification, and similarity computation with BERT.  
    提供 BERT 的句向量生成、文本分类、相似度计算工具代码。

  - [BERT BiLSTM-CRF for NER](https://github.com/macanv/BERT-BiLSTM-CRF-NER)  
    TensorFlow implementation for NER using BERT + BiLSTM-CRF.  
    使用 BERT 与 BiLSTM-CRF 实现命名实体识别（NER）。

  - [BERT Chinese NER](https://github.com/ProHiryu/bert-chinese-ner)  
    BERT-based approach for Chinese named entity recognition.  
    基于 BERT 的中文命名实体识别模型。

  - [BERT Innovations in NLP](https://mp.weixin.qq.com/s?__biz=MzI0ODcxODk5OA==&mid=2247505634&idx=1&sn=34e163b399a3fcb9a899cb72aeef1bab&chksm=e99ee51bdee96c0d17695cfd83e5dbcc8467f3d3358c87461416c69d13473c775afbb29405ea) by 张俊林  
    A comprehensive review of BERT innovations across NLP tasks.  
    全面综述 BERT 在各类 NLP 任务中的创新与应用。

<a name="text-modeling-and-analysis"></a>

- Text Modeling and Analysis

  - [Self Attention Mechanism](https://github.com/roomylee/self-attentive-emb-tf) Simple TensorFlow implementation of "[A Structured Self-attentive Sentence Embedding](https://arxiv.org/abs/1703.03130)" (ICLR 2017)
  
  - [Encoder Decoder](https://github.com/jacoxu/encoder_decoder) Four types of encoder-decoder models implemented using Python, Theano, Keras, and Seq2Seq
  
  - [Seq2seq](https://github.com/farizrahman4u/seq2seq) Sequence-to-sequence learning with Keras
  
  - [Keras Language Modeling](https://github.com/codekansas/keras-language-modeling) Language modeling code for question-answering tasks using Keras
  
  - [CNN for Sentence Classification in Keras](https://github.com/alexander-rakhlin/CNN-for-Sentence-Classification-in-Keras) Keras implementation of "[Convolutional Neural Networks for Sentence Classification](https://arxiv.org/pdf/1408.5882.pdf)" (EMNLP 2014)
  
  - [CNN for Classification](https://github.com/Shijihao/CNN_for_classification) PyTorch implementation of CNN for sentence classification
  
  - [Awesome NLP Sentiment Analysis](https://github.com/haiker2011/awesome-nlp-sentiment-analysis) A curated list of datasets, papers, and open-source implementations for sentiment analysis

<a name="text-similarity"></a>

- Text Similarity

  - [Cilin and Hownet](https://github.com/yaleimeng/Final_word_Similarity) Word similarity computation using extended Chinese thesaurus (Cilin) and HowNet
  
  - [Similarity Compute](https://github.com/liuhuanyong/SentenceSimilarity) Sentence similarity based on Cilin, HowNet, fingerprints, word embeddings, and VSM
  
  - [Siamese Sentence Similarity](https://github.com/liuhuanyong/SiameseSentenceSimilarity) Siamese BiLSTM model for sentence similarity with training and test datasets
  
  - [SentenceSim](https://github.com/fssqawj/SentenceSim) Chinese short sentence similarity based on HowNet, Onehot, word2vec, Harbin SDP, LSTM, and fusion algorithms

<a name="text-disambiguation"></a>

- Text Disambiguation

  - [Word MultiSense Disambiguation](https://github.com/liuhuanyong/WordMultiSenseDisambiguation) Disambiguation and multi-sense acquisition for Chinese words using encyclopedic knowledge

<a name="information-extraction"></a>

- Information Extraction

  - [Open IE Papers](https://github.com/NPCai/Open-IE-Papers) Collection of OpenIE and ORE papers and resources

  - [Relation Extraction Summary](http://shomy.top/2018/02/28/relation-extraction/) A summary of relation extraction/classification papers from 2013–2017

  - [LM-LSTM-CRF](https://github.com/jia-zh/NLP-Resourcesss/blob/master/Information%20Extraction.md) PyTorch implementation of "[Empower Sequence Labeling with Task-Aware Neural Language Model](http://arxiv.org/abs/1709.04109)" (AAAI 2018)

  - [Named Entity Relation Extraction](https://github.com/twjiang/NamedEntity_realtion_extraction) Entity relation extraction using syntactic parsing

  - [Pytorch Relation Extraction](https://github.com/ShomyLiu/pytorch-relation-extraction) PyTorch reproduction of [PCNN + MIL (Zeng 2015)](http://aclweb.org/anthology/D/D15/D15-1203.pdf) and [PCNN + ATT (Lin 2016)](http://nlp.csai.tsinghua.edu.cn/~lyk/publications/acl2016_nre.pdf)

  - [Zh NER TF](https://github.com/fighting41love/zh-NER-TF) BiLSTM-CRF model for Chinese NER using TensorFlow

  - [BERT BiLSTM CRF NER](https://github.com/macanv/BERT-BiLSTM-CRF-NER) NER using BERT with BiLSTM-CRF (TensorFlow)

  - [Event Triples Extraction](https://github.com/liuhuanyong/EventTriplesExtraction) Event triple extraction using dependency parsing and semantic role labeling

  - [Important Event Extractor](https://github.com/liuhuanyong/ImportantEventExtractor) Ranking news importance based on DoCRank and selecting timeline highlights

  - [Text Grapher](https://github.com/liuhuanyong/TextGrapher) Extracts and structures key document information into a semantic graph

  - [Knowledge Graph from Scratch](https://zhuanlan.zhihu.com/c_1018901137012928512) Zhihu column on building knowledge graphs from scratch

  - [Text Info Exp](https://github.com/Roshanson/TextInfoExp) Toolkit for TF-IDF, classification, clustering, word vectors, sentiment, and relation extraction

<a name="text-generation"></a>

- Text Generation

  - [Texar](https://github.com/asyml/texar) A toolkit for text generation and beyond

  - [Awesome Text Generation](https://github.com/ChenChengKuan/awesome-text-generation) A curated list of recent models and applications in text generation

  - [Ehud Reiter's Blog](https://ehudreiter.com/) In-depth discussions on NLG techniques, evaluation, and applications

  - [Talk Latent](https://github.com/harvardnlp/Talk-Latent/blob/master/main.pdf) Slides for “Controlling Text Generation” by Alexander Rush

<a name="sequence-labeling"></a>

- Sequence Labeling

  - [Kashgari](https://github.com/BrikerMan/Kashgari) A simple and powerful NLP framework for NER, POS tagging, and text classification; build state-of-the-art models in minutes

<a name="reading-comprehension"></a>

- Reading Comprehension

  - [CMRC 2017](https://github.com/ymcui/cmrc2017) First Chinese Machine Reading Comprehension evaluation workshop

  - [CMRC 2018](https://github.com/ymcui/cmrc2018) Second Chinese Machine Reading Comprehension evaluation workshop

  - [Neural Reading Comprehension and Beyond](https://stacks.stanford.edu/file/druid:gd576xb1833/thesis-augmented.pdf) PhD thesis by Danqi Chen on neural reading comprehension

  - [Teaching Machines to Read](http://rsarxiv.github.io/2016/06/18/%E6%95%99%E6%9C%BA%E5%99%A8%E5%AD%A6%E4%B9%A0%E9%98%85%E8%AF%BB/) A review article on machine reading comprehension and key research papers

<a name="qa-system"></a>

- QA System

  - [AnyQ](https://github.com/baidu/AnyQ) FAQ-based question answering system by Baidu

  - [KBQA using Seq2Seq](https://zhuanlan.zhihu.com/p/34585912) Implementation of a knowledge-base QA system with seq2seq model, [GitHub](https://github.com/wavewangyue/kbqa)

<a name="knowledge-graph"></a>

- Knowledge Graph

  - [Intro Guide to Knowledge Graph Technology](https://www.jiqizhixin.com/articles/2018-06-20-4) A beginner-friendly guide to knowledge graph technology and applications

  - [Slides About Knowledge Graph](https://pan.baidu.com/s/1zS8Yye88bk7yAbQnyBdr0Q) Collection of knowledge graph slides, Baidu Netdisk code: z5yb

  - [Agriculture Knowledge Graph](https://github.com/cjm1044642385/Agriculture_KnowledgeGraph) Tools for entity recognition, relation extraction, classification trees, and data mining in agriculture

  - [Person Relation Knowledge Graph](https://github.com/liuhuanyong/PersonRelationKnowledgeGraph) Chinese person relation knowledge graph construction, distant supervision, bootstrapping, and QA applications

  - [Awesome Knowledge Graph](https://github.com/husthuke/awesome-knowledge-graph) Curated resources for learning and building knowledge graphs

  - [Automatic/Semi-automatic Knowledge Extraction](http://blog.sina.com.cn/s/blog_4caedc7a0102ewpj.html) Blog post from Microsoft Research Asia on knowledge base construction

  - [Bottom-Up Knowledge Graph Construction](http://www.4u4v.net/xiang-jie-zi-xia-er-shang-gou-jian-zhi-shi-tu-pu-quan-guo-cheng.html?from=timeline) Detailed tutorial on constructing knowledge graphs from the bottom-up

  - [Chinese Knowledge Graph APIs and Tools](https://blog.csdn.net/sinat_26917383/article/details/66473253) A summary of Chinese APIs, tools, research institutes, and frameworks

  - [Product-Oriented View on Knowledge Graphs](http://www.woshipm.com/it/1088237.html) Analysis of the value and application of knowledge graphs from a product management perspective

  - [Military Knowledge Graph and QA](https://github.com/liuhuanyong/QAonMilitaryKG) QA system for military knowledge graph (5800+ entries), including spacecraft, aircraft, and space equipment

<a name="relation-extraction"></a>

- Relation Extraction

  - [Relation Extraction Summary](http://shomy.top/2018/02/28/relation-extraction/) Explanation of relation extraction, dataset introductions, and a summary of key works (2013–2017)

        
## <a name="nlp-organizations"></a> NLP Organizations

**Note: The order does not indicate ranking. This list is not exhaustive—contributions are welcome!**

- [ACL Anthology](https://aclanthology.info/)  
  A digital archive of research papers in natural language processing and computational linguistics.

- [NLP Conference Calendar](http://cs.rochester.edu/~omidb/nlpcalendar/)  
  A maintained calendar for major NLP conferences and submission deadlines.

---

<a name="china-school"></a>

### Academic Institutions in Mainland China

- [NLP Group, Institute of Computing Technology, Chinese Academy of Sciences](http://nlp.ict.ac.cn/index_zh.php)

- [NLP Group, Institute of Automation, Chinese Academy of Sciences](http://nlp.ict.ac.cn/index_zh.php)

- [Chinese Information Processing Lab, Institute of Software, CAS](http://www.icip.org.cn/zh/homepage/)

- [Natural Language Processing & Social Human Computing Lab, Tsinghua University](http://nlp.csai.tsinghua.edu.cn/site2/index.php/zh) – [GitHub](https://github.com/thunlp)

- [THUIR Group, State Key Lab of Intelligent Technology and Systems, Tsinghua University](http://www.thuir.cn/)

- [MOE Key Laboratory of Computational Linguistics, Peking University](http://klcl.pku.edu.cn/)

- [Institute of Computational Linguistics, Peking University](http://icl.pku.edu.cn/)

- [Language Computing and Web Mining Lab, PKU](http://59.108.48.12/lcwm/index.php?title=%E9%A6%96%E9%A1%B5)

- [Social Computing and Information Retrieval Center, Harbin Institute of Technology](http://ir.hit.edu.cn/)

- [Intelligent Technology and NLP Lab, HIT](http://insun.hit.edu.cn/main.htm)

- [Machine Intelligence and Translation Lab, HIT](http://mitlab.hit.edu.cn/)

- [NLP Group, Fudan University](http://nlp.fudan.edu.cn/)

- [NLP Group, Soochow University](http://nlp.suda.edu.cn/)

- [Institute for Human Language Technology, Soochow University](http://hlt.suda.edu.cn/)

- [NLP Group, Nanjing University](http://nlp.nju.edu.cn/homepage/)

- [NLP Lab, Northeastern University](http://www.nlplab.com/)

- [NLP Lab, Xiamen University](http://nlp.xmu.edu.cn/)

- [NLP Lab, Zhengzhou University](http://nlp.zzu.edu.cn/)

---

<a name="china-company"></a>

### Companies and Research Labs in Mainland China

- [Natural Language Computing Group, Microsoft Research Asia](https://www.microsoft.com/en-us/research/group/natural-language-computing/)

- [Huawei Noah's Ark Lab](http://www.noahlab.com.hk/)

- [Tencent AI Lab – NLP Center](https://ai.tencent.com/ailab/nlp/)

- [NLP Department, Baidu](https://nlp.baidu.com/)

- [Toutiao AI Lab](http://lab.toutiao.com/)

---

<a name="china-hmt"></a>

### Institutions in Hong Kong, Macau, and Taiwan

- [Text Mining Group, CUHK](http://www1.se.cuhk.edu.hk/~textmine/)  
  Chinese University of Hong Kong

- [Social Media Mining Group, PolyU](http://www4.comp.polyu.edu.hk/~cswjli/Group.html)  
  The Hong Kong Polytechnic University

- [Human Language Technology Center, HKUST](http://www.cse.ust.hk/~hltc/)  
  Hong Kong University of Science and Technology

- [NLP<sup>2</sup>CT Lab, University of Macau](http://nlp2ct.cis.umac.mo/index.html)  
  NLP and Portuguese-Chinese Machine Translation Lab

- [NLP Lab, National Taiwan University](http://nlg.csie.ntu.edu.tw/)


<a name="east-asia"></a>
  
- 新加坡/日本/以色列/澳大利亚

  - [NUS Natural Language Processing Group](http://www.comp.nus.edu.sg/~nlp/index.html)（新加坡国立大学自然语言处理组）

  - [NLP and Big Data Research Group in the ISTD pillar at the Singapore University of Technology and Design](http://www.statnlp.org/) （新加坡科技设计大学自然语言处理和大数据研究组） 
  
  - [NLP Research Group at the Nanyang Technological University](https://ntunlpsg.github.io/)（南洋理工大学自然语言处理组）
  
  - [Advanced Translation Technology Laboratory at National Institute of Information and Communications Technology](http://att-astrec.nict.go.jp/en/)（日本情报通讯研究所高级翻译技术实验室）
  
  - [Nakayama Laboratory at University of Tokyo](http://www.nlab.ci.i.u-tokyo.ac.jp/index-e.html) （东京大学中山实验室） 
  
  - [Natural Language Processing Lab at Bar-Ilan University](http://u.cs.biu.ac.il/~nlp/)  （以色列巴伊兰大学自然语言处理实验室）

  - [The University of Melbourne NLP Group](http://hum.csse.unimelb.edu.au/nlp-group/)（澳大利亚墨尔本大学自然语言处理组）

<a name="north-america"></a>

## North American Institutions 北美地区

- [Natural Language Processing - Research at Google](https://research.google.com/pubs/NaturalLanguageProcessing.html)  
  Google NLP Research Group （Google自然语言处理组）

- [The Redmond-based Natural Language Processing group](http://research.microsoft.com/en-us/groups/nlp/)  
  Microsoft NLP Group （微软自然语言处理组）

- [Facebook AI Research (FAIR)](https://research.fb.com)  
  Facebook AI Research （Facebook AI研究部）

- [IBM Thomas J. Watson Research Center](http://researchweb.watson.ibm.com/labs/watson/index.shtml)  
  IBM Thomas J. Watson Research Center（IBM研究中心）

- [The Stanford Natural Language Processing Group](http://nlp.stanford.edu/)  
  Stanford NLP Group（斯坦福大学自然语言处理组）

- [The Berkeley Natural Language Processing Group](http://nlp.cs.berkeley.edu/index.shtml)  
  Berkeley NLP Group（加州大学伯克利分校自然语言处理组）

- [Natural Language Processing research at Columbia University](http://www1.cs.columbia.edu/nlp/index.cgi)  
  Columbia University NLP Group（哥伦比亚大学自然语言处理组）

- [Graham Neubig's lab at the Language Technologies Institute of Carnegie Mellon University](http://www.cs.cmu.edu/~neulab/)  
  CMU NeuLab（卡内基梅隆大学Graham Neubig实验室）

- [RPI Blender Lab](http://nlp.cs.rpi.edu/)  
  NLP Lab at Rensselaer Polytechnic Institute（伦斯勒理工学院NLP实验室）

- [UC Santa Barbara Natural Language Processing Group](http://nlp.cs.ucsb.edu/)  
  UCSB NLP Group（加州大学圣塔芭芭拉分校NLP组）

- [The Natural Language Group at the USC Information Sciences Institute](http://nlg.isi.edu/)  
  USC ISI NLP Group（南加州大学信息科学研究所NLP组）

- [Natural Language Processing @USC](https://cl.usc.edu/)  
  USC NLP Group（南加州大学自然语言处理组）

- [Natural Language Processing Group at University of Notre Dame](http://nlp.nd.edu/)  
  Notre Dame NLP Group（圣母大学NLP组）

- [Artificial Intelligence Research Group at Harvard](http://www.eecs.harvard.edu/ai/)  
  Harvard AI Group（哈佛大学人工智能研究组）

- [The Harvard natural-language processing group](http://nlp.seas.harvard.edu/)  
  Harvard NLP Group（哈佛大学NLP组）

- [Computational Linguistics and Information Processing at Maryland](https://wiki.umiacs.umd.edu/clip/index.php/Main_Page)  
  UMD CLIP Lab（马里兰大学计算语言学与信息处理实验室）

- [Language and Speech Processing at Johns Hopkins University](http://www.clsp.jhu.edu/about-clsp/)  
  JHU CLSP（约翰斯·霍普金斯大学语言与语音处理实验室）

- [Human Language Technology Center of Excellence at JHU](http://hltcoe.jhu.edu/)  
  JHU HLTCOE（人类语言技术卓越中心）

- [Machine Translation Group at The Johns Hopkins University](http://www.statmt.org/jhu/)  
  JHU Machine Translation Group（约翰斯·霍普金斯大学机器翻译组）

- [Machine Translation Research at Rochester](https://www.cs.rochester.edu/~gildea/mt/)  
  University of Rochester MT Group（罗切斯特大学机器翻译研究）

- [NLP @ University of Illinois at Urbana-Champaign](http://nlp.cs.illinois.edu/)  
  UIUC NLP Group（伊利诺伊大学厄巴纳-香槟分校NLP组）

- [UIC Natural Language Processing Laboratory](http://nlp.cs.uic.edu/)  
  UIC NLP Lab（伊利诺伊大学芝加哥分校NLP实验室）

- [Human Language Technology Research Institute at The University of Texas at Dallas](http://www.hlt.utdallas.edu/)  
  UT Dallas HLT Research Institute（德州大学达拉斯分校人类语言技术研究所）

- [Natural Language Processing Group at MIT CSAIL](http://nlp.csail.mit.edu/)  
  MIT NLP Group（麻省理工学院计算机与人工智能实验室）

- [Natural Language Processing Group at Texas A&M University](http://nlp.cs.tamu.edu/)  
  Texas A&M NLP Group（德州农工大学NLP组）

- [The Natural Language Processing Group at Northeastern University](https://nlp.ccis.northeastern.edu/)  
  Northeastern NLP Group（东北大学NLP组）

- [Cornell NLP group](https://confluence.cornell.edu/display/NLP/Home/)  
  Cornell NLP Group（康奈尔大学自然语言处理组）

- [Natural Language Processing group at University Of Washington](https://www.cs.washington.edu/research/nlp)  
  UW NLP Group（华盛顿大学NLP组）

- [Natural Language Processing Research Group at University of Utah](https://www.cs.utah.edu/nlp/)  
  University of Utah NLP Group（犹他大学自然语言处理组）

- [Natural Language Processing and Information Retrieval group at University of Pittsburgh](http://www.isp.pitt.edu/research/nlp-info-retrieval-group)  
  Pitt NLP & IR Group（匹兹堡大学NLP与信息检索组）

- [Brown Laboratory for Linguistic Information Processing (BLLIP)](http://bllip.cs.brown.edu/)  
  BLLIP at Brown University（布朗大学语言信息处理实验室）

- [Natural Language Processing (NLP) group at University of British Columbia](https://www.cs.ubc.ca/cs-research/lci/research-groups/natural-language-processing/)  
  UBC NLP Group（不列颠哥伦比亚大学NLP组）

  
<a name="europe"></a>

## European Institutions 欧洲地区

- [Natural Language and Information Processing Research Group at University of Cambridge](http://www.cl.cam.ac.uk/research/nl/)  
  University of Cambridge NLP Group（英国剑桥大学自然语言与信息处理组）

- [The Computational Linguistics Group at Oxford University](http://www.clg.ox.ac.uk/)  
  University of Oxford Computational Linguistics Group（英国牛津大学计算语言学组）

- [Human Language Technology and Pattern Recognition Group at the RWTH Aachen](https://www-i6.informatik.rwth-aachen.de/)  
  RWTH Aachen HLT & Pattern Recognition Group（德国亚琛工业大学语言技术与模式识别组）

- [The Natural Language Processing Group at the University of Edinburgh (EdinburghNLP)](http://edinburghnlp.inf.ed.ac.uk/)  
  University of Edinburgh NLP Group（英国爱丁堡大学自然语言处理研究组）

- [Statistical Machine Translation Group at the University of Edinburgh](http://www.statmt.org/ued/?n=Public.HomePage)  
  Edinburgh SMT Group（英国爱丁堡大学统计机器翻译组）

- [Natural Language Processing Research Group at The University of Sheffield](http://nlp.shef.ac.uk/)  
  University of Sheffield NLP Group（英国谢菲尔德大学自然语言处理组）

- [Speech Research Group at University of Cambridge](http://mi.eng.cam.ac.uk/Main/Speech/)  
  University of Cambridge Speech Research Group（剑桥大学语音研究组）

- [Statistical Machine Translation Group at the University of Cambridge](http://divf.eng.cam.ac.uk/smt)  
  Cambridge SMT Group（剑桥大学统计机器翻译组）

- [Computational Linguistics group at Uppsala University](http://www.lingfil.uu.se/forskning/datorlingvistik/?languageId=1)  
  Uppsala University CL Group（瑞典乌普萨拉大学计算语言学组）

- [The Center for Information and Language Processing at University of Munich](http://www.cis.uni-muenchen.de/ueber_uns/)  
  LMU Munich CIS（德国慕尼黑大学信息与语言处理中心）

- [National Centre for Language Technology at Dublin City University](http://www.nclt.dcu.ie/)  
  DCU NCLT（爱尔兰都柏林城市大学国家语言技术中心）

- [The National Centre for Text Mining (NaCTeM) at University of Manchester](http://nactem.ac.uk/)  
  University of Manchester NaCTeM（英国曼彻斯特大学国家文本挖掘中心）

- [The Information and Language Processing Systems group at the University of Amsterdam](http://ilps.science.uva.nl/)  
  University of Amsterdam ILPS Group（荷兰阿姆斯特丹大学信息与语言处理系统组）

- [Institute of Formal and Applied Linguistics at Charles University](http://ufal.mff.cuni.cz/)  
  Charles University UFAL（捷克查理大学语言学应用与规范研究所）

- [DFKI Language Technology Lab](https://www.dfki.de/lt/)  
  DFKI LT Lab（德国人工智能研究中心语言技术实验室）

- [IXA in University of the Basque Country](http://ixa.eus/)  
  University of the Basque Country IXA Group（西班牙巴斯克大学自然语言处理组）

- [Statistical Natural Language Processing Group at the Institute for Computational Linguistics at Heidelberg University](http://www.cl.uni-heidelberg.de/statnlpgroup/)  
  Heidelberg University StatNLP Group（德国海德堡大学统计自然语言处理组）

- [NLP Research at the University of Helsinki](https://blogs.helsinki.fi/language-technology/)  
  University of Helsinki NLP Group（芬兰赫尔辛基大学自然语言处理组）
   
    
    
## Reference

Some of the resources in this repository are adapted and organized based on the following excellent projects and community contributions. We express our sincere gratitude to their authors:

- [FunNLP](https://github.com/fighting41love/funNLP)  
- [Awesome Chinese NLP](https://github.com/crownpku/Awesome-Chinese-NLP)  
- [Domestic and International NLP Research Groups](https://blog.csdn.net/wangxinginnlp/article/details/44890553)  
- [NLP-Resources by Jia Zheng (zhengjia0826@163.com)](https://github.com/jia-zh/NLP-Resources)

Special thanks to Jia Zheng (Software Institute, Chinese Academy of Sciences) for his early contributions in organizing and compiling many of the resources.

Our team has further updated the content, optimized the structure, and continues to maintain it over time. If your work has been referenced without explicit credit, please contact us for proper acknowledgment.

📌 This repository is intended solely for academic learning and research purposes. Please refer to the original sources for usage permissions and licensing details. If you believe any content infringes your rights, please contact us and we will address or remove it promptly.
