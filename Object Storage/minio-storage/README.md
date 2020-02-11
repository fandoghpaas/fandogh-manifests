## Minio

> MinIO is an object storage server released under Apache License v2.0. It is compatible with Amazon S3 cloud storage service. It is best suited for storing unstructured data such as photos, videos, log files, backups and container / VM images. Size of an object can range from a few KBs to a maximum of 5TB. [Read More](https://github.com/minio/minio)

---

In order to deploy minio on fandogh you can use the following manifests.

```
$ fandogh service apply -f minio-manifest.yml -p MINIO_ACCESS_KEY="<strong_key>" -p MINIO_SECRET_KEY="<another strong key>" -p MINIO_VOLUME="storage"
```