# heroku-exploration
 just learning heroku


Tutorial extracted from https://www.youtube.com/watch?v=aUW5GAFhu6s

To verify heroku installation
```
heroku 
heroku version
heroku update
```

To login heroku (opens up browser login in 7.39.2 onwards)
```
heroku login
```

Go to your git repo
```
git init
heroku git:repo remote -a "name-of-heroku-app"
```

Make sure .gitignore looks like this
```
.env
/node_modules
```

Back to cmd line
```
git add .
git commit -am "initial commit"
git push heroku master
heroku open
```