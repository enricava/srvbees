
## Start Prometheus

```sh
docker run \
    --rm \
    --net="host" \
    -p 9090:9090 \
    -p 8081:8081 \
    -v ./prometheus.yml:/etc/prometheus/prometheus.yml \
    prom/prometheus
```
