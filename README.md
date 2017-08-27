Azure Go Doc
===
This project is for building Go Doc for Azure Go projects.

Currently, I add these library to the [Dockerfile](https://github.com/TsuyoshiUshio/AzureGoDoc/blob/master/Dockerfile). 

```
github.com/go-autorest
github.com/azure-sdk-for-go
```

If you want to add other libraries, feel free to add it and send pull request.

This repository is automatically build on the DockerHub. Then automatically deployed on App Service on Linux.

# Azure Go Doc Website

You can refer this site. However, I create this website as a hobby. The URL might be changed in the future. 

[Azure Go Library Doc website](http://azuregodoc.azurewebsites.net)


# Continuous Deployment

This website is automatically build/updated. If you push new change to the master, DockerHub automated build start, then webhook call App Service on Linux deployment.



