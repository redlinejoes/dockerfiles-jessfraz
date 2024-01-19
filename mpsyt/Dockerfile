FROM python:3.13.0a3-alpine
LABEL maintainer "Justin Garrison <justinleegarrison@gmail.com>"

RUN apk add --no-cache \
	mplayer \
	mpv

RUN pip install mps-youtube

ENTRYPOINT ["mpsyt"]
