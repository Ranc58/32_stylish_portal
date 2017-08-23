# Shared CSS Library

nginx config file for replace CSS in two sites:
1) [simpsons.fox-fan.ru](https://simpsons.fox-fan.ru/)
2) [python.org/doc/](https://www.python.org/doc/)
# How to Test
First, you need install nginx: `sudo apt install nginx`.\
Second step: go to this repo folder and create nginx.conf link to your nginx folder:\
`sudo ln -s $(pwd)/nginx.conf /path/to/your/nginx.conf`.\
Finally setting you must open `nginx.conf` from this repo and correct way to `dist/style.css`(see comments in nginx.conf).\
Setup complete.\
Run nginx: `sudo nginx`\
Open your browser and go to [127.0.0.1:8001](http://127.0.0.1:8001) and [127.0.0.1:8002](http://127.0.0.1:8001)
# Project Goals

The code is written for educational purposes. Training course for web-developers - [DEVMAN.org](https://devman.org)
