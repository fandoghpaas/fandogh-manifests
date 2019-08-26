## PGWeb

> Pgweb is a web-based database browser for PostgreSQL, written in Go and works on OSX, Linux and Windows machines. Main idea behind using Go for backend development is to utilize ability of the compiler to produce zero-dependency binaries for multiple platforms. Pgweb was created as an attempt to build very simple and portable application to work with local or remote PostgreSQL databases. [Read More](https://github.com/sosedoff/pgweb)

---

In order to deploy pgweb on fandogh you can use the following manifests.

```
$ fandogh service apply -f pgweb-manifest.yml -p DATABASE_URL="postgres://user:password@host:port/database"
```