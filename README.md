# alpine-privoxy
alpine privoxy


docker build -t huangsen365/alpine-privoxy .


docker run -d -p 8080:8080 --restart=always --name=my_alpine_privoxy_8080 huangsen365/alpine-privoxy
