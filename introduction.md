# Introduction

## NLP Problem Investigation

1. Pick one NLP task from the list below.
- POS tagging: noun, verb, adjective, other.
- NER: 人, 時, 地, 物, other.
- Sentiment analysis: positive, negative, neutral.

2. Answer the following questions.
- What is the problem we are trying to solve?
- What does the training data look like?
- What is your plan to handle the data? 
  - Where to get the data?
  - How to get the data?
  - How to store the data?
  - What preprocessing do we need to do?
- What are the common approaches (algorithm/model) to solve this problem? 
  - Note: You will need to pick one approach and try it in the latter stage.

3. Make a presentation slide and present your findings.

## Setup a project in Github.
We will use github to manage the project. So you need to set up
a project in GitHub.

You can checkout [this tutorial](https://www.rs-online.com/designspark/github-nvidia-cn).

You also need to understand some basic git commands.
- `clone`
- `add`
- `commit`
- `checkout`
- `status`
- `log`
- `branch`

## Managing Python Dependencies
You need to provide a `requirements.txt` to store all the python package you use.

When you install python packages, it is recogmended to use virtual environment.
By doing this, the packages you downloaded will not affect the system and other project.

Some common tools to achieve this are:
- [Python's native venv](https://docs.python.org/zh-tw/3/tutorial/venv.html)
- Anaconda/conda
