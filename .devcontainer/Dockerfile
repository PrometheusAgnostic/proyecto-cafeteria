FROM mcr.microsoft.com/openjdk/jdk:25-ubuntu

RUN apt-get update \
	&& apt-get install -y --no-install-recommends git maven postgresql-client \
	&& rm -rf /var/lib/apt/lists/*

WORKDIR /workspace