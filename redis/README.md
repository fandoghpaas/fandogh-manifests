## Redis

> Redis is often referred as a data structures server. What this means is that Redis provides access to mutable data structures via a set of commands, which are sent using a server-client model with TCP sockets and a simple protocol. So different processes can query and modify the same data structures in a shared way. [Read More](https://github.com/antirez/redis)

---

There are two ways to deploy redis on fandogh.

#### Fandogh Managed Service (Recommended)

```
$ fandogh service apply -f managed-service-manifest.yml -p PASSWORD="<strong password>" -p VOLUME="<volume name (for persistence)>"
```

#### Manual Internal Service

```
$ fandogh service apply -f redis-manifest.yml
```
