# deephaven-caddy

A Deephaven reverse-proxy setup using [Caddy](https://caddyserver.com).

```shell
docker compose up -d
```

Then, connect to [https://deephaven-foo.localhost](https://deephaven-foo.localhost) or [https://deephaven-bar.localhost](https://deephaven-bar.localhost) (you'll probably need to accept the self-signed certificate).

## Manual TLS

See [manual-tls-certs branch](https://github.com/devinrsmith/deephaven-caddy/tree/manual-tls-certs).

## Related

* [deephaven-envoy](https://github.com/devinrsmith/deephaven-envoy)
* [deephaven-traefik](https://github.com/devinrsmith/deephaven-traefik)
