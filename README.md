# Neo4j 4.3 Server Side Routing demo

## Server Side Routing

- 3 X Neo4j Core with no ports exposed
- 1 X Neo4j Core with ports exposed
- 1 Read Replica
- Server Side Routing enabled

```bash
docker-compose -f compose-ssr.yml up -d
```

## Singe Instance + Read Replica

- 1 X Neo4j Single
- 1 X Read Replica

```bash
docker-compose -f compose-single+rr.yml up -d
```