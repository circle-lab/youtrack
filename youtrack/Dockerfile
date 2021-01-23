FROM alpine

ENV YOUTRACK_VERSION=2020.6.3319

WORKDIR /tmp

RUN apk --no-cache update \
    && apk --no-cache upgrade \
    && apk --no-cache add openjdk11 \
    && wget -O youtrack.jar https://download.jetbrains.com/charisma/youtrack-${YOUTRACK_VERSION}.jar

EXPOSE 8080
