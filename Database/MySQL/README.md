# MySQL

MySQL is the world's most popular open source database. With its proven performance, reliability and ease-of-use, MySQL has become the leading database choice for web-based applications, covering the entire range from personal projects and websites, via e-commerce and information services, all the way to high profile web properties including Facebook, Twitter, YouTube, Yahoo! and many more.

## Variable Table
> Value of `variables` mentioned in this table should be overwritten with values of your choice, before deployment.

|Variable | Description |
|--- |--- |
|**MYSQL_ROOT_PASSWORD** | Password of your choice for MySQL
|**SERVICE_NAME** | Choose a name for your MySQL service

## Managed Service
You can also skip deploying `MySQL` from manifest and start using [Fandogh Managed Service](https://docs.fandogh.cloud/docs/mysql-managed-service.html) with few clicks.

## Deploying with [fandogh-cli](https://docs.fandogh.cloud/docs/service-manifest.html#%D9%85%D8%A7%D9%86%DB%8C%D9%81%D8%B3%D8%AA-%D8%B3%D8%B1%D9%88%DB%8C%D8%B3-%DA%86%DB%8C%D8%B3%D8%AA)

```
fandogh service apply -f deployment_manifest.yml
```

