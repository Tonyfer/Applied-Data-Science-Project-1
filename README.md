# Spring 2018
# Project 1: What did the presidents say at their inauguation?

![image](figs/title.jpg)

### [Project Description](doc/)
This is the first and only *individual* (as opposed to *team*) this semester. 

Term: Spring 2018

+ Projec title: Analysis on Inauguation Speeches
+ This project is conducted by Yu Tong

+ Project summary: In this project, I firstly created a data frame[file](output/wholeinauglist.csv) which contains all information of each speech. Then I computed the tf(term frequency) of each word and did clustering analysis on the words. Then I did clustering of these speeches based on the emotions of each sentence of speech. I also did a clustering analysis based on the output of the topic model of each speech. Finally, based on tf-idf, I computed the distances of every two speech, and then define a function to get the nearest neighborhood of a chosen speech.

+ Prject report: [Project 1 Report](https://github.com/TZstatsADS/Spring2018-Project1-Tonyfer/blob/master/doc/Project1%20.nb.html)

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
