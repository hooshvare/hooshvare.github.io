---
layout: default
title: Sentiment Analysis
parent: Datasets
nav_order: 5
---

# Persian Sentiment Analysis
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## SnappFood

[Snappfood](https://snappfood.ir/) (an online food delivery company) user comments containing 70,000 comments with two labels (i.e. polarity classification): 

1. Happy
2. Sad


|   Label  |   #   |
|:--------:|:-----:|
| Negative | 35000 |
| Positive | 35000 |



**Download**
You can download the dataset from [here](https://bit.ly/2Xu2xq1)

**Cite**

Please cite the following paper in your publication if you are using this dataset in your research:



```markdown
@article{ParsBERT,
    title={ParsBERT: Transformer-based Model for Persian Language Understanding},
    author={Mehrdad Farahani, Mohammad Gharachorloo, Marzieh Farahani, Mohammad Manthouri},
    journal={ArXiv},
    year={2020},
    volume={abs/2005.12515}
}

```

---

## Digikala Sentiment

Digikala user comments provided by [Open Data Mining Program (ODMP)](https://www.digikala.com/opendata/). This dataset contains 62,321 user comments with three labels: 

|      Label      |    #   |
|:---------------:|:------:|
|     no_idea     |  10394 |
| not_recommended |  15885 |
|   recommended   |  36042 |


**Download**
You can download the dataset from [here](https://bit.ly/2ZzATut)

**Cite**

Please cite the following paper in your publication if you are using this dataset in your research:



```markdown
@article{ParsBERT,
    title={ParsBERT: Transformer-based Model for Persian Language Understanding},
    author={Mehrdad Farahani, Mohammad Gharachorloo, Marzieh Farahani, Mohammad Manthouri},
    journal={ArXiv},
    year={2020},
    volume={abs/2005.12515}
}

@misc{digikalanext, 
    title={DigikalaNext: Open Data Mining Program}, 
    url={https://www.digikala.com/opendata/}, 
    journal={DigikalaNext | Open Data Mining Program}
}
```

--- 

## DeepSentiPers Sentiment

which is a balanced and augmented version of SentiPers, contains 12,138 user opinions about digital products labeled with five different classes; two positives (i.e., happy and delighted), two negatives (i.e., furious and angry) and one neutral class. Therefore, this dataset can be utilized for both multi-class and binary classification. In the case of binary classification, the neutral class and its corresponding sentences are removed from the dataset.

**Binary:**
1. Negative (Furious + Angry)
3. Positive (Happy + Delighted)

**Multi**
1. Furious
2. Angry
3. Neutral
4. Happy
5. Delighted


|   Label   |   #  |
|:---------:|:----:|
|  Furious  |  236 |
|   Angry   | 1357 |
|  Neutral  | 2874 |
|   Happy   | 2848 |
| Delighted | 2516 |



**Download**
You can download the dataset from [here](https://bit.ly/3ejrbAn)

**Cite**

Please cite the following paper in your publication if you are using this dataset in your research:

```markdown
@article{ParsBERT,
    title={ParsBERT: Transformer-based Model for Persian Language Understanding},
    author={Mehrdad Farahani, Mohammad Gharachorloo, Marzieh Farahani, Mohammad Manthouri},
    journal={ArXiv},
    year={2020},
    volume={abs/2005.12515}
}

@misc{sharami2020deepsentipers,
    title={DeepSentiPers: Novel Deep Learning Models Trained Over Proposed Augmented Persian Sentiment Corpus},
    author={Javad PourMostafa Roshan Sharami and Parsa Abbasi Sarabestani and Seyed Abolghasem Mirroshandel},
    year={2020},
    eprint={2004.05328},
    archivePrefix={arXiv},
    primaryClass={cs.CL}
}
```