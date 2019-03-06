FROM openjdk:8-jdk-alpine

# Set timezone to Asia/Chongqing
RUN apk --update add tzdata \
	&& cp /usr/share/zoneinfo/Asia/Chongqing /etc/localtime \
	&& echo "Asia/Chongqing" > /etc/timezone \
	&& apk del tzdata

# Install fonts
RUN apk add --update ttf-dejavu \
	&& rm -rf /var/cache/apk/*
