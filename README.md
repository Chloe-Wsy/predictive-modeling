# Project: Dogs, Fried Chicken or Blueberry Muffins?
![image](figs/chicken.jpg)
![image](figs/muffin.jpg)

### [Full Project Description](doc/project3_desc.md)

+ Project summary: In this project, I used several feature extraction such as LBP feature extraction, HoG feature extraction methods and classification models(SVM, Random Forest, Xgboost, Logistic Regression, GBM) from machine learning to recogonize whether there is a dog, chicken or blueberry muffin in the image. I have a baseline model which is GBM + SIFT and we are trying to develop a way that improve the baseline model most. We also tried RGB for feature extraction and CNN for both feature extraction and classification. However, there are grayscale images that RGB could not deal with; and CNN takes a long time to train the model. I finally use xgboost + HoG as our winners. They achieve a accuracy rate of about 80% and takes a short time to train (less than 1 minute).
	

Following [suggestions](http://nicercode.github.io/blog/2013-04-05-projects/) by [RICH FITZJOHN](http://nicercode.github.io/about/#Team) (@richfitz). This folder is orgarnized as follows.

```
proj/
├── lib/
├── data/
├── doc/
├── figs/
└── output/
```

Please see each subfolder for a README file.
