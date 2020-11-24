# powervs-container-host

Dockerfiles to build containers from where you can run Terraform automation to install OpenShit in PowerVS.

# Building the images

```
  docker login registry.redhat.io (https://access.redhat.com/RegistryAuthentication)

  (x86_64)  docker build -t powervs-container-host-$(uname -m) -f ./dockerfile/Dockerfile.x86_64 .

  (ppc64le) docker build -t powervs-container-host-$(uname -m) -f ./dockerfile/Dockerfile.ppc64le .
```
