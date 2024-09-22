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

### [defaults/main.yml](defaults/main.yml)

設定方法の詳細については[defaults/main.yml](defaults/main.yml)のサンプルコードなどを参照してください。

#### `redis_extra_cfg`

Redisの設定

#### `redis_port`

Redisのポート

### [vars/main.yml](vars/main.yml)

設定値については[vars/main.yml](vars/main.yml)を参照してください。

#### `redis_config_dir`

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
