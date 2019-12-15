# 100 Days Of Code - Log

## Day 5: December 15, 2019

**Today's Progress**:
Yesterday was not possible to do my hour of coding :( I hope that this will not happen again soon. 
1. Following with _Web development 101_ of _The Odin project_ (37% completed)
   1. Going on with section _The Back End_ pending to finish exercise of fixing unit test (done 3 and 4, pending 5..6)

**Thoughts**:
1. Lost seveal time with an isue with docker and with a silly error on my code.

**Link(s) to work**:
* [Commit exercise #3 and #4](https://github.com/marc-pinyol/learn_ruby/commit/770af0f51f2430c50eb0281c91a1c5e041385564)


## Day 4: December 13, 2019

**Today's Progress**: 
1. Following with _Web development 101_ of _The Odin project_ (37% completed)
   1. Going on with section _The Back End_ pending to finish exercise of fixing unit test (done 2, pending 3..6)

**Thoughts**:
1. Work on night gives me more time and focus... but at the end I go to sleep a little bit late...
1. I'm enjoying learning Ruby.

**Link(s) to work**:
* [Commit exercise #2](https://github.com/marc-pinyol/learn_ruby/commit/d406e60a8d207c29e407b70687ab91e5d92ffffb)

## Day 3: December 12, 2019

**Today's Progress**: 
1. Following with _Web development 101_ of _The Odin project_ (37% completed)
   1. Done problems 1 to 3 of project euler.
   1. Going on with section _The Back End_ pending to finish exercise of fixing unit test (done 0..1, pending 2..6)

**Thoughts**:
* Feeling that today I wasted my time with euler problems... but feeling at same time that I need to check documentation for each command :( so... maybe I need to waste time to get confidence.
* More confortable checking and fixing unit tests. Seems that Ruby is really focused to use TDD.
* [Ruby cheat sheet and others](http://overapi.com/ruby)

**Link(s) to work**:
* [Git repo of learn_ruby](https://github.com/marc-pinyol/learn_ruby) 

## Day 2: December 11, 2019

**Today's Progress**: 
1. Fixed issues and creat repos on github.
1. Discovered/rediscovered _The Odin project_ online training web. Enrolled on _Full Stack Ruby on Rails track_.
   1. Started _Ruby programming_ > _Basic Ruby_ section
      1. Going on _Ruby building blocks_
      1. Done the full [Codecademy Introduction to Ruby](https://www.codecademy.com/courses/learn-ruby/lessons/introduction-to-ruby/) section from their [Ruby Track](https://www.codecademy.com/catalog/language/ruby).
      1. Done until lesson 5 of [Regexone](https://regexone.com/lesson/repeating_characters?)
   1. Cherry picking on _Web development 101_ (32% completed)
      1. Created silly ruby on rails car application.
      1. Git overview.

**Thoughts**: 
* It won't be easy to find 1 hour each day to finish this challenge.
* Interesting discover of [Heroku](https://www.heroku.com/). Usefull for quick deployments. [More info](https://www.theodinproject.com/courses/web-development-101/lessons/your-first-rails-application?ref=lnav#step-2-initialize-git-and-push-to-github)
* [Git cheat sheet](https://education.github.com/git-cheat-sheet-education.pdf)

**Link(s) to work**:
* [The Odin Project](https://www.theodinproject.com/)

## Day 1: December 10, 2019

**Today's Progress**: Setup RoR dev enviroment with docker. Started RoR tutorial

**Thoughts:** I'm in love with Docker, just a few lines and a clean, reproduible dev enviroment is up.

**Link to work:** 
1. [RoR docker setup](https://www.freecodecamp.org/news/painless-rails-development-environment-setup-with-docker/)
1. [RoR and Postgres docker setup](https://medium.com/better-programming/setting-up-rails-with-postgres-using-docker-426c853e8590)
1. [RoR tutorial](https://www.freecodecamp.org/news/lets-create-an-intermediate-level-ruby-on-rails-application-d7c6e997c63f/) **Come back here some day**

### Usefull commands:
**Docker**
```
docker-compose build
docker-compose run --rm --service-ports ruby_dev
```
**RoR init**
```
rails new myapp && cd myapp
bundle update && bundle install
```
**RoR start web server**
```
rails server -p $PORT -b 0.0.0.0
```
**Docker clean up**
```
docker-compose down
```