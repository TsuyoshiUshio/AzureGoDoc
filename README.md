Azure Go Doc
===
This project is for building Go Doc for Azure Go projects.

Currently, I add these library to the `Dockerfile`. 

```
github.com/go-autorest
github.com/azure-sdk-for-go
```

If you want to add other libraries, feel free to add it and send pull request.

This repository is automatically build on the DockerHub. Then automatically deployed on App Service on Linux.

