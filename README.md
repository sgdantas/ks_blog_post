# ks_blog_post
Medium post using Kickstarter dataset

https://sgdantas1.medium.com/can-you-classify-a-kickstarter-project-by-its-goals-or-name-bf00fb9819ba


Kickstarter campaigns can make ideas into reality. We want to explore if we can categorize a kickstart project into different classes by using its goals or name. In other words, we want to answer the following questions:
- How do projects from different categories differ? Is there any category which has higher goals on average? Or longer crowdfunding duration?
- Can we classify projects based only on their goals specifications (duration, year, value)?
- Can we classify projects based only on their titles?


## Data Description
-  323750 rows (one for each project) and 17 columns (information about the project, such as launch date, goal, end date, etc)

The data can be download at https://www.kaggle.com/kemical/kickstarter-projects?select=ks-projects-201612.csv

## File Description
All the code can be found at the jupyter notebook `notebook.ipynb`.
In order to run the code, just install the libraries below.
The figure in this repo is the same figure that is presented in the blog post. It can be generated using the notebook.

## Libraries Used
- pandas
- numpy
- keras
- scikit-learn
- imbalanced-learn

## Results and Conclusions
- How do projects from different categories differ? Is there any category which has higher goals on average? Or longer crowdfunding duration?
Their differences are not very significant, some categories such as journalism and Film & Video are right-skewed distribution, but their duration and launch data are similar.
Can we classify projects based only on their goals specifications (duration, year, value)?
- These information alone are not sufficient to classify the projects, the models trained on this information only performed very poorly.
Can we classify projects based only on their titles?
- Despite being very short and brief, the titles are useful in classifying projects.

## Acknowledgments

 @bloomwatcher for providing the data, Kaggle for hosting it.
 Also, a big shoutout to all programmers that keep amazing libraries such as scikit-learn, pandas and numpy alive.



