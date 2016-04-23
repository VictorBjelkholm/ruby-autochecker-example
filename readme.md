## ruby-autochecker-example

This is a example on how you can run autochecker on various CI services.

Badges indicated with `master` should be passing 100%

Badges indicated with `master-fail` should be passing only on 2.3 and fail on the rest

## CI services that currently runs these tests and is supported by autochecker

CircleCI:

master:

[![Circle CI](https://circleci.com/gh/VictorBjelkholm/ruby-autochecker-example.svg?style=svg)](https://circleci.com/gh/VictorBjelkholm/ruby-autochecker-example)

master-fail:

[![Circle CI](https://circleci.com/gh/VictorBjelkholm/ruby-autochecker-example/tree/master-fail.svg?style=svg)](https://circleci.com/gh/VictorBjelkholm/ruby-autochecker-example/tree/master-fail)

Semaphoreci:

master:

[![Build Status](https://semaphoreci.com/api/v1/victorbjelkholm/ruby-autochecker-example/branches/master/badge.svg)](https://semaphoreci.com/victorbjelkholm/ruby-autochecker-example)

master-fail:

[![Build Status](https://semaphoreci.com/api/v1/victorbjelkholm/ruby-autochecker-example/branches/master-fail/badge.svg)](https://semaphoreci.com/victorbjelkholm/ruby-autochecker-example)

Travis CI:

master:

[![Build Status](https://travis-ci.org/VictorBjelkholm/ruby-autochecker-example.svg?branch=master)](https://travis-ci.org/VictorBjelkholm/ruby-autochecker-example)

master-fail:

[![Build Status](https://travis-ci.org/VictorBjelkholm/ruby-autochecker-example.svg?branch=master-fail)](https://travis-ci.org/VictorBjelkholm/ruby-autochecker-example)

## CI services that is left to confirm or fix bugs in

* https://codeship.com/
* https://snap-ci.com/
* http://wercker.com/
