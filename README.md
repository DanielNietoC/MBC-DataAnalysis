# MBC-DataAnalysis
 This is the repository for the materials of the Data Analysis class at the UPF Masters for Brain & Cognition taught by Klaus Wimmer & Alex Hyafil, largely using material from Albert Compte.

 
 # Coding in Python
 
 Why should a cognitive psychologist / neuroscientist learn how to code? See the arguments in these different sources:
 - "The next generation of neuroscientists needs to learn how to code" [article from Neuron journal](https://doi.org/10.1016/j.neuron.2021.12.001)
 - "Why it's important to learn to code in contemporary biology?" [article from Wire](https://www.wired.com/2017/03/biologists-teaching-code-survive/?mbid=nl_31817_p4&CNDID=49340875)
 - "Why every (psychology) student should learn to code" [blog post](https://computingforpsychologists.wordpress.com/2012/01/13/why-every-psychology-student-should-learn-to-code/)

You can brush up your Python skills by following one (or some) of these suggested Python tutorials:
 - [Introduction to Python](https://cogs18.github.io/intro.html) from the Department of Cognitive Science of UC San Diego
 - [Python for Everybody Specialization](https://www.coursera.org/specializations/python) (free Coursera course starts Dec 20)
 - [LearnPython.org](https://www.LearnPython.org)
 - [Datacamp - Intro to Python for Data Science](https://campus.datacamp.com/courses/intro-to-python-for-data-science/)
 - Python training at the [Neuromatch Academy](https://academy.neuromatch.io/about): [Day 1](https://compneuro.neuromatch.io/tutorials/W0D1_PythonWorkshop1/student/W0D1_Tutorial1.html) and [Day 2](https://compneuro.neuromatch.io/tutorials/W0D2_PythonWorkshop2/student/W0D2_Tutorial1.html), tutorials with videos 
- Introductory material from the ["Advanced Scientific Programming in Python" summer school](https://aspp.school/wiki/introductory_material)
- If your master's project relies heavily on programming or you continue along with a PhD, we strongly recommend reading quietly through Patrick Mineault's wonderful [Good Research Code Handbook](https://goodresearch.dev)

## Setting up your computer to run Python
In this class we will run our analyses by coding them in Python. We will do this both in class and at home, so we need to have proper access to these programs. There are three different options: in the first one code will be run locally on your computer, while the second and third option use cloud computing (so no installation of any software on your computer):
- If you will be using your own laptop at all times, you may want to install Python locally. The best option is to install the [Anaconda package](https://www.anaconda.com/products/distribution), which comes with everything we need for the class.
- The **preferred option** for running Python codes in the cloud is using Google Colab, which is a free service. Just click on the "Google Colab" icon next to an assignment to open it in Google Colab (you can also go to the [Google Colab homepage](https://colab.research.google.com/) and import a notebook from your computer or with an url.
- Alternatively, you can run Python codes in the cloud using Anaconda in [myapps.upf.edu](https://myapps.upf.edu/). This might be faster than on a slow local computer as it runs on UPF servers. You get a detailed explanation of this service [here](https://guiesbibtic.upf.edu/myapps/inici). When you access MyApps you will be able to upload and download files from your MyCloudFiles folder. Then, when you open a Jupyter Notebook from within a session of Anaconda in MyApps you will be working on that MyCloudFiles folder, so you can work and keep your code organized there. You will have everything in the cloud and accessible from any computer anywhere.

## Statistics tutorials
You can also refresh your statistics with the following online courses:
 - [Intro to statistics](https://www.udacity.com/course/intro-to-inferential-statistics--ud201https://www.udacity.com/course/intro-to-statistics--st101)
 - [Intro to inferential statistics](https://www.udacity.com/course/intro-to-inferential-statistics--ud201)
 - [Intro to descriptive statistics](https://www.udacity.com/course/intro-to-descriptive-statistics--ud827)
 - [Statistics tutorial](https://compneuro.neuromatch.io/tutorials/W0D5_Statistics/chapter_title.html) at the [Neuromatch Academy](https://academy.neuromatch.io/about), tutorials with videos

## Assignment 0: coding in Python

- First steps: [Notebook](A0_PythonBasics/Assignment0.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/wimmerlab/MBC-DataAnalysis/blob/main/A0_PythonBasics/Assignment0.ipynb) Solutions [Notebook](A0_PythonBasics/Assignment0_solutions.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/wimmerlab/MBC-DataAnalysis/blob/main/A0_PythonBasics/Assignment0_solutions.ipynb)
- Second steps (optional!):[Notebook](A0_PythonBasics/Assignment0-2.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/wimmerlab/MBC-DataAnalysis/blob/main/A0_PythonBasics/Assignment0-2.ipynb) Solutions [Notebook](A0_PythonBasics/Assignment0-2_solutions.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/wimmerlab/MBC-DataAnalysis/blob/main/A0_PythonBasics/Assignment0-2_solutions.ipynb)
- [Slides from the first class](slides/intro.pdf)

## Assignment 1: descriptive statistics, parametric vs non-parametric methods & linear regression
In this assignment, we will see:
- how to visually inspect experimental data
- how to characterize experimental data using descriptive statistics
- how to perform a simple statistic test using either a parametric (T-test) or non-parametric (shuffling) method
- how to assess the impact of an experimental factor on our experimental measurement using linear regression
- how to take into account the hetereogeneity of our sample population using linear mixed models

<div class="alert alert-block alert-warning">
<b>Preparing for this assignment:</b> 

The following resources will help you to get ready to complete this assignment. 
<ul>
    <li>Watch <a href="http://youtu.be/5q-Ws4y8JE4" target="_blank">this video</a> (here the <a href="https://www.cmrr.umn.edu/~kendrick/statsmatlab/StatsLecture2Slides_Hypothesis.pdf" target="_blank">slides</a>) only until time stamp 23:08 (stop right after permutation tests) in order to learn about:</li>
    <ul>
        <li>the logic of t-tests to test the hypothesis that two samples have the same mean</li>
        <li>the non-parametric equivalent in permutation tests. Make sure you understand this logic</li>
    </ul>
    <li>Watch <a href="https://www.youtube.com/watch?v=KsVBBJRb9TE" target="_blank">this video</a> and then follow with <a href="https://www.youtube.com/watch?v=xIDjj6ZyFuw" target="_blank">this video</a> to learn the concepts about simple linear regression</li>
    <li>For a complementary look on linear regression that put its into the more general framework of model fitting, watch <a href="https://www.youtube.com/watch?v=9JfXKmVB6qc" target="_blank">this video</a> (until 15:10) and then follow with <a href="https://www.youtube.com/watch?v=HumajfjJ37E" target="_blank">this video</a> (linear regression by minimizing squared errors) and <a href="https://www.youtube.com/watch?v=8mpNmzLKNfU" target="_blank">this one</a> (linear regression by maximizing likelihood). These are parts of the material for Model Fitting day which are accessible <a href="https://compneuro.neuromatch.io/tutorials/W1D2_ModelFitting/chapter_title.html" target="_blank">here</a>. </li>
    <li> (Very optional) See <a href="https://www.cns.nyu.edu/~eero/NOTES/leastSquares.pdf" target="_blank">these notes</a> from Eero Simoncelli (NYU) if you want to delve more into the mathematics related to linear regression</li>
    <li>Read <a href="https://doi.org/10.1152/jn.00362.2015" target="_blank">this paper</a> (focussing on Experiment 2) to understand the logic of the experimental data that we will analyze</li>
</ul>
</div>

- First part: descriptive statistics and hypothesis tests [Notebook](A1_LinearRegression/Assignment1A.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/wimmerlab/MBC-DataAnalysis/blob/main/A1_LinearRegression/Assignment1A.ipynb)

- Second part: linear regression [Notebook](A1_LinearRegression/Assignment1B.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/wimmerlab/MBC-DataAnalysis/blob/main/A1_LinearRegression/Assignment1B.ipynb) 


## Assignment 2: psychometric curves, logistic regression and interaction terms

**In this assignment, we will see how to study binary decisions:**
- using the **psychometric curve** to describe how decisions depend on a single stimulus feature
- using **logistic regression** (one form of Generalized Linear Model) to describe how decisions depend on a set of experimental factors (and their **interactions**)
- using **generalized linear mixed models** (GLMM) to capture the heterogeneity of behavior across the population 

<div class="alert alert-block alert-warning">
<b>Preparing for this assignment:</b> 

The following resources will help you to get ready to complete this assignment. 
<ul>
    <li>Watch <a href="https://www.youtube.com/watch?v=yIYKR4sgzI8" target="_blank">this video</a> to have a quick overview of linear and logistic regression, a form of generalized linear regression, and how they compare. You should learn: </li>
    <ul>
        <li>what type of data is appropriate for logistic regression modeling</li>
        <li>how we can decide among candidate predictors using regression</li>
        <li>regression fit methods: least-squares versus maximum likelihood</li>
    </ul>
    <li>Watch <a href="https://www.youtube.com/watch?v=vN5cNN2-HWE" target="_blank">this video</a> in order to understand the parameters of a logistic regression:</li>
    <ul>
        <li>concept of link function (<b>logit</b> for logistic regression)</li>
        <li>how to interpret the intercept and slope parameters of predictors in a logistic regression</li>
    </ul>
        <li>Watch <a href="https://www.youtube.com/watch?v=HSHcIHMxhbE" target="_blank">this video</a> to see a step-by-step construction of a multiple linear model with interaction terms. Make sure you understand the logic of the interaction explained in the last half of the video. Take the exercise at the end of the video by stopping the video while you make your calculations.</li>
    <li>Browse <a href="https://en.wikipedia.org/wiki/Interaction_(statistics)" target="_blank">this Wikipedia page</a> about interactions. It focuses a lot on ANOVAs, which we do not plan to address directly, so do not focus too much on that. I suggest reading the introduction, the <i>"In regression"</i> subsection and the <i>"Examples"</i> subsection. </li>
    <li>OPTIONAL: If you were wondering why we skip ANOVAs and are happy just with linear models, ANOVA being such a popular statistical tool, <a href="https://eigenfoo.xyz/tests-as-linear/" target="_blank">here</a> is a more advanced Python document for you to make the point that linear models are a very general framework, which includes many of the classical statistical tests (also ANOVAs). We can run all our tests with linear models!!
</ul>
</div>

- **First part**: psychometric curves and maximum likelihood estimation [Notebook](A2_LogisticRegression/Assignment2A.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ahyafil/MBC-DataAnalysis/blob/main/A2_LogisticRegression/Assignment2A.ipynb) 
