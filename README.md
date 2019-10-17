# Important terms/questions to know
Check [this file](https://github.com/big-data-org-fall-2019/public_files/blob/master/importantTermsQuestions.pdf) weekly!

# Quiz Solutions
- [Quiz 1 Solution](https://github.com/big-data-org-fall-2019/public_files/blob/master/ReadingQuiz1_solution.pdf)
- [Quiz 2 Solution](https://github.com/big-data-org-fall-2019/public_files/blob/master/ReadingQuiz2_solution.pdf)
- [Quiz 3 Solution](https://github.com/big-data-org-fall-2019/public_files/blob/master/ReadingQuiz3_solution.pdf)

# Week 1 Presentations
- [Syllabus](https://github.com/big-data-org-fall-2019/public_files/blob/master/new_syllabus_2019_v1.pdf)
- [Course Intro](https://github.com/big-data-org-fall-2019/public_files/blob/master/IntroToCourse_fall2019.pdf)
- [Using OSC](https://github.com/big-data-org-fall-2019/public_files/blob/master/UsingOSC_part1_fall2019.pdf)


# Reading Assignments

This is a list of reading assignments associated with each set of topics we will cover throughout the course.  

I plan to give short "reading quizzes" which will be extremely trivial if you have at least read through (or watched, if it is a video) the material once before coming to class.

## Week 2: Data preparation and plotting.   Read/view before coming to class Tuesday August 27.
- Watch this: Using pandas: a short [pandas intro video.](https://www.youtube.com/watch?v=dcqPhpY7tWk)
The video uses the "titanic" dataset, which can be found on the scratch area on OSC at this location:
    
         /fs/scratch/PAS1585/titanic/titanic3.xls

**If** you want to go along with the video, you will need to replace the line:
    
    titanic_df = pd.read_excel('titanic3.xls','titanic3',index_col=None,na_values=['NA'])    
    
with:
    
    titanic_df = pd.read_excel('/fs/scratch/PAS1585/titanic/titanic3.xls','titanic3',index_col=None,na_values=['NA'])
    

- Read though this: A simple tutorial using pandas: https://bitbucket.org/hrojas/learn-pandas/src/master/
This has alot of lessons on pandas which will be very helpful.   At the very least, go through lesson 1.   If you have time, you can copy snippets of the code from this lesson into you own jupyter notebook to practice.

## Week 3: Regression and Classiifcation:

- **Different types of Linear Regression**
This "Quora" question helps distinguish between common linear regression tasks:  
https://www.quora.com/What-is-the-difference-between-a-multiple-linear-regression-and-a-multivariate-regression

- **Examples of different types of Linear Regression**
This "stackexchange" question does the same thing, but with specific examples:  
https://stats.stackexchange.com/questions/2358/explain-the-difference-between-multiple-regression-and-multivariate-regression

- **Issues in Linear Regression**
Also, scan through this article to get a better understanding of the subtle issues that can come up even in "simple" problems like linear regression:  
https://blog.galvanize.com/introduction-to-linear-regression/ . 
This last article goes into depth on linear regression, and highlights a different tool (statsmodels) than the one we will use in class (scikit-learn).  I won't really cover this in class but there is a lot of useful info in this last article!

- **Introduction to Regression and Classification in Machine Learning**
This gives a nice overview of what classification is, along with a simple introduction to "Support Vector Machines" (or SVMs), which is the tool we will use on Thursday.  Here is the link:  
https://www.springboard.com/blog/introduction-regression-classification-machine-learning/

- **Beyond Accuracy: Precision and Recall**
This gives an introduction to important performance metrics in classification: recall, precision, the confusion matrix, the ROC curve and AUC (the Area Under the Curve).   Here is the link:  
https://towardsdatascience.com/beyond-accuracy-precision-and-recall-3da06bea9f6c 

## Week 4: Classification
- **Video 1**
A Nice video showing how to use one-vs-all for multi-classs classification
https://www.youtube.com/watch?v=ZvaELFv5IpM

- **Video 2**
A Nice video showing the issues of one-vs-one and one-vs-all for multi-classs classification
https://www.youtube.com/watch?v=_s3z8dQX3pM

- **Evaluation of Multi-class Classificastion**
This article gives a nice overview of a number of ways to evaluate the performance of a multi-class classifier:
https://medium.com/apprentice-journal/evaluating-multi-class-classifiers-12b2946e755b

## Week 5: Decision Trees and Random Forests**
- **Overview**
This article focuses on decision trees and how they work:
https://towardsdatascience.com/decision-tree-an-algorithm-that-works-like-the-human-brain-8bc0652f1fc6

- **Builing Random Forests from Decsion Trees**
https://www.datascience.com/blog/random-forests-decision-trees-ensemble-methods

## Week 6: Logistic Regression
- **Overview**
A simple description of Logistic Regression
https://towardsdatascience.com/understanding-logistic-regression-9b02c2aec102

- **A more complex description of logistic regression**
This is more involved, along with a discussion of "odds":
https://towardsdatascience.com/logistic-regression-python-7c451928efee

## Week 7: Softmax Classification
- **Two articles which cover softmax classification**
- https://towardsdatascience.com/the-softmax-function-neural-net-outputs-as-probabilities-and-ensemble-classifiers-9bd94d75932
- https://www.harrisgeospatial.com/docs/backgroundsoftmaxregression.html
