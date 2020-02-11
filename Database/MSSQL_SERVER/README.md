# Microsoft SQL Server

Microsoft SQL Server is a relational database management system developed by Microsoft. As a database server, it is a software product with the primary function of storing and retrieving data as requested by other software applications—which may run either on the same computer or on another computer across a network (including the Internet).
<br/>
Microsoft markets at least a dozen different editions of Microsoft SQL Server, aimed at different audiences and for workloads ranging from small single-machine applications to large Internet-facing applications with many concurrent users.

## Variable Table
>  **Before deployment** value of `variables` mentioned in this table should be overwritten with values of your choice.

|Variable | Description |
|--- |--- |
|**STRONG_PASSWORD** | Password of your choice for MSSQL Server `At least 8 characters including uppercase, lowercase letters, base-10 digits and/or non-alphanumeric symbols.`
|**SERVICE_NAME** | Choose a name for your MSSQL Server service
|**VOLUME_NAME** | Name of volume to attached to your MSSQL Server service

## Managed Service
You can also skip deploying `MSSQL Server` from manifest and start using [Fandogh Managed Service](https://docs.fandogh.cloud/docs/mssql-managed-service.html) with few clicks.

## Deploying with [fandogh-cli](https://docs.fandogh.cloud/docs/service-manifest.html#%D9%85%D8%A7%D9%86%DB%8C%D9%81%D8%B3%D8%AA-%D8%B3%D8%B1%D9%88%DB%8C%D8%B3-%DA%86%DB%8C%D8%B3%D8%AA)

> Note, according to [Microsoft Documents](https://hub.docker.com/_/microsoft-mssql-server) minimum amount of memory for MSSQL Server to work properly should be `2048Mi` and above.
```
fandogh service apply -f deployment_manifest.yml
```

