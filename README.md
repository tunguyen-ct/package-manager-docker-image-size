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
<img width="763" alt="Screen Shot 2022-03-25 at 17 29 28" src="https://user-images.githubusercontent.com/93700515/160103961-7dec98da-a03d-43f0-829b-7621f4fe96cc.png">

# Comparison Table


| Package Manager  | Docker Image Size |
| ------------- | ------------- |
| npm@8.x | 326MB |
| yarn@1.x | 1.05GB |
| pnpm@6.x | 284MB |
