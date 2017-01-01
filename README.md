# WindowsDockerFiles
Docker Files for Windows Server Containers

```
docker build -t docker.io/dscottraynsford/chocolatey-windowsservercore .\chocolatey-windowsservercore
docker tag dscottraynsford/chocolatey-windowsservercore:latest bmdcontainers-on.azurecr.io/dscottraynsford/chocolatey-windowsservercore:latest
docker push dscottraynsford/chocolatey-windowsservercore:latest
docker push bmdcontainers-on.azurecr.io/dscottraynsford/chocolatey-windowsservercore:latest
```

```
docker build -t bmdcontainers-on.azurecr.io/dscottraynsford/jre-windowsservercore .\jre-windowsservercore
```

```
docker build -t bmdcontainers-on.azurecr.io/dscottraynsford/jdk-windowsservercore .\jdk-windowsservercore
```