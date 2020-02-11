# File Browser
**File Browser** provides a file managing interface within a specified directory and it can be used to upload, delete, preview, rename and edit your files. It allows the creation of multiple users and each user can have its own directory. It can be used as a standalone app or as a middleware.
<br/><br/>
Please check the  [main repository](https://github.com/filebrowser/filebrowser)  for more info.

## Variable Table
>  **Before deployment** value of `variables` mentioned in this table should be overwritten with values of your choice.

|Variable | Description |
|--- |--- |
|**SERVICE_NAME** | Choose a name for your File Browser service

## Deploying with [fandogh-cli](https://docs.fandogh.cloud/docs/service-manifest.html#%D9%85%D8%A7%D9%86%DB%8C%D9%81%D8%B3%D8%AA-%D8%B3%D8%B1%D9%88%DB%8C%D8%B3-%DA%86%DB%8C%D8%B3%D8%AA)
```
fandogh service apply -f deployment_manifest.yml
```
