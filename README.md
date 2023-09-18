# oauth2-proxy-keycloak

## Setup

setup keycloak

```bash
docker compose up -d keycloak 
```

If A and B are on the same server

```bash
echo 127.0.0.1 keycloak >> /etc/hosts
```

start proxy

```bash 
docker compose up -d oauth2-proxy any
```