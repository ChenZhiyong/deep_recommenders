# DeepRecSys
[![python](https://img.shields.io/badge/python-=3.7-brightgreen)](requirements.txt)
[![tensorflow](https://img.shields.io/badge/tensorflow-=2.2-brightgreen)](requirements.txt)
[![license](https://img.shields.io/badge/license-MIT-green)](LICENSE)


此代码库包含推荐系统领域中经典或最新的 `CTR` 模型和 `Match` 模型，以及其他相关深度模型的实现。<br/>
此代码库主要用于自我学习和提升, 还希望能够帮助对推荐系统感兴趣的朋友和同学，共同进步。

由于本人水平有限，如有错误，还望指正。

## Projects

### CTR
* [Factorization Machines](deep_recommend/recommend/ctr/fm)(2010) `Done`
* [DeepFM: A Factorization-Machine based Neural Network for CTR Prediction](deep_recommend/recommend/ctr/deepfm)(IJCAI 2017) `Done`
* [Deep & Cross Network for Ad Click Predictions](deep_recommend/recommend/ctr/dcn)(KDD 2017) `Done`
* [xDeepFM: Combining Explicit and Implicit Feature Interactions for Recommender Systems](deep_recommend/recommend/ctr/xdeepfm)(KDD 2018) `Done`
* [Deep Interest Network for Click-Through Rate Prediction](deep_recommend/recommend/ctr/din)(KDD 2018) `Doing`

### Match
* [Sampling-Bias-Corrected Neural Modeling for Large Corpus Item Recommendations](deep_recommend/recommend/match/google_tt) `Done`

### Other
* [Attention Is All You Need](deep_recommend/other/transformer)(NeurlPS 2017) `Done`


## Quick Start
``` shell
python run.py \
    {ctr} \
    {fm,deepfm,dcn,xdeepfm} \
    {criteo} \
    train_data_dir \
    valid_data_dir \
    test_data_dir \
    save_path \
    --version VERSION \
    --batch_size BATCH_SIZE \
    --epochs EPOCHS
```


