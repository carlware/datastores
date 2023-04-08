## Datastores

An easy way to get several databases running with just few commands using docker
And containers can use them easily.

## setup
```shell
# run first networking
cd services/networking && docker compose up -d

# then any database can be launch (e.g.)
cd services/elasticseach && docker compose -d
```

## test
```shell
# test endpoint
curl -L XGET test.happydevel.com 

```

## other services description
1. sqlpad: nice ui to execute sql queries
2. dozzle: nice ui to see docker logs
