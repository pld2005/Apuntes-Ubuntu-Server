# Servicio UFW

Uncomplicated Firewall (ufw) es un cortafuegos diseñado para ser de fácil uso desarrollado por Ubuntu. Utiliza la línea de comandos para configurar las iptables usando un pequeño número de comandos simples.

#### Bloquear todo tipo de conecciones entrantes
```sh
$ sudo ufw default deny incoming
```

#### Permitir todo tipo de conecciones salientes
```sh
$ sudo ufw default allow outgoing
```

#### Permitir conexiones SSH
```sh
$ sudo ufw allow ssh
```

#### Permitir conexiones FTP - SSH - :80
```sh
$ sudo ufw allow www
```

#### Permitir conexiones SSL
```sh
$ sudo ufw allow 443/tcp
```

#### Lista de conexiones
```sh
$ sudo ufw status
```

#### Habilitar Firewall
```sh
$ sudo ufw enable
```