<img src='https://www.salesforce.org/wp-content/uploads/2021/02/uva-university-of-virginia-logo.png' width=300 align='center'/>

# Machine Learning for Virginia (ML4VA)

## Purpose
The main objective of Machine Learning for Virginia ([ML4VA](https://www.cs.virginia.edu/~nn4pj/teaching#ml4va)) is to prepare students to apply what they learn in machine learning courses to a real-world scenario, especially one that exists from the UVA local community to the state of Virginia at large. Through this 12-week project, students will be working in a team of three to use machine learning to make a meaningful contribution to the well-being of the state of Virginia and its residents. The project topic can be on various issues in education, economy, environment, healthcare, transportation, energy, finance, public safety, and culture.

## Project Description
This project analyzes offensive language on the internet through the lens of Machine Learning. We use Natural Language Processing (NLP) models to categorize text commentary taken from social media websites into two categories: offensive language and non-offensive language.

## Dataset
<img src="https://upload.wikimedia.org/wikipedia/commons/7/7c/Kaggle_logo.png" alt="kaggle" class="center" width="100">

We sourced our data from [Kaggle](https://www.kaggle.com/); specifically from the [Detecting Insults in Social Commentary Competition](https://www.kaggle.com/c/detecting-insults-in-social-commentary/data?select=train.csv). This is a single-class classification problem. The label is either 0 meaning a neutral comment, or 1 meaning an insulting comment (neutral can be considered as not belonging to the insult class).

## Results Preview

<h3>&nbsp;&nbsp;&nbsp;&nbsp;Multinomial Naive-Bayes Classifier&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Support Vector Machine</h3>
<span>
  <img src="https://github.com/iainmuir6/Machine-Learning-for-Virginia/blob/main/output/mnbc.png" alt="mnbc" class="center" width="400">
  <img src="https://github.com/iainmuir6/Machine-Learning-for-Virginia/blob/main/output/svm.png" alt="mnbc" class="center" width="400">
</span>
<h3>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Nueral Network I&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Nueral Network II</h3>
<span>
  <img src="https://github.com/iainmuir6/Machine-Learning-for-Virginia/blob/main/output/nn1.png" alt="mnbc" class="center" width="400">
  <img src="https://github.com/iainmuir6/Machine-Learning-for-Virginia/blob/main/output/nn2.png" alt="mnbc" class="center" width="400">
</span>

## Credits
* Kyle Cheng (kwc9ap)
* Boris Topalov (bnt4yb)
* Final Project for [CS 4774](https://www.cs.virginia.edu/~nn4pj/teaching), Machine Learning, taught by [Rich Nguyen](http://www.cs.virginia.edu/~nn4pj/).
