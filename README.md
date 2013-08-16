# Learning R

Start by using RStudio.

We used R previously, in the titanic competition, `Code/Courses/coursera-datascience/titanic`
for which we were using

    export R_LIBS=/Users/daniel/Downloads/R_LIBS

## Importing CSV Files

    list.files(baseDir,recursive=TRUE)
    dat.csv <- read.csv("/Users/daniel/Downloads/Kaggle-BelkinEnergyDisaggregation/csv/H4_CSV/Tagged_Training_07_26_1343286001/TaggingInfo.csv", header=FALSE)
    dat.csv <- read.csv("/Users/daniel/Downloads/Kaggle-BelkinEnergyDisaggregation/csv/H4_CSV/Tagged_Training_07_26_1343286001/TaggingInfo.csv", header=FALSE)

## Importing matlab files - NOT
This is for Kaggle Belkin Energy Disaggregation

    install.packages("R.matlab")
    require('R.matlab')
    ati=readMat('/Users/daniel/Downloads/Kaggle-BelkinEnergyDisaggregation/H1/AllTaggingInfo.mat')

## Tried these    

* [Intro Slides](http://www.ats.ucla.edu/stat/r/seminars/intro.htm)


## Will check these out

[R tutorial (site/book)](http://www.r-tutor.com/)

[Basic R youtube tutorial (by Tiago Zortea)](http://www.youtube.com/playlist?list=PLFf3DKi9pkFQceRv27Wm_EtNx6QOiCpOY&feature=edit_ok)

[Another Youtube tutorial (by Gordon Davis)](http://www.youtube.com/user/GordonAnthonyDavis/videos)

See this [post](http://www.kaggle.com/c/titanic-gettingStarted/forums/t/3356/very-basic-r-program/18329).

And this [page on the `caret` library](http://caret.r-forge.r-project.org/)

And this post on the forum: [Basic R Code](http://www.kaggle.com/c/titanic-gettingStarted/forums/t/3702/basic-r-code)

[article on a similar dataset](http://rforwork.info/2012/12/23/binary-classification-a-comparison-of-titanic-proportions-between-logistic-regression-random-forests-and-conditional-trees/). The [dataset is from here](http://biostat.mc.vanderbilt.edu/twiki/bin/view/Main/DataSets)

[Another Kaggler](https://github.com/mattdelhey/kaggle-titanic/blob/master/1-clean.R)

[Article on Tuning with caret](http://rss.acs.unt.edu/Rdoc/library/caret/html/train.html)
