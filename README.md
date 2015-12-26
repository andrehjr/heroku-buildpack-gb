# heroku-buildpack-gb

A [Heroku Buildpack](https://devcenter.heroku.com/articles/buildpacks) for [Go](https://golang.org/) projects using the gb build tool](http://getgb.io/).

This buildpack is based on [heroku-buildpack-go](https://github.com/heroku/heroku-buildpack-go) and of course [heroku-buildpack-go](https://github.com/sendwithus/heroku-buildpack-gb) but this one actually uses gb for compiling/building.

Experimental project.

#### Example Project Structure
```
root/
  src/
    app/
      main.go
  vendor/
    github.com/...
```

#### Example Procfile
```yaml
web: main
```