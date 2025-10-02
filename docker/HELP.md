## dify

```shell
git clone https://github.com/langgenius/dify.git --branch 1.9.0
# config nginx prot with .env#1147~
```

## ref

- https://mdnice.com/writing/a4da5a2e342f4228acea032c2a154fa3


## nginx-proxy-manager

```shell
sudo vim /etc/hosts
# nginx proxy manager test
127.0.0.1       chat.yuan-idea.com
127.0.0.1       yuan-idea.com

# resolvectl for ubuntu 24
sudo resolvectl flush-caches
sudo systemctl restart systemd-resolved
sudo resolvectl statistics

nslookup chat.yuan-idea.com
```
