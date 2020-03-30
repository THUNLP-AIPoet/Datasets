THU Chinese Rhythm and Rhyme Data (THU-CRRD)
==========
CRRD contains the rhythm and rhyme data for the  phonological rules of Chinese poetry.  Please note that this dataset is incomplete now and we will keep improving it.

## 1. Files and Version
### V1.0
* pingsheng.txt. The level-tone (平声) Chinese characters.
* zesheng.txt. The oblique-tone (仄声) Chinese characters.
* pingshui.txt. The pingsui rhyme category, in which the Chinese characters are categorized into to 30 rhyme classes.  Note that some polyphonic characters belong to multiple classes.
* pingshui_amb.pkl. We use a simple method to disambiguate the polyphonic rhyme characters in the pingsui rhyme category. This file will be needed when one runs our recently released models.

## 2. Cite
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