## circle_ci_test

[![CircleCI](https://circleci.com/gh/msrks/circle_ci_test.svg?style=svg)](https://circleci.com/gh/msrks/circle_ci_test)

practice of CircleCI: develop Flaskr app. using CircleCI

- https://github.com/pallets/flask/tree/master/examples/flaskr
- https://circleci.com/docs/2.0/project-walkthrough/

### The microblogging named Flaskr does the following things:

1. Let the user sign in and out with credentials specified in the configuration. Only one user is supported.
2. When the user is logged in, they can add new entries to the page consisting of a text-only title and some HTML for the text. This HTML is not sanitized because we trust the user here.
3. The index page shows all entries so far in reverse chronological order (newest on top) and the user can add new ones from there if logged in.

### Usage

```
$ cd circle_ci_test
$ pip install --editable .
$ export FLASK_APP=flaskr.flaskr
$ export FLASK_DEBUG=true
$ flask initdb
$ flask run
```

### Test

```
$ python setup.py test
```
