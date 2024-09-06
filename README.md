# Local DNS with Coredns

## Run container

```shell
docker compose up -d
```

## Validate if DNS works

```shell
dig -p 1053 @localhost www.untalsanders.dev 
```