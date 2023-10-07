
# Pull

```shell
docker pull postgres:latest
```

# Build

```shell
docker build -t node-do-zero:1.0 .
```

# Run

```shell
docker run --name node-do-zero-db -p 5432:5432 node-do-zero:1.0
```

# Exec

```shell
docker exec -i -t node-do-zero-db sh
```