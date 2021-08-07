1. Launch a http server for sharing cached packages on the host.
This can reduce download time.

```
make share-cache
```

2. Testing the ros2 package installation inside a docker.

```
make
make test
```

Use `make clean` to free up disk space afterward.

Note: Make sure you have a good amount of free space for docker images.
I would recommend to have at least 15 GB's available.