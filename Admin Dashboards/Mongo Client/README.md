# Mongo Client
Cross-platform and self hosted, easy to use, MongoDB 4.0+ support and more features!

## Variable Table

>  **Before deployment** value of `variables` mentioned in this table should be overwritten with values of your choice.

|Variable | Description |
|--- |--- |
|**SERVICE_NAME** | Choose a name for your Mongo Client service
|**USERNAME** | Choose username for your Mongo Client dashboard
|**STRONG_PASSWORD** | Choose strong password for your Mongo Client dashboard
|**DATABASE_URL** | mongodb://username:password@mongodb_service_name:27017/database_name?authSource=admin&authMechanism=SCRAM-SHA-1

## Deploying with [fandogh-cli](https://docs.fandogh.cloud/docs/service-manifest.html#%D9%85%D8%A7%D9%86%DB%8C%D9%81%D8%B3%D8%AA-%D8%B3%D8%B1%D9%88%DB%8C%D8%B3-%DA%86%DB%8C%D8%B3%D8%AA)
```
fandogh service apply -f deployment_manifest.yml
```

