# AskDanaher
Web app to return John Danaher's social media posts based on keyword inputs. 

## Table of Contents
* [References](#refs)
* [Requirements](#libs)
* [Summary](#summary)


## References <a class="anchor" id="refs"></a>
* [Deploying a Python Flask app on Heroku - John Kagga](https://medium.com/the-andela-way/deploying-a-python-flask-app-to-heroku-41250bda27d0)
* [Build a Simple Web App - Garrett Eichhorn](https://towardsdatascience.com/build-a-simple-web-app-with-github-pages-flask-and-heroku-bcb2dacc8331)


## Requirements <a class="anchor" id="libs"></a>
* [wordcloud](https://pypi.org/project/wordcloud/)
* [itertools](https://docs.python.org/2/library/itertools.html)
* [collections](https://docs.python.org/3/library/collections.html)
* [gensim](https://radimrehurek.com/gensim/)
* [NLTK](https://www.nltk.org/)
* [pandas](https://pandas.pydata.org/)
* [Matplotlib](https://matplotlib.org/)
* [seaborn](https://seaborn.pydata.org/)
* [NumPy](https://numpy.org/)
* [json](https://docs.python.org/3/library/json.html)
* [functools](https://docs.python.org/3/library/functools.html)
* [Heroku](https://www.heroku.com/)
* [Flask](https://flask.palletsprojects.com/en/1.1.x/)

## Summary <a class="anchor" id="summary"></a>
This project scrapes John Danaher's social media posts. The post database is updated weekly. The posts are converted into a NLP weights dictionary to use for keyword filtering and relevance sorting. The project is available [HERE]() as a web app using Flask and Heroku.
![offensewordcloud](/images/offensewordcloud.png)
![defensewordcloud](/images/defensewordcloud.png)


    
    

