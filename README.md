redis
=================

Setup Redis server

OS Platform
-----------------

### Debian

- bookworm
- bullseye

Role Variables
--------------

設定方法の詳細については[defaults/main.yml](defaults/main.yml)のサンプルコードを参照してください。

### `redis_extra_cfg`

Redisの設定

### `redis_port`

Redisのポート

Example Playbook
--------------

```yaml
- hosts: servers
  roles:
    - role: redis
```

License
--------------

Apache License 2.0
