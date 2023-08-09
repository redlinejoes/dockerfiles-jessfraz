FROM alpine:3.18.3
LABEL maintainer "Jessie Frazelle <jess@linux.com>"

RUN apk --no-cache add \
	--repository http://dl-cdn.alpinelinux.org/alpine/edge/testing/ \
	gnuplot

ENTRYPOINT ["gnuplot"]
