# Adminer
`Adminer` (formerly known as phpMinAdmin) is a tool for managing content in **MySQL** databases (since version 2 also in **PostgreSQL**, **MS SQL**, **SQLite** and Oracle databases). Adminer is distributed under Apache license (or GPL v2) in a form of a single PHP file (around 470 KiB in size). Its author is Jakub Vrána who started to develop this tool as a light-weight alternative to phpMyAdmin, in July 2007.\
Adminer got some attention in 2008 when it made it to the CCA finals at SourceForge.[2] Also, first webhosting providers started to include Adminer as MySQL managing tool into their portfolio of services. In 2012 Adminer got coverage on Linux.com for the second time.[3] The project's priorities, according to its author, are (in this order): safety, user-friendliness, performance, functionality, and size.

## Variable Table

>  **Before deployment** value of `variables` mentioned in this table should be overwritten with values of your choice.

|Variable | Description |
|--- |--- |
|**SERVICE_NAME** | Choose a name for your Adminer service
|**DATABASE_SERVICE_NAME** | Name of the database service

## Managed Service
You can also skip deploying `Adminer` from manifest and start using [Fandogh Managed Service](https://docs.fandogh.cloud/docs/mongodb-managed-service.html) with few clicks.

## Deploying with [fandogh-cli](https://docs.fandogh.cloud/docs/service-manifest.html#%D9%85%D8%A7%D9%86%DB%8C%D9%81%D8%B3%D8%AA-%D8%B3%D8%B1%D9%88%DB%8C%D8%B3-%DA%86%DB%8C%D8%B3%D8%AA)
```
fandogh service apply -f deployment_manifest.yml
```
