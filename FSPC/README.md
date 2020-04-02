Fine-grained Sentimental Poetry Corpus (FSPC)
==========
FSPC is a manually-labelled Fine-grained Sentiment Poetry Corpus. Each poem and each line is annotated into 5 classes, namely negative, implicit negative, neutral, implicit positive and positive. Details of the corpus please look into our paper.

As the sentiment expression of Chinese classical poetry is often implicit, and sometimes the understanding varies from person to person,  it is difficult to have completely objective sentimental labels, although we adopted a reasonable annotation mechanism.

We will continue to optimize and expand this data set.

## 1. Statistics and Version
### V1.0
* Number of poems: 5,000
* Sentiment Classes: negative, implicit negative, neutral, implicit positive and positive

Detailed Statistics:
![image](../pictures/FSPC.jpg)
Neg. is the abbreviation of negative and Pos. is the abbreviation of positive.

## 2. Format
FSPC is saved in JSON format. Each line is a poem. An example is as follows:

```
{
    "poet": "韦庄", 
    "poem": "自有春愁正断魂|不堪芳草思王孙|落花寂寂黄昏雨|深院无人独倚门", 
    "dynasty": "唐", 
    "setiments": {"holistic": "1", "line1": "1", "line2": "1", "line3": "2", "line4": "2"}, 
    "title": "春愁"
}
```
Lines and sentiments in a poem are split by "|". Sentiments dict contains the holistic sentiment of whole poem, sentiment of the first line, ..., sentiment of the fourth line. The labels of setiments represent  1: negative, 2:implicit negative, 3:neutral, 4:implicit positive and 5:positive 

## 3. Cite
If you use this corpus, please cite the following paper:

Huimin Chen, Xiaoyuan Yi, Maosong Sun, Cheng Yang, Wenhao Li and Zhipeng Guo. 2019. Sentiment-Controllable Chinese Poetry Generation. In *Proceedings of the Twenty-Eighth International Joint Conference on Artificial Intelligence*, Macao, China. \[[pdf](http://114.215.64.60/~chm/publications/ijcai2019_SCPG.pdf)\]

bib format:
```
@inproceedings{chensentiment:19,
    author  = {Huimin Chen and Xiaoyuan Yi and Maosong Sun and Cheng Yang and Wenhao Li and Zhipeng Guo},
    title   = {Sentiment-Controllable Chinese Poetry Generation},
    year    = "2019",
    booktitle = {Proceedings of the Twenty-Eighth International Joint Conference on Artificial Intelligence},
    address = {Macao, China}  
}
```
