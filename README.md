# Run solr

```
docker-compose up -d
```

# Next load some of the example data that is included in the container:

```
docker exec -it my_solr post -c gettingstarted example/exampledocs/manufacturers.xml

docker exec -it my_solr post -c gettingstarted example/exampledocs/utf8-example.xml
```