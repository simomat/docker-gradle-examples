


## Define proxy for docker

```bash
$ mkdir -p ~/.docker/
$ export DOCKER_CONFIG=~/.docker/
```

Configure proxy settings in *~/.docker/config.json*
```json
{
 "proxies":
 {
   "default":
   {
     "httpProxy": "http://127.0.0.1:3001",
     "httpsProxy": "http://127.0.0.1:3001",
     "ftpProxy": "http://127.0.0.1:3001",
     "noProxy": "*.test.example.com,.example2.com"
   }
 }
}
```
