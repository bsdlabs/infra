The following commands can be executed to (1) create a container from an image and start the container, and (2) attach and (3) detach from an interactive shell.

1. List Images: ```sudo podman images```
2. Create and run a container (-d)etatched and with a (-t)ty: ```sudo podman run -dt <image id>```
3. Connect to the container ```sudo podman attach <container id>```
4. To end your interactive container session: ```Ctrl+p then Ctrl+q```
5. List running containers: ```sudo podman container list```

Podman also allows for the downloading and importing of an image:<br>
```sudo podman pull ghcr.io/freebsd/freebsd-runtime:14.3```
