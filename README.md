# heroku-buildpack-gb

A [Heroku Buildpack](https://devcenter.heroku.com/articles/buildpacks) for [Go](https://golang.org/) projects using the gb build tool](http://getgb.io/).

This buildpack is based on [heroku-buildpack-go](https://github.com/heroku/heroku-buildpack-go) and of course [heroku-buildpack-gb](https://github.com/sendwithus/heroku-buildpack-gb) but this one actually uses gb for compiling/building.

It installs gb, and calls `gb build` on the project.

Should work with any project that currently using gb.

