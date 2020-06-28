# Images2Poem: Generating Chinese Poetry from Image Streams
Data for the paper [**Images2Poem: Generating Chinese Poetry from Image Streams**](https://dl.acm.org/doi/10.1145/3240508.3241910).

## Downloads
Link on [**BaiduYun**](https://pan.baidu.com/s/1r5e4z0CtnH0AfAMXPOhNXg). Password: op1m.

The download link contains training, testing image data, human evaluation data, and data for cross-lingual embeddings. 
The training image data `IMAGE2POEM_TRAIN.zip` contains 200k images collected from [Baidu search engine](http://image.baidu.com/), with 600+ attribute words that frequently appear in Chinese poetry data (such as "宫殿(palace) and "扁舟(tiny boat)". Note that although we tried some noise filtering process, the dataset still contains a lot of noise. However, the quality of the generated poems trained on the data are quite acceptable.
The testing image data `IMAGES2POEM_TEST.rar` contains 50 image streams focusing on natural scenery collected from websites like [Ctrip](http://Ctrip.com) and [Mafengwo](http://Mafengwo.cn). We use 25 of them for human evaluation.
Human evaluation data `human_evaluation.rar` contains the questionnaires (in Chinese) for human evaluation. Poems generated from six models (three baselines and three model variants for ablation studies) are shown in random order.

For poetry data used for Images2Poem, please refer to the data of [RNNPG](https://github.com/XingxingZhang/rnnpg). There are larger recently proposed poetry data, including [this project](https://github.com/chinese-poetry/chinese-poetry).
We also utilize MSCOCO data and wikipedia data for training. Please refer to the paper for the details. The `cross-lingual/` folder provides a dictionary from ancient Chinese words to modern chinese words, a Chinese-English dictionary, and pretrained bi-CCA cross-lingual word vectors trained on English, Chinese, poetry ancient Chinese corpus and these dictionaries.

`images2poem.zip` has part of codes for the project. If you are interested, please read the README file in it.

## Reference
If you found our work useful, please consider citing:
```
@InProceedings{Images2Poem,
author = {Liu, Lixin and Wan, Xiaojun and Guo, Zongming},
title = {Images2Poem: Generating Chinese Poetry from Image Streams},
year = {2018},
booktitle = {Proceedings of the 26th ACM International Conference on Multimedia},
pages = {1967–1975},
}
```



