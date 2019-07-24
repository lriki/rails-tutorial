# README


### Note:

```
choco install heroku-cli
choco install chromedriver
```

```
createdb -U postgres sample_app_development
```

```
heroku config
```

```
heroku run rails db:migrate
heroku ps:restart
heroku open
```

```
git push heroku master
heroku open
```


### rails test で "DEPRECATED chromium-webdriver" とかエラー出る
https://stackoverflow.com/questions/55970418/capyabra-selenium-chrome-driver-settings

### rails test で失敗する
test 環境用の DB 作ってなかった。

```
createdb -U postgres sample_app_test
```


This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
