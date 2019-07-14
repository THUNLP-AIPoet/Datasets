Rhyme and Rhythm Data (RRD)
==========
This repository provides datasets developed by THUAIPoet (九歌) group, Research Center for Natural Language Processing, Computational Humanities and Social Sciences, Tsinghua University. *All our datasets are released for academic use only*.

* Fluency: are the lines of the poem fluent and well-formed?
* Coherence: is the poem as a whole coherent in meaning and theme?
* Meaningfulness: does the poem convey some certain messages?
* Overall Score: the reader’s general impression on the poem.

**Note**: The *Overall Score* is the general impression of the whole poem, instead of the sum or average score of the other three criteria.

Each poem is annotated by at least two human experts. In PQED, we provide the average of the scores given by different experts on each criterion. Because such evaluation is subjective, it's hard to guarantee accuracy. We will keep improving this dataset and try to alleviate individual preference.

## 1. Statistics and Version
### V0.1
* Number of poems: 173
* Provided criteria: fluency, coherence, meaningfulness and overall score
* The Genre of poetry: Chinese quatrain (*Jueju*, 绝句)

## 2. Format
PQED is saved in JSON format. Each line is a poem. An example is as follows:

```
{"poem": "渌水明秋月|南湖采白蘋|荷花娇欲语|愁杀荡舟人", "fluency": 4.0, "coherence": 4.0, "meaningfulness": 3.75, "overall score": 4.0}
```