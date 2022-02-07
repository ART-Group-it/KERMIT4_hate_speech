# Kermit as hate speech recognizer (_KERM-HATE_) :frog: :cursing_face:
[![Paper](https://img.shields.io/badge/paper-PeerJ-blue)](https://peerj.com/articles/cs-859/)
<p align="center">
<img src="./imgs/kermit.jpg" width="500"/>
</p>
This notebook contains all the helpful instructions for generating and training Kermit as _hate speech recognizer_.

As an example dataset, we will use the [Davidson dataset](https://ojs.aaai.org/index.php/ICWSM/article/view/14955).

## Model architecture

The architecture of the model is defined in the following image

<p align="center">
<img src="./imgs/architecture.png" width="500"/>
</p>

## Datasets
The _Datasets_ folder includes:
- The [Davidson dataset](https://ojs.aaai.org/index.php/ICWSM/article/view/14955)
- The _Election_datasets.zip_ : a corpus heavily used within our paper and generated by Manch Hui in his [Kaggle repository](https://www.kaggle.com/manchunhui/us-election-2020-tweets/metadata).
In detail, the .zip file consists of:
  - Democratic dataset
  - GOP dataset    

## How to cite us
```
@article{10.7717/peerj-cs.859,
 title = {Syntax and prejudice: ethically-charged biases of a syntax-based hate speech recognizer unveiled},
 author = {Mastromattei, Michele and Ranaldi, Leonardo and Fallucchi, Francesca and Zanzotto, Fabio Massimo},
 year = 2022,
 month = feb,
 keywords = {Hate speech, Explainability, Bias, Neural networks, Syntax},
 volume = 8,
 pages = {e859},
 journal = {PeerJ Computer Science},
 issn = {2376-5992},
 url = {https://doi.org/10.7717/peerj-cs.859},
 doi = {10.7717/peerj-cs.859}
}
```
