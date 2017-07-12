# Flask by example

a Flask app that calculates word-frequency pairs based on the text from a given URL.

Referenced from [Flask by Example - Project Setup](https://realpython.com/blog/python/flask-by-example-part-1-project-setup/) on Real Python.


## Activation before start

At Terminal, input the following codes for initiation each time:

```
$ source env/bin/activate
$ export APP_SETTINGS="config.DevelopmentConfig"
$ echo "source `which activate.sh`" >> ~/.bashrc
$ source ~/.bashrc
$ export DATABASE_URL="postgresql://localhost/wordcount_dev"
$ python manage.py runserver
```

Then run on [local server](http://127.0.0.1:5000/)
(Press CTRL+C to quit).

## Result

![](/image/web1.jpeg)

original webpage

![](/image/web2.jpeg)

try google

![](/image/web3.jpeg)

try github

