# README

##  Add permissions to the app
 `sudo chown -R $USER:$USER .`

## Delete this
`tmp/pids/server.pid `

<!-- Method to run rails server -->
## Run a container
`docker-compose run web /bin/sh`

<!-- docker run -p 3000:3000 docker-rails:v1 bin/rails s -b 0.0.0.0 -->
<!--  We could craft a really long, ugly docker run
that executes the instructions one after another. However, that’s going to be hard
to comprehend -->
Install rails 6 and webpacker
  `https://forum.devtalk.com/t/docker-for-rails-developers-notes-for-rails-6-1-ruby-2-7-2/5490 `
  `https://roeland.moors.org/2021/10/03/rails-7-docker-nginx.html`

## This is a great resource
<!-- https://dev.to/amree/ruby-on-rails-development-using-docker-o1d -->

Run the ruby image 

`docker run -it --rm -v ${PWD}:/usr/src/app ruby:3.0 bash`

Install rails version you want from https://rubygems.org/gems/rails

`gem install rails -v 6.1.4.3`

Create a new app 
`rails new app`

Build a rails image from the Dockerfile

`docker build . `

Run a the rails image

`docker run --rm -p 3000:3000 -t rails image_id`

`docker-compose run {{name of your the container you want to start}} /bin/bash`

Install webpacker
`rails webpacker:install`

Install the react-rails gem
`rails webpacker:install:vue`

There may be an error compiling 
<!-- import * as Vue from 'vue' -->

## Read this for puppeteer  
<!-- http://www.smartjava.org/content/using-puppeteer-in-docker-copy-2/ -->