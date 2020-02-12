# PgWeb
`PgWeb` is a web-based database browser for PostgreSQL, written in Go and works on OSX, Linux and Windows machines. Main idea behind using Go for backend development is to utilize ability of the compiler to produce zero-dependency binaries for multiple platforms. PgWeb was created as an attempt to build very simple and portable application to work with local or remote PostgreSQL databases. [Read More](https://github.com/sosedoff/pgweb)

## Variable Table

>  **Before deployment** value of `variables` mentioned in this table should be overwritten with values of your choice.

|Variable | Description |
|--- |--- |
|**SERVICE_NAME** | Choose a name for your PgWeb service
|**DATABASE_URL** | postgres://user:password@host:port/database

## Deploying with [fandogh-cli](https://docs.fandogh.cloud/docs/service-manifest.html#%D9%85%D8%A7%D9%86%DB%8C%D9%81%D8%B3%D8%AA-%D8%B3%D8%B1%D9%88%DB%8C%D8%B3-%DA%86%DB%8C%D8%B3%D8%AA)
```
fandogh service apply -f deployment_manifest.yml
```
