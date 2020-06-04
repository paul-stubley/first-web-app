# My first web app

This repo covers my first attempt at creating a web app as part of the Udacity DataScience Nanodegree.  The back end is written in python, the front end in HTML, Bootstrap and a little JS to use Plotly.

The app can be seen on [Heroku](https://pgs-worldbank-app.herokuapp.com/).

One thing of interest is that Heroku requires the app to be in its own git repo, which means pushing this repo to two different remotes.  After the Heroku repo was set up, I set up a second one on github [here](https://github.com/new), before pushing to this remote repo too.  Full instructions, and to set up pushing to both remotes at once, see [here](https://gist.github.com/rvl/c3f156e117e22a25f242).

```
git remote add github https://github.com/paul-stubley/first_web_app.git
git remote show
git push github master  
```

## Running locally (WIP)

Before pushing the app to Heroku, it can be run locally with the addition of a line in the worldbank.py file:
```
app.run(host='0.0.0.0', port=3001, debug=True)
```
