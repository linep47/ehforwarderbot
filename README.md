修改自https://github.com/jiz4oh/ehforwarderbot.git
# ehforwarderbot

## install

```console
git clone https://github.com/linep47/ehforwarderbot ehforwarderbot
```

## configuration

1. in `profiles/default/blueset.telegram/config.yaml` #网页版
   1. Update `token`
   2. Update userid in `admins`
2. (optional) in `profiles/default/config.yaml` #多账号
   1. add extra slave_channels
3. 'nano profiles/comwechat/blueset.telegram/config.yaml' #comwechat
   1. Update `token`
   2. Update userid in `admins`
## start

```console
cd ehforwarderbot
# comwechat
docker compose up -d
# web
# docker compose -f ./docker-compose.web.yaml up -d
```

