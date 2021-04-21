# Fake News Detection Model
충북대학교 소프트웨어학과 팀 시카고의 졸업작품 Fake-News-Detection System에 들어갈 모델 학습시키는 레포지토리 입니다.


# Dependency
- Numpy
- Pandas
- NLTK

# Inference Process
```Pytorch-Transformers```를 사용해 모델을 학습 시켰습니다.

## 0. Data Cleaning & Preprocessing
- ```nltk```를 이용해 ```stop word``` 및 ```Punctuation``` 제거
- ```BertTokenizer```을 사용해 Tokenizing 했습니다.
## 1. Learning

# Dataset
캐글 Fake and real news dataset

https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset