# Guide (miscellaneous)

## Setting up a new project

- mkdir Playground 
- cd Playground
- rails new playground
- cd playground
- git init
- git add -A
- git ci -m 'initial commit'
- git remote add origin https://github.com/kristen-clarityhk/playground.git
- git push -u origin master
- git co -b develop
- git push -u origin develop  

## Static pages

- rails g controller Pages home about contact
- then change the routes and add links to all pages