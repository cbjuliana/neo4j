# neo4j 

```
docker run -it --rm --publish=7474:7474 --publish=7687:7687 -e NEO4J_dbms_connector_https_advertised__address="localhost:7473" -e NEO4J_dbms_connector_http_advertised__address="localhost:7474" -e NEO4J_dbms_connector_bolt_advertised__address="localhost:7687" --env=NEO4J_AUTH=none neo4j
```
