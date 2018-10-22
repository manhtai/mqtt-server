# MQTT server

> MQTT server for [count29-app][0]. But it's just a MQTT server, so...

1) Create new tls certs, using [letsencrypt][1], or buy your own.

2) Create new password file using [mosquitto_passwd][2]. Then,

```
docker-compose up -d
```

Enjoy!


[0]: https://github.com/manhtai/count29-app
[1]: https://letsencrypt.org/
[2]: https://mosquitto.org/man/mosquitto_passwd-1.html
