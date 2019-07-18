# scylladb with jaeger


## init schmea

* clone jaeger code

```code
git clone https://github.com/jaegertracing/jaeger.git
```

* create schema

> need cqlsh install first

```code
MODE=test sh ./plugin/storage/cassandra/schema/create.sh | cqlsh
```

## start 

* docker-compose

```code
docker-compose up -d
```

* view UI webpage


```code
open http://hostip:16686
```