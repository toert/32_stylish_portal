# Shared CSS Library

This config file for Nginx helps you to test changed static files without deploying websites on your own computer (google it - nginx proxy_pass)

# How to Test

1) Install nginx for your operating system
2) Create link for config:

	`cd 32_stylish_portal`
	
	`sudo ln -s $(pwd)/nginx.conf /path/to/nginx/nginx.conf`

3) Change paths of roots in config file
4) Start it by typing `sudo nginx` in CL

# Project Goals

The code is written for educational purposes. Training course for web-developers - [DEVMAN.org](https://devman.org)
