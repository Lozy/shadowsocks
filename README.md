shadowsocks
===========

```
wget --no-check-certificate \
   https://raw.githubusercontent.com/Lozy/shadowsocks/master/SS_debian -O SS_debian
chmod +x SS_debian
./SS_debian
```

Addition parameter:

| option | describle | default |
| ------ | --------- | ------- |
|  --sport      |      shadowsocks server port | 40004 |
|  --lport      |      local port | 40005 |
|  --password   |       shadowsocks password | randomize(8) |
|  --encry      |       package encry type | aes-256-cfb |
