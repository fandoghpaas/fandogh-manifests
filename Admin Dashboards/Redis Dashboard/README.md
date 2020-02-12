# Redis Dashboard
`Redis` web management tool written in `node.js`.

## Variable Table

>  **Before deployment** value of `variables` mentioned in this table should be overwritten with values of your choice.

|Variable | Description |
|--- |--- |
|**SERVICE_NAME** | Choose a name for your Redis Dashboard service
|**REDIS_SERVICE_NAME** | Name of your Redis service
|**USERNAME** | Choose username for your Redis Dashboard
|**STRONG_PASSWORD** | Choose a strong password for your Redis Dashboard
|**REDIS_SERVICE_PASSWORD** | Password of your Redis service

## Deploying with [fandogh-cli](https://docs.fandogh.cloud/docs/service-manifest.html#%D9%85%D8%A7%D9%86%DB%8C%D9%81%D8%B3%D8%AA-%D8%B3%D8%B1%D9%88%DB%8C%D8%B3-%DA%86%DB%8C%D8%B3%D8%AA)
```
fandogh service apply -f deployment_manifest.yml
```

