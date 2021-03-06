PunchClock Server
=======

Provides a set of endpoints for the [PunchClock](https://github.com/panicinc/PunchClock) iOS app as well as a [Status Board](https://panic.com/statusboard/)-compatible In/Out panel.

Setup
-----

Let's assume you've gone through the basic [heroku setup steps](https://devcenter.heroku.com/articles/quickstart) and are ready to deploy an application.

The server is designed to run with a [Postgres](https://devcenter.heroku.com/articles/heroku-postgresql) database and the [ZeroPush](https://devcenter.heroku.com/articles/zeropush) notification service. To get it running for testing you'll need to install some ruby gems and customzie your local enviroment.

- `$ cp dotenv.sample .env`
- `$ gem install bundler; bundle install`

#### Images
Put your people images in the public folder and name them the same as the names used in the app.


Contributing
------------

Feel free to fork and send us pull requests

Bug Reporting
-------------

**PunchClockServer is an unsupported, unofficial Panic product.** If you can't contribute directly, please file bugs here.

