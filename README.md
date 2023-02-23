# Unified Emotion Trace

Xing Wang, Shouhua Zhang, and Ivan Smetannikov. 2021. Fiction Popularity Prediction Based on Emotion Analysis. In Proceedings of the 2020 1st International Conference on Control, Robotics and Intelligent System (CCRIS '20). Association for Computing Machinery, New York, NY, USA, 169–175. https://doi.org/10.1145/3437802.3437831

## Project Structure

* `emotion_trace_analysis.ipynb` data analysis

* `emotion_trace_popularity_prediction_embedding.ipynb` popularity predcition using Keras embeddings

* `emotion_trace_popularity_prediction_et.ipynb` popularity prediction using Emotion Trace

* `dataset/` raw dataset crawled using https://github.com/wangx1ng/gutenberg-collector

* `emotion_traces/` generated Emotion Trace vectors

* `figures/` generated data insights figures

* `emotion_flow/` code using Emotion Trace method on the emotion flow dataset(https://github.com/sjmaharjan/emotion_flow)
  
## Cite

```
@inproceedings{10.1145/3437802.3437831,
author = {Wang, Xing and Zhang, Shouhua and Smetannikov, Ivan},
title = {Fiction Popularity Prediction Based on Emotion Analysis},
year = {2021},
isbn = {9781450388054},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3437802.3437831},
doi = {10.1145/3437802.3437831},
abstract = {In addition to bringing us knowledge, books also bring us emotional experiences. How do the emotional fluctuations brought by books affect readers’ evaluation of them? What is the difference in emotional fluctuations between books of different popularity? In this paper, we model and analyse the emotional fluctuations of different fiction books with different popularity and study the feasibility of predicting the popularity of fiction books using emotional fluctuations and recurrent neural networks. A new dataset is also generated to support this research and other related researches. Our proposed method obtained the best accuracy of 73.4% for predicting the popularity of fiction books and 41.4% for predicting genres. Some interesting data insights are also extracted from the dataset.},
booktitle = {Proceedings of the 2020 1st International Conference on Control, Robotics and Intelligent System},
pages = {169–175},
numpages = {7},
keywords = {Popularity Prediction, Natural Language Processing, Emotion Analysis},
location = {Xiamen, China},
series = {CCRIS '20}
}
```
