Microsoft SQL Server manifests
=========================

In order to deploy mssql server on fandogh you can use the following manifests.

### manifest-with-dedicated-volume.yml
This manifest deploys an instance of mssql server with 3GB of memory.

*Note* feel free to customized the manifest based on your needs.

To deploy the service you can run the following command:

```bash
fandogh service apply -f manifest-with-dedicated-volume.yml -p MSSQL_SA_PASSWORD=A_COMPLEX_PASSWORD -p VOLUME_NAME=NAME_OF_YOUR_VOLUME
```


