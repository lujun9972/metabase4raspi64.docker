FROM eclipse-temurin:11

RUN mkdir /apps
WORKDIR /apps/

ADD https://downloads.metabase.com/v0.44.1/metabase.jar /apps/

EXPOSE 3000

CMD java -jar metabase.jar
