# 下面這條指令在日後 Miniflux 大版本升級時候有可能也會用到
$ docker-compose exec miniflux /usr/bin/miniflux -migrate
# 下面這條在新增管理員帳號跟密碼，等下要登入 Miniflux 管理後台用的
$ docker-compose exec miniflux /usr/bin/miniflux -create-admin

