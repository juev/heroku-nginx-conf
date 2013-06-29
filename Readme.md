# Heroku-Nginx

This repository contains the template for the organization of a server that will distribute static content with nginx.
To work use [heroku-buildpack-nginx](https://github.com/abhishekmunie/heroku-buildpack-nginx).
For the work necessary to install [heroku toolbelt](https://toolbelt.heroku.com "Heroku Toolbelt").

## Usage

    (~) $ mkdir test
    (~) $ cd test
    (test) $ git clone https://github.com/Juev/Heroku-Nginx.git
    (test) $ heroku create --stack cedar --buildpack https://github.com/abhishekmunie/heroku-buildpack-nginx.git
    (test) $ git push heroku master

Nginx configuration is located in the `conf`, and the content is placed in the `public` directory.