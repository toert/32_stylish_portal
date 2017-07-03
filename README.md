# Shared CSS Library

This config file for Nginx helps you to test changed static files without deploying websites on your own computer (google it - nginx proxy_pass)

# How to Test

1) Install nginx for your operating system
2) Create link for config:

	`cd 32_stylish_portal`

	`sudo ln -s $(pwd)/nginx.conf /path/to/nginx/nginx.conf`

3) Change paths of roots in config file
4) Start it by typing `sudo nginx` in CL
5) Go to 
 [http://127.0.0.1:8010](http://127.0.0.1:8010) (proxy pass for [htmlbook.ru/](http://htmlbook.ru/))
 [http://127.0.0.1:8011](http://127.0.0.1:8011) (proxy pass for [djbook.ru/](https://djbook.ru/))

# Project Goals

The code is written for educational purposes. Training course for web-developers - [DEVMAN.org](https://devman.org)
