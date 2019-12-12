# 100 Days Of Code - Log

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

### Day 2: December 11, 2019

**Today's Progress**: 
1. Fixed issues and creat repos on github.
1. Discovered/rediscovered _The Odin project_ online training web. Enrolled on _Full Stack Ruby on Rails track_.
   1. Started _Ruby programming_ > _Basic Ruby_ section
      1. Going on _Ruby building blocks_
      1. Done the full [Codecademy Introduction to Ruby](https://www.codecademy.com/courses/learn-ruby/lessons/introduction-to-ruby/) section from their [Ruby Track](https://www.codecademy.com/catalog/language/ruby).
      1. Done until lesson 5 of [Regexone](https://regexone.com/lesson/repeating_characters?)
   1. Cherry picking on _Web development 101_ (32% completed)
      1. Created silly ruby on rails car application
      1. Git overview [Git cheat sheet](https://education.github.com/git-cheat-sheet-education.pdf)

**Thoughts**: 
* It won't be easy to find 1 hour each day to finish this challenge.
* Interesting discover of [Heroku](https://www.heroku.com/). Usefull for quick deployments. [More info](https://www.theodinproject.com/courses/web-development-101/lessons/your-first-rails-application?ref=lnav#step-2-initialize-git-and-push-to-github) 

**Link(s) to work**: [The Odin Project](https://www.theodinproject.com/)
