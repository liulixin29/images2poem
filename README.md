# Images2Poem: Generating Chinese Poetry from Image Streams
Data for the paper [**Images2Poem: Generating Chinese Poetry from Image Streams**](https://dl.acm.org/doi/10.1145/3240508.3241910).

## Downloads
Link on [**BaiduYun**](https://pan.baidu.com/s/1r5e4z0CtnH0AfAMXPOhNXg). Password: op1m.

The download link contains training, testing image data and human evaluation data. 
The training image data contains 200k images collected from [**Baidu search engine**](http://image.baidu.com/), with 628 attribute words that frequently appear in Chinese poetry data (such as "宫殿(palace) and "扁舟(tiny boat)". Note that although we tried some noise filtering process, the dataset contain a lot of noise. However, the quality of the generated poems trained on the data are quite acceptable.
The testing image data contains 50 image streams focusing on natural scenery collected from websites like [**Ctrip**](http://Ctrip.com) and [**Mafengwo**](http://Mafengwo.cn). We use 25 of them for human evaluation.
Human evaluation data contains the questionnaires (in Chinese) for human evaluation. Poems generated from six models (three baselines and three model variants for ablation studies) are shown in random order.

For poetry data used for Images2Poem, please refer to the data of [**RNNPG**](https://github.com/XingxingZhang/rnnpg). Other recently proposed poetry data are much larger, including [**this project**](https://github.com/chinese-poetry/chinese-poetry).
We also utilize MSCOCO data and wikipedia data for training. Please refer to the paper for the details.

## Citation
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



