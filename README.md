# docker-ejabberd-data

Data image for [rroemhild/ejabberd](https://github.com/rroemhild/docker-ejabberd).

## Uasge

```
$ docker create --name ejabberd-data rroemhild/ejabberd-data
$ docker run -d --name ejabberd --volumes-from ejabberd-data rroemhild/ejabberd
```
