## Config
### Gitea

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

[v] domain

```
[server]
DOMAIN           = git.polaris
HTTP_PORT        = 3000
ROOT_URL         = http://git.polaris/
DISABLE_SSH      = false
SSH_PORT         = 10022
START_SSH_SERVER = false
OFFLINE_MODE     = false
```

### .env

[v] domain

```
[GOGS]
GOGS_PORT=8380

[DB]
MYSQL_ROOT_PASSWORD=1234
PHPMYADMIN_PORT=8082

[DRONE]
DRONE_PORT=8381
DRONE_HOST=http://drone.polaris
DRONE_GIT_URL=http://git.polaris
DRONE_SECRET=ANY_SECRET_YOU_WANT
```