FROM alpine:3.18.3
RUN apk --no-cache add \
	openvpn

RUN mkdir /usr/share/openvpn
RUN cp /etc/openvpn/* /usr/share/openvpn/

WORKDIR /etc/openvpn
ENTRYPOINT ["openvpn"]
