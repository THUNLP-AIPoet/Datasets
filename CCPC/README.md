THU Chinese Classical Poetry Corpus (THU-CCPC)
==========
CCPC is a Chinese classical poetry corpus with split training, testing and validation sets.  This corpus contains human-authored Chinese classical poems from Sui dynasty (A.D. 581 ) to Ming dynasty (A.D. 1644 ).  Each poem is accompanied by its author's name,  dynasty, title and automatically-extracted keywords.

We will keep improving this dataset and adding more genres of poetry.

## 1. Statistics and Version
### V1.0
* Number of poems:  Training  109,727; Validation  7,979;  Testing:  9,976
* The genre of poetry: quatrain (*Jueju*, 绝句)

## 2. Format
CCPC is saved in JSON format. Each line is a poem.  The sentences in a poem are seperated by the '|' symbol. Each poem is accompanied by 1~4 keywords automatically extracted by our keyword extraction tool.  An example is as follows:

```
{"dynasty": "Tang", "author": "杜牧", "content": "李白题诗水西寺|古木回岩楼阁风|半醒半醉游三日|红白花开山雨中", "title": "念昔游三首 其三", "keywords": "题诗 花开 楼阁 山雨"}
```
## 3. Cite
If you use this dataset, please kindly cite the following paper:

Zhipeng Guo, Xiaoyuan Yi, Maosong Sun, Wenhao Li, Cheng Yang, Jiannan Liang, Huimin Chen, Yuhui Zhang and Ruoyu Li. 2019.  Jiuge: A Human-Machine Collaborative Chinese Classical Poetry Generation System. In *Proceedings of the 57th Annual Meeting of the Association for Computational Linguistics: System Demonstrations*, pages 25–30, Florence, Italy. \[[pdf](https://www.aclweb.org/anthology/P19-3005.pdf)\]

bib format:
```
@inproceedings{jiuge:19,
    author  = {Zhipeng Guo and Xiaoyuan Yi and Maosong Sun and Wenhao Li and Cheng Yang and Jiannan Liang and Huimin Chen and Yuhui Zhang and Ruoyu Li},
    title   = "{J}iuge: A Human-Machine Collaborative {C}hinese Classical Poetry Generation System",
    year    = "2019",
    pages   = "25--30",
    booktitle = {Proceedings of the 57th Annual Meeting of the Association for Computational Linguistics: System Demonstrations},
    address = {Florence, Italy}
}
```
