FROM openjdk:8-jre

# Set timezone to Asia/Shanghai
RUN set -e \
	&& echo "Asia/Shanghai" > /etc/timezone \
	&& rm /etc/localtime \
	&& dpkg-reconfigure -f noninteractive tzdata
