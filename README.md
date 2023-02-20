# Docker Collection

## What is this?

This is a collection of Dockerfiles that I use for my own projects. They are not meant to be used by anyone else, but feel free to use them if you want.

## How do I use them?

You can use them by cloning this repository and then running `docker-compose up --build` on the directory of the application you want to use. For example, to build the `elk` image, you would run:

```bash
cd elk
docker-compose up --build

# or if you want to run it in the background
docker-compose up -d --build
```

## What's in here?

- [elk](elk/README.md): Elasticsearch, Logstash, and Kibana
- [dynamodb](dynamodb/README.md): DynamoDB