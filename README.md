![Odooku](https://cdn.rawgit.com/adaptivdesign/odooku/master/img.svg "Odooku")

[![Build Status](https://travis-ci.org/adaptivdesign/odooku.svg?branch=10.0)](https://travis-ci.org/adaptivdesign/odooku)

# Odooku
Run Odoo on Heroku, docs at [https://adaptivdesign.github.io/odooku/](https://adaptivdesign.github.io/odooku/).

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

```
$ heroku create --buildpack https://github.com/SpaceAndSunSoftware/odooku-buildpack.git#10.0
$ heroku addons:create heroku-postgresql:hobby-basic
$ heroku addons:create heroku-redis:hobby-dev
$ heroku config:set AWS_ACCESS_KEY_ID=<your_aws_key>
$ heroku config:set AWS_SECRET_ACCESS_KEY=<your_aws_secret>
$ heroku config:set S3_BUCKET=<your_s3_bucket_name>
$ git push heroku master
```
