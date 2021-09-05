# Kaggle-Commonlit-readability-prize

## Problem Statement
Build  an algorithm to rate the complexity of reading passages for grade 3-12 classroom use.

## Performance
| Code   | Public LB RMSE |Private LB RMSE| Notes | 
| ------------- | ------------- | --------------| --------------|
| [Ensemble of 2 Robertas]()https://github.com/bharadwaj-vedula/Kaggle-Commonlit-readability-prize/tree/main/RoBerta%20Ensemble  | 0.471  | 0.471 | Ensemble of two previously trained RoBertas (RoBerta Base + RoBerta Large)|
| [Roberta on TPUs](https://www.kaggle.com/bharadwajvedula/tpu-high-speed-roberta-training)  | NA | NA  | Notebook for training Roberta on TPUs |
| [Roberta Large Model](https://github.com/bharadwaj-vedula/Kaggle-Commonlit-readability-prize/tree/main/RoBerta%20Large)  | 0.479  | 0.478 | Finetuned on Roberta Large|
|[Ridge Model](https://www.kaggle.com/bharadwajvedula/clr-lb-0-475-lazy-way-to-get-good-score/data)| 0.475 | 0.479 | RoBerta was used as feature extractor and ridge was trainined on top of it|
| [Roberta Base Model](https://github.com/bharadwaj-vedula/Kaggle-Commonlit-readability-prize/tree/main/RoBerta%20Base)  | 0.479  | 0.481 | Finetuned on Roberta Base|
| [Roberta Base PyTorchLightning](https://github.com/bharadwaj-vedula/Kaggle-Commonlit-readability-prize/tree/main/Roberta%20Base%20Pytorch%20Lightning)  | 0.487  | 0.488 | Finetuned on Roberta Base with PyTorch Lightining|
| [Glove Embeddings Model](https://github.com/bharadwaj-vedula/Kaggle-Commonlit-readability-prize/tree/main/Glove)  | 0.683  | 0.702 | Models were trained with the help of Glove Pretrained Embeddings|
