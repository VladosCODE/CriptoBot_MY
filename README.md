$ heroku create --stack cedar --buildpack https://github.com/stomita/heroku-buildpack-phantomjs.git

# or if your app is already created:
$ heroku buildpacks:add https://github.com/stomita/heroku-buildpack-phantomjs

$ git push heroku master