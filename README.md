```
docker build -t image_name .
[OPTIONAL]docker build -t username/my_image:v1.0 .
docker build --no-cache -t aiyaraaiya/go_docker_test:v1.0 .
docker run -p host_port:container_port image_name
docker run -p 8080:8080 aiyaraaiya/go_docker_test:v1.0
```
```
Alpine
Url: https://alpinelinux.org/
Imagename: alpine
Shorty: Its very small.
Packagemanger: apk
Shells: /bin/sh
Size: Few MBs - current tag needs 2.7MB

Jessie aka Debian 8
Url: https://wiki.debian.org/DebianJessie
Imagename: debian:jessie
Shorty: No LTS anymore
Packagemanager: apt
Shells: /bin/bash
Size: ~50mb

Stretch aka Debian 9
Url: https://wiki.debian.org/DebianStretch
Imagename: debian:stretch
Shorty: LTS is running out
Packagemanager: apt
Shells: /bin/bash and many more
Size: ~40mb

Buster aka Debian 10
Url: https://wiki.debian.org/DebianBuster
Imagename: debian:buster
Shorty: All what you need, but newer
Packagemanager: apt
Shells: /bin/bash and many more
Size: ~50mb

Bullseye aka Debian 11
Url: https://wiki.debian.org/DebianBullseye
Imagename: debian:bullseye
Shorty: All what you need, but newer
Shells: /bin/bash and many more
Size: ~50mb

Bookworm aka Debian 12
Url: https://wiki.debian.org/DebianBookworm
Imagename: debian:bookworm
Shorty: Newest debian
Shells: /bin/bash and many more
Size: ~50mb

Ubuntu based on debian
Url: https://hub.docker.com/_/ubuntu
Imagename: ubuntu
Shorty: All what you need
Packagemanager: apt
Shells: /bin/bash and more
Size: ~25mb
```