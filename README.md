# wpl-car-sales

## server
git push heroku shivam:master
https://stark-peak-39857.herokuapp.com

## client
git push heroku-client `git subtree split --prefix client/car-sales shivam`:master
heroku config:set SERVER_API=https://stark-peak-39857.herokuapp.com --app agile-brook-17309