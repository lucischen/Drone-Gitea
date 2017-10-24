## Config
### Gitea

```shell
vim ./gogs/gogs/conf/app.ini
```
replace server config
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
