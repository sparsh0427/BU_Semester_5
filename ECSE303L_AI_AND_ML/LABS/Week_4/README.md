## Challenge Week 4
In its vanilla form logistic regression is used to do binary classification. Multiclass classification with logistic regression can be done either through the one-vs-rest scheme in which for each class a binary classification problem of data belonging or not to that class is done, or changing the loss function to cross- entropy loss.

Decision trees are constructed via an algorithmic approach that identifies ways to split a data set based on different conditions. It is one of the most widely used and practical methods for supervised learning. Decision Trees are a non-parametric supervised learning method used for both classification and regression tasks.

### How to use

#### Colab
Open task 1 notebook in colab: &emsp;[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/DeepConnectAI/challenge-week-4/blob/master/task_1_multiclass_logistic.ipynb)<br>
Open task 2 notebook in colab: &emsp;[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/DeepConnectAI/challenge-week-4/blob/master/task_2_decision_tree_viz.ipynb)

How to get the data using wget?
```python
# Obsesity Dataset for Task 1
!wget https://github.com/DeepConnectAI/challenge-week-4/raw/master/data/obesity_data.csv
```
#### Local
This is not a huge repository therefore can easily be downloaded.
```bash
# Clone the repository
$ git clone https://github.com/DeepConnectAI/challenge-week-4.git

# Go to project directory
$ cd challenge-week-4

# Open up the jupyter notebook if installed
$ jupyter notebook
```
