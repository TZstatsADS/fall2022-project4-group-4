# Project 4: Machine Learning Fairness

### [Project Description](doc/project4_desc.md)

Term: Fall 2022

+ Team 4
+ Project title: Learning fair representations (LFR) vs. Fairness-aware Classifier with Prejudice Remover Regularizer (PR)
+ Team members
	+ Leon, Alix 
	+ Li, Xinyun 
	+ Cai, Jinyang 
	+ Podias, John 
	+ Tu, Zhongcheng 
+ Project summary: In this project, we implement two algorithms: Learning fair representations (LFR) and Fairness-aware Classifier with Prejudice Remover Regularizer (PR) on the compas-two-years dataset. This dataset contains information on defendants in Broward County from 2013 and 2014. Our analysis is limited to data for Caucasian and African-American defendants. We compare two algorithms' performance on the dataset by accuracy, discrimination and calibration based on the target variable, two_year_recid, which indicates if a defendant was arrested again within two years.
	
**Contribution statement**: Xinyun Li codes implement the LFR algorithm. Alix Leon and Jingyang Cai code and implement the PR algorithms. Jinyang Cai designed the evalutaion metrics and perform the data cleaning with John Podias. Xinyun Li and Jingyang Cai wrote the presentation files together.

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
