# Mattermost
`Mattermost` is an open source Slack alternative. It's written in Golang and React and runs as a single Linux binary with MySQL or PostgreSQL. Use the features you like (file sharing, real-time group chat and webhooks—to name a few) and access the source code.

## Variable Table

>  **Before deployment** value of `variables` mentioned in this table should be overwritten with values of your choice.

|Variable | Description |
|--- |--- |
|**SERVICE_NAME** | Choose a name for your Mattermost service
|**DATABASE_SERVICE_NAME** | Name of the database service
|**DATABASE_SERVICE_PORT** | Database service port (5432 for PostgreSQL or 3306 for MySQL)
|**DATABASE_USERNAME** | Database username
|**DATABASE_PASSWORD** | Database password
|**DATABASE_NAME** | Database name
|**VOLUME_NAME** | Name of volume to persist Mattermost data

## Managed Service
You can also skip deploying `Mattermost` from manifest and start using [Fandogh Managed Service](https://docs.fandogh.cloud/docs/mongodb-managed-service.html) with few clicks.

## Deploying with [fandogh-cli](https://docs.fandogh.cloud/docs/service-manifest.html#%D9%85%D8%A7%D9%86%DB%8C%D9%81%D8%B3%D8%AA-%D8%B3%D8%B1%D9%88%DB%8C%D8%B3-%DA%86%DB%8C%D8%B3%D8%AA)

### Database
before you deploy `Mattermost` manifest, be sure that you have created a database service before hand and create a database in it and pass it to the manifest as `DATABASE_NAME`.
<br/><br/>
You can create `MySQL` or `PostgreSQL` with `Fandogh Managed Service` commands as described below:
```
fandogh managed-service deploy mysql latest \
-c service_name=SERVICE_NAME \
-c phpmyadmin_enabled=true \
-c mysql_root_password=DATABASE_PASSWORD
```
or
```
fandogh managed-service deploy postgres latest \
-c service_name=SERVICE_NAME \
-c adminer_enabled=true \
-c postgres_password=DATABASE_PASSWORD
```
> DATABASE_USERNAME will be `root` for MySQL and `postgres` for PostgreSQL.

### Final Step
```
fandogh service apply -f deployment_manifest.yml
```
