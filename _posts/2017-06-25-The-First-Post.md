---
layout: post
title: "Dare to know"
date: 2017-06-25
---

For a long now, I have struggled to figure out how to dive into the field of machine learning that have been on my list since second year of college. I tried doing some elementary courses online but *always* lost the interest after some time. 
I realized that theoretical approach was not my thing. I liked to learn things by doing. So without further ado, let us jump to what all I will be discussing here which is basically what all I have learned in the past 3 weeks.

> **Contents**
>1. Start solving practical problems and whatever comes in your way. Google it Bro !
>2. First lesson of Machine learning that you should be familiar with.
>3. First problem I solved on [Kaggle](https://www.kaggle.com/c/titanic) and why you should too.
>4. My Solution to Kaggle problem.
>5. What changes you can do to my code for better results.
>6. Do I need to be a pro in mathematics to study ML.
>7. What do I do next!

###  1. Learning by Doing

 + Human mind learn and understand more when more senses are involved in the process hence solving problems are always a better way to learn more instead of watching videos or mugging up books.
 + I started working on Data science after I got to know about Kaggle. Which I believe provides an appropriate methodology for a head start as well as to master your skills in the field.
 + It has some starting problems which actually teaches you about basics of machine learning problems and different statistical models.
 + It is been there for a long time now, hence the community is pretty big and you can always get help very easily. There are tutorials for initial problems and then you are on your own. First three problems will really provide you a good momentum to move forward.
 
### 2. Different kinds of problems

The first thing you will read about Machine learning probably in every course or every article would be that there are mainly two kinds of problems. These are namely:

  - Supervised Learning:
     + For now we will keep it very short so you don't clutter your mind with things irrelevant. In this kind of learning you are usually given a data, an input and you are also provided with what output you are supposed to evaluate. 
     + This is like you are given some medical data and on the basis of this information you have to tell for an example what kind of diabetes your patient is suffering from.
     + This is further of two kinds :
       1. Classification(Categorical/Qualitative) - In this, you divide your output in different categories. So you *classified it into one of the categories*. Like in the above mentioned diabetes example, your answer would be Type 1 or Type 2.
       2. Regression(Quantitative) - In this, on the basis of your data you have to provide an absolute number, *a quantity*. Like predicting price of a house which can vary from 10k to 50k depending upon

  - Unsupervised Learning : As the name suggests, we are unaware of what kind of specific output we should evaluate from the data. So we try to draw as many inferences/interpretations we can from the data. One of the very well know methods is cluster analysis.

As you have become aware of basic terminology we can move further.

### 3. Ahhh!  Titanic
 + The first problem you will solve on Kaggle will be a simple classification problem where you are supposed to predict whether a person survived or not when the ship sank. There are some features given to you and right now I would like to save you the suspense.
This will be very easy and you will develop basic understanding of how ML problems are solved. It will help you get over all the misconceptions you had uptil now.

*Without further ado, lets talk something technical now.*

1. The first choice that you will have to make would be choosing between Python or R to code. I personally chose Python because I was already familiar with it. I will save the research part for you to choose what works for you best but you can take help from this [link](https://www.quora.com/Which-is-better-for-data-analysis-R-or-Python).
2.  If you chose python like I did, you have to install many dependencies time to time. It is better to work using Anaconda, it is if I have to give a very simple definition collection of many libraries of Python and R. So you don't have to install different libraries individually later. Here is the [link](https://www.continuum.io/downloads) to download it and get started. You might want to invest some time into learning what virtual environments are if you are going to use it. 
3. *Where do I code?* 
    We write our code in a jupyter notebook, I will be sharing a link to a video series later that will get you started. You can simply start from terminal by writing.
	
     ```
	 jupyter notebook 
     ```

      After this a browser tab will open and you can create a new notebook and start using it.

*Things I learned while solving this problem*

 1. I just read about some very basic libraries and their common functions but it really provided me a very nice momentum and it generated a curiosity to learn more about the field. I also studied some Maths in the process which was very exciting.
 2.  I started with reading about **Pandas** which is a python data manipulation library. It has lot of basic and complicated functions, though I have covered only easier ones for now. 
     + You should start with reading about pandas data structures which are namely Series and Dataframe. Former is just like a 1D array while latter is a 2D. 
       ```
	   import pandas as pd
	   s = pd.Series(data, index=index)
       ```
     + This is how you initialize a Series where *data* is the data you want to feed in it. Where as for Dataframes you use something like this.
  	   ```
  		df = pd.DataFrame(d)
  	   ```
       where *d* can be a collection of Series.
    
       You might want to read more about Pandas from this official 10 minutes [introduction](http://pandas.pydata.org/pandas-docs/version/0.15.2/10min.html)  and also about [data structures](https://pandas.pydata.org/pandas-docs/stable/dsintro.html).

 3.  I then moved forward to *Matplotlib* which is a python 2D plotting library. Machine Learning is just applied Mathematics hence situations will come where you have to visualize your data or at least plot one variable w.r.t. other. For all this *Matplotlib comes in handy*. You will realize with time that knowing your data is an important phase while you are solving a problem. Without it, trying to build a model will be very difficult.
 
