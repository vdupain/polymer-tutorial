# Polymer Tutorial

## Requirements

- docker

## Installation

- Clone the repo: `git clone git@github.com:vdupain/polymer-tutorial.git`
- `docker run --net host --name nginx-polymer \
	-v $(pwd):/usr/share/nginx/html:ro -d nginx \
	/bin/sh -c "cp /usr/share/nginx/html/nginx-default.conf /etc/nginx/conf.d/default.conf && nginx -g \"daemon off;\""`
- Go to http://localhost/finished/
