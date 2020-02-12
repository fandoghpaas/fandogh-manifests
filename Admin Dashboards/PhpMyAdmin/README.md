# PhpMyAdmin
`phpMyAdmin` is a free and open source administration tool for `MySQL` and MariaDB. As a portable web application written primarily in `PHP`, it has become one of the most popular `MySQL` administration tools, especially for web hosting services.

## Variable Table

>  **Before deployment** value of `variables` mentioned in this table should be overwritten with values of your choice.

|Variable | Description |
|--- |--- |
|**SERVICE_NAME** | Choose a name for your PhpMyAdmin service
|**MYSQL_SERVICE_NAME** | Name of the database service

## Managed Service
You can also skip deploying `PhpMyAdmin` from manifest and start using [Fandogh Managed Service](https://docs.fandogh.cloud/docs/mysql-managed-service.html) with few clicks.

## Deploying with [fandogh-cli](https://docs.fandogh.cloud/docs/service-manifest.html#%D9%85%D8%A7%D9%86%DB%8C%D9%81%D8%B3%D8%AA-%D8%B3%D8%B1%D9%88%DB%8C%D8%B3-%DA%86%DB%8C%D8%B3%D8%AA)
```
fandogh service apply -f deployment_manifest.yml
```

