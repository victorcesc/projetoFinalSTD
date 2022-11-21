FROM gradle:7-jdk17-alpine

COPY hello /hello

WORKDIR /hello

RUN gradle installDist

CMD ["./app/build/install/app/bin/app"]