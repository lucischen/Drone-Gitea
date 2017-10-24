## Config
### Gogs

```shell
vim ./gogs/gogs/conf/app.ini
```
replace server config
```ini
[server]
APP_DATA_PATH    = /data/gitea
SSH_DOMAIN       = gitea-server
DOMAIN           = gitea-server
HTTP_PORT        = 3000
ROOT_URL         = http://gitea-server:3000/
DISABLE_SSH      = false
SSH_PORT         = 22
LFS_START_SERVER = false
OFFLINE_MODE     = false
```
