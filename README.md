
# Ruby on Rails Tutorial : hello world
[*Ruby on Rails tutorial*](http://www.railstutorial.org/)


Commands ran to build this application : 

- cd to workspace
- rails new hello_app
- update Gemfile to use a fixed version for package just as an exercise
- cd to hello_app
- run the command : bundle install
- run command : rails server # server starts running at 3000. localhost:3000
- update app/controller/application_controller.rb to add a hello def
- update config/routes.rb with root "application#hello"
- rails server

-- to add to git
- git init
- git add -A
- git commit -m ""
- git log # to see previous commit messages 
- git push origin master # pushed the changes to github

-- to modify README.md by creating branch
- git branch -b modify-README
- git mv README.rdoc README.md
- modify README.md
- git checkout master
- git merge modify-README

-- pushing to heroku
- 