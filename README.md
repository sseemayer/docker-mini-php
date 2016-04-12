# mini-php
A super-lightweight (< 20 MB) and complete docker image for serving PHP apps over HTTP. Combines [Alpine Linux](http://www.alpinelinux.org/) with [lighttpd](https://www.lighttpd.net/) and [php-fpm](http://php-fpm.org/), running in [runit](http://smarden.org/runit/)

Exposes a web server on port 5000. Place your webapp into the container at `/app/htdocs`
