[![makocchi/random-exit](https://shields.beevelop.com/docker/image/image-size/makocchi/random-exit/latest.svg)]()
[![makocchi/random-exit](https://shields.beevelop.com/docker/image/layers/makocchi/random-exit/latest.svg)]()

# Docker image that exits randomly

```shell
# Default success(exit 0) percentage is 50%
docker run makocchi/random-exit
```

## A percentage of success is controllable

```shell
# 80% success
docker run -e SUCCESS=80 makocchi/random-exit

# Always fail(exit 1)
docker run -e SUCCESS=0 makocchi/random-exit
```
