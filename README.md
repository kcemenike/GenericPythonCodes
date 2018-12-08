# GenericPythonCodes
This is just a repo of generic python codes, mostly housed in iPython notebooks.
***
# Prerequisite(s)
I shall do as much as I can to insert all required modules as import statements on the first line of the notebook. They are mostly popularly known modules - if you get any error while trying to run this first line, just run:
pip install [module] without the square braces
***
## Understanding Underscores in Python
The underscore is a really powerful tool. You may have seen it in your introduction to Object Oriented Programming (OOP) in Python (def __init__(self): or something like this) or in other applications, but this notebook tries to descrive a few uses of the underscore character in Python
1. Interpreter
2. Variable<br>
  a. Ignore Element in iterable<br>
  b. Ignore multiple elements in iterable<br>
  c. Loop variable / List comprehensions / Lambda functions etc<br>
3. BaseX number representation<br>
4. In OOP (object oriented programming)<br>
  a. Single leading underscore e.g. \_var<br>
  b. Single Trailing and Double trailing Underscore e.g. var\_ and var\_\_<br>
  c. Double leading underscore e.g. \_\_var<br>
  d. Reverse data mangling<br>
5. Double Leading and Trailing Underscores e.g. \_\_var\_\_
***
## Random Letter and Random String Generator using random.choice
This code generates a random letter and a random string of length n
***
## 3 ways to reverse a list
1. Using reverse()
2. Using reversed()
3. Using list slicing [::-1]
***
## Machine Learning basics using the Iris dataset
The Iris dataset was used, and the RandomForest classifier is the model. Model accuracy is 96%
***
## Pandas Melt and Pandas Pivot
How to "melt" a column (or multiple columns) into individual rows i.e. transforming variables (or features) into observations (or labels) depending on your point of view :-)
The last block of code shows how to use get method to extract data from strings in columns of a dataframe (hope this makes sense)
***
## Linear Programming with Python - [AnalyticsVidhya](#) <design by kcEmenike>

### Case Study: Creating a TED watchlist of videos

TED publishes hundreds of videos in various languages, and because there are so many videos and so little time available, I intend to maximise my use of time to watch as many videos as possible.

The objective is:
- Decide on which talk to watch (i.e. to watch or not to watch a talk) so that I watch the highest number of videos

**Constraints are such that:**
- <font color=red>Only 10 hours are available for all videos</font>
- <font color=red>I can only watch 25 videos</font>

How can I maximise the little time to make a decision on which video to watch?

*The dataset is available at [rounakbanik/ted-talks](https://www.kaggle.com/rounakbanik/ted-talks) on Kaggle*

### Table of Content
- Import items
- Get data
- Choose important data for analytics
- Create optimisation object from PuLP and define optimisation problem type (minimisation or maximisation)
- Define constraints
- Run optimisation and write results to LP file
- Convert optimisation result to readable decision-making format
- Show optimisation result
***
## A primer on Regex and NLTK (Natural Language Toolkit)
This is an introduction to Regular Expressiosn (regex) and how to use it to extract word paterns from large datasets. I've used the opportunity to also include an introduction to the Natural Language Toolkit, to show how to "tokenize" words and sentences in a dataset.
- Basic regex
- regex patterns
- Intermediate regex
- NLTK tokenization
- word tokenization
- sentence tokenization
- regex tokenization
- regex tokenization using "\w+" versus word tokenization
- Exercise: Histogram plot of word frequency per line in dataset
