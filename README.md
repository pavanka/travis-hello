# travis-hello
Continuously deploy to Parse

Steps to follow:
- Set up your github repository with [travis](http://docs.travis-ci.com/user/getting-started/): you can use the `.travis.yml` in this repo as a starting point.
- Add your [Parse account key](https://parse.com/docs/js/guide#command-line-account-keys) as a [secret](http://docs.travis-ci.com/user/encryption-keys/) environment variable.

That is all there is to it!
You are now all set to continuously deploy to your Parse app on every push to github.

This is how an example [travis build](https://travis-ci.org/pavanka/travis-hello/builds/80049941) looks like.
