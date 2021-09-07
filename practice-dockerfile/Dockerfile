FROM mongo

COPY . ./usr/workspace/mongo

RUN docker exec -it mongo-test

RUN show dbs

RUN mongo


# RUN mongo mongodb://host.docker.internal:27017

# RUN show dbs

