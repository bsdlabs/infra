The following commands can be executed to (1) create a container from an image and start the container, and (2) attach and (3) detach from an interactive shell.

1. List Images: ```sudo podman images```
1. Create and run a container (-d)etatched and with a (-t)ty: ```sudo podman run -dt <image id>```
2. Connect to the container ```sudo podman attach <container id>```
3. To end your interactive container session: ```Ctrl+p then Ctrl+q```

Podman also allows for the downloading and importing of an image:<br>
```sudo podman pull ghcr.io/freebsd/freebsd-runtime:14.3```
