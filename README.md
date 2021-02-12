# docker-graphql-playground

Simple docker container that expose the graphql playground. Can be usefull in development environments, coupled with
docker-compose.

```
docker run -p 8090:80 -e GRAPHQL_ENDPOINT=http://localhost:8080/graphql vtemian/graphql-playground
```
