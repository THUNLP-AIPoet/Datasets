Poetry Quality Evaluation DataSet (PQED)
==========
PQED is a manually-annotated poetry quality dataset. Each poem is scored on a 5-point scale ranging from 1 to 5 in terms of the following four criteria:

* Fluency: are the lines of the poem fluent and well-formed?
* Coherence: is the poem as a whole coherent in meaning and theme?
* Meaningfulness: does the poem convey some certain messages?
* Overall Score: the reader’s general impression on the poem.

**Note**: The *Overall Score* is the general impression of the whole poem, instead of the sum or average score of the other three criteria.

Each poem is annotated by at least two human experts. In PQED, we provide the average of the scores given by different experts on each criterion. Because such evaluation is subjective, it's hard to guarantee accuracy. We will keep improving this dataset and try to alleviate individual preference.

## 0. Statistics and Version
### V0.1
* Number of poems: 173
* Provided criteria: fluency, coherence, meaningfulness and overall score
* The Genre of poetry: Chinese quatrain (*Jueju*, 绝句)

## 1. Format
PQED is saved in JSON format. Each line is a poem. An example is as follows:

```
{"poem": "渌水明秋月|南湖采白蘋|荷花娇欲语|愁杀荡舟人", "fluency": 4.0, "coherence": 4.0, "meaningfulness": 3.75, "overall score": 4.0}
```
## 2. Cite
If you use this dataset, please cite the following paper:

Xiaoyuan Yi, Maosong Sun, Ruoyu Li, and Wenhao Li. 2018. Automatic Poetry Generation with Mutual Reinforcement Learning. In *Proceedings of the 2018 Conference on Empirical Methods in Natural Language Processing*, pages 3143–3153, Brussels, Belgium. \[[pdf](https://aclweb.org/anthology/D18-1353)\]

bib format:
```
@inproceedings{Yimrl:18,
    author  = {Xiaoyuan Yi and Maosong Sun and Ruoyu Li and Wenhao Li},
    title   = {Automatic Poetry Generation with Mutual Reinforcement Learning},
    year    = "2018",
    pages   = "3143--3153",
    booktitle = {Proceedings of the 2018 Conference on Empirical Methods in Natural Language Processing},
    address = {Brussels, Belgium}  
}
```