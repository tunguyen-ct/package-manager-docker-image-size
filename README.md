# Steps to benchmark

NPM

```
cd npm-docker-next
make build
```

Yarn

```
cd yarn-docker-next
make build
```

PNPM

```
cd pnpm-docker-next
make build
```

# View docker image size

```
docker image ls
```

# Comparison Table


| Package Manager  | Docker Image Size |
| ------------- | ------------- |
| npm@8.x | 326MB |
| yarn@1.x | 1.05GB |
| pnpm@6.x | 284MB |