### devdocs
---
https://devdocs.io/

https://github.com/freeCodeCamp/devdocs

```sh
rackup
rackup --help

thor docs:list
thor docs:download
thor docs:manifest
thor docs:generate
thor docs:page
thor docs:package
thor docs:clean

thor console
thor console:docs

thor test:all
thor test:docs
thor test:app

thor assets:compile
thor assets:clean

git clone https://github.com/freeCodeCamp/devdocs.git && cd devdocs
docker build -t thibaut/devdocs .
docker run --name devdocs -d -p 9292:9292 thibaut/devdocs

git clone https://github.com/freeCodeCamp/devdocs.git && cd devdocs
gem install bundler
bundle install
bundle exec thor docs:download --default
bundle exec rackup
```

```
```

```
```

