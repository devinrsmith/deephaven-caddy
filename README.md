# deephaven-caddy

A Deephaven reverse-proxy setup using [Caddy](https://caddyserver.com).

Currently, requires a [deephaven-core](https://github.com/deephaven/deephaven-core) server-jetty tar. Copy it into [deephaven](./deephaven/), then run:

```shell
docker compose build
docker compose up -d
```

Then, connect to [https://deephaven-foo.localhost](https://deephaven-foo.localhost) (you'll probably need to accept the self-signed certificate).
