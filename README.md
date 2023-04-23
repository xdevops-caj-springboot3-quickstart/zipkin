# Zipkin

Distributed tracing via Zipkin.

## Run Zipkin server via container

```bash
podman run -d --rm --name=zipkin \
  -p 9411:9411 \
  openzipkin/zipkin
```

Access the Zipkin dashboard <http://localhost:9411/> in a browser.

## Refeences

- https://hub.docker.com/r/openzipkin/zipkin/