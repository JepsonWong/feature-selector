# feature-selector

Feature selector is a tool for dimensionality reduction of machine learning datasets

Refer to the [Feature Selector Usage notebook](https://github.com/WillKoehrsen/feature-selector/blob/master/Feature%20Selector%20Usage.ipynb) for how to use

The feature selector is a tool for removing features for a dataset intended
for machine learning. There are five methods used to identify features to remove:

1. Missing Values
2. Single Unique Values
3. Collinear Features
4. Zero Importance Features
5. Low Importance Features 

The `FeatureSelector` also includes a number of visualization methods to inspect 
characteristics of a dataset. 

Requires:

```
python==3.6+
lightgbm==2.1.1
matplotlib==2.1.2
seaborn==0.8.1
numpy==1.14.5
pandas==0.23.1
scikit-learn==0.19.1

```

参考网址：
资源 | 一个Python特征选择工具，助力实现高效机器学习
https://mp.weixin.qq.com/s?__biz=MzA3MzI4MjgzMw==&mid=2650744875&idx=3&sn=e7de9ce4074077d4de1f40ab24ebe51f&chksm=871aec55b06d65430e9c54085e3933735a62465aabe5cc5227de11cde40ee831db9340858920#rd
