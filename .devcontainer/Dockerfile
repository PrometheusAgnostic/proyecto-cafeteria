FROM mcr.microsoft.com/devcontainers/java:1-25-bookworm

RUN apt-get update \
	&& apt-get install -y --no-install-recommends postgresql-client \
	&& rm -rf /var/lib/apt/lists/*

WORKDIR /workspace