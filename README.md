# BC-Wikipedia-Concepts

The dissemination of information worldwide is significantly facilitated by the news media, with many events having global relevance across various regions. However, certain news events receive limited coverage, restricted to specific geographic areas, due to barriers that hinder the spread of information. These barriers can be attributed to political, geographical, economic, cultural, or linguistic factors. In this research, we propose an approach for classifying these barriers by extracting semantic information from news articles using Wikipedia-concepts. Our methodology involves the collection of news articles, each annotated to indicate the specific barrier types, leveraging metadata from news publishers. Subsequently, we employ Wikipedia-concepts, in conjunction with the content of the news articles, as features to determine the barriers to news dissemination. Our approach is then compared with traditional text classification techniques, deep learning methods, and transformer-based models. \begin{MyColorPar}{red}The findings indicate that 1) Utilizing semantic knowledge based on Wikipedia-concepts yields distinct categories across the ten classes, thereby enhancing the effectiveness and speed of the classification model. 2) The proposed approach, incorporating Wikipedia-concepts-based semantic knowledge, leads to improved performance in barrier classification when compared to using solely the body text of news articles. Specifically, there is a notable increase in the average F1-scores for four out of five barriers, with economic barrier rising from 0.65 to 0.68, linguistic barrier from 0.71 to 0.72, political barrier from 0.68 to 0.70, and geographical barrier from 0.63 to 0.68.

## Approach
![](/assets/meth.PNG "meth")

## Meta data
![](/assets/MetaDataBarriers-1.PNG "MetaDataBarriers-1")

## Information Spreading
![](/assets/ArticlePerPublisher.png "ArticlePerPublisher")
![](/assets/NumberOfPublisher.png "NumberOfPublisher")
![](/assets/EventsPerPublishers.png "EventsPerPublishers")
![](/assets/venn_resultr.png "venn_result")
![](/assets/venn_result2.png "venn_result2")

## Results
![](/assets/WC-Avg-resul.png "WC-Avg-resul")

## Requirements

We recommend Conda with Python3. Use requirements.txt to create the necessary environment. 
