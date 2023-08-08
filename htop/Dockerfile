# htop in a container
#
# docker run --rm -it \
# 	--pid host \
# 	jess/htop
#
FROM alpine:3.18.3
LABEL maintainer "Jessie Frazelle <jess@linux.com>"

RUN apk --no-cache add \
	htop

CMD [ "htop" ]
