# Twaddle

This is for keeping useful stuff

## Jupyter Notebook / Lab stuff

# Remote Access to IPython Notebooks via SSH

remote_user@remote_host$ ipython notebook --no-browser --port=8889

local_user@local_host$ ssh -N -f -L localhost:8888:localhost:8889 remote_user@remote_host

* in browser: localhost:8888

* close ssh tunel:

local_user@local_host$ ps aux | grep localhost:8889

local_user@local_host$ kill -15 id

## Bayes meets Machine Learning

* [Probabilistic Programming and Bayesian Methods for Hackers](https://github.com/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers)
* [Coursera Course Bayesian Methods for Machine Learning](https://www.coursera.org/learn/bayesian-methods-in-machine-learning/home/welcome)

