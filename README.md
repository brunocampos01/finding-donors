# Finding Donors
![Python 3](https://img.shields.io/badge/Python-3-red.svg)
![License](https://img.shields.io/badge/Code%20License-MIT-red.svg)


<img src="references/donors.gif" align="center"/>

<br/>
<br/>

## **Data Mining Goals**
The goal is to build a model that can predict whether an individual earns more than $ 50,000.

So how **outgoing artifacts** will be a rating for which people to contact, people who earn over $ 50,000, to ask for donations.


## Datasource
- The datasource is: https://archive.ics.uci.edu/ml/datasets/Census+Income
- Kaggle post: https://www.kaggle.com/brunocampos01/adult-income-accuracy-0-90-and-fscore-0-90

## Algoritms
- Decision Tree: baseline
```
{'acc_test': 0.8190160309563295, 'f_test': 0.6180441525269113}
```

- Vector Support Machine
```
{'acc_test': 0.7966832504145936, 'f_test': 0.3057516611295681}
```

- AdaBoost
```
{'acc_test': 0.8576008844665561, 'f_test': 0.6299100804543303}
```

- AdaBoost Tunning
```
{'acc_test': 0.9055016181229774, 'f_test': 0.9070481732945361}
```

## **Better Result this Data Set !!!**
I researched the best result found in this dataset. In kaggle there are competitions using this dataset where the leader of the competition got 0.88608.
- https://www.kaggle.com/c/census-income/leaderboard
- https://www.kaggle.com/c/adult-census-income/leaderboard
- https://www.kaggle.com/c/cs189-sp16-hw5-census/leaderboard
- https://www.kaggle.com/c/test-competition-ag/leaderboard (0.88608)
- https://arxiv.org/pdf/1810.10076.pdf


## Requirements
- Python 3.6 or more
```sh
sudo apt-get install Python3
```

- Pip
```
sudo apt-get install python3-pip
```

- Python Virtual Environment
```sh
pip3 install --user virtualenv
```

- Git
```sh
pip install -r requirements.txt
```

---


<p  align="left">
<br/>
<a href="mailto:brunocampos01@gmail.com" target="_blank"><img src="https://github.com/brunocampos01/devops/blob/master/images/email.png" alt="Gmail" width="30">
</a>
<a href="https://stackoverflow.com/users/8329698/bruno-campos" target="_blank"><img src="https://github.com/brunocampos01/devops/blob/master/images/stackoverflow.png" alt="GitHub" width="30">
</a>
<a href="https://www.linkedin.com/in/brunocampos01" target="_blank"><img src="https://github.com/brunocampos01/devops/blob/master/images/linkedin.png" alt="LinkedIn" width="30"></a>
<a href="https://github.com/brunocampos01" target="_blank"><img src="https://github.com/brunocampos01/devops/blob/master/images/github.png" alt="GitHub" width="30"></a>
<a href="https://brunocampos01.netlify.app/" target="_blank"><img src="https://github.com/brunocampos01/devops/blob/master/images/blog.png" alt="Website" width="30">
</a>
<a href="https://medium.com/@brunocampos01" target="_blank"><img src="https://github.com/brunocampos01/devops/blob/master/images/medium.png" alt="GitHub" width="30">
</a>
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png",  align="right" /></a><br/>
</p>
