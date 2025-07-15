The following commands can be executed to (1) create a container from an image and start the container, and (2) attach and (3) detach from an interactive shell.

```sudo podman images```
1. ```sudo podman run -dt <image id>```
2. ```sudo podman attach <container id>```
3. With your container focused: ```Ctrl+p then Ctrl+q```

Podman also allows for the downloading and importing of an image:
```sudo podman pull ghcr.io/freebsd/freebsd-runtime:14.3```

