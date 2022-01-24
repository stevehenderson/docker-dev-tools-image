# Dev Tools Image

This image is designed to provide a development environment inside Kubernetes with all the tools you need to succeed.
It will start and open up an ssh port.  You can then connect a service and ingress to connect to the development environment.

## Building

Create a secrets sub folder in this repo home directory

```
mkdrir secrets
```

Copy in the *public* key  you will use to access the dev image:

```
cp ~/.ssh/ida_rsa.pub secrets/
```

