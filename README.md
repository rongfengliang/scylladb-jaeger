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