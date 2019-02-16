## Usage

```
docker create \
  --name=ddclient \
  -v <path to data>:/config \
  -e PGID=<gid> -e PUID=<uid>  \
  -e TZ=<Timezone> \
  linuxserver/ddclient
```
