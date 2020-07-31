# DOCKER COMPOSE 

## DotEnv config

~~~.env
USERD = admin
PASSWD = admin
FOLDER = sharing
VOLUME_FOLDER = ./sharing
DOMAIN_NAME = WORKGROUP
TZ = EST5EDT
~~~

* **USERD** - Usuário Administrador que será criado dentro do container

* **PASSWD** - Senha que esse adm terá

* **FOLDER** - Pasta simbólica que será compartilhada.

* **VOLUME_FOLDER** - Pasta real que será compartilhada.

* **DOMAIN_NAME** - Nome que será marcado como workgroup


File manager: 

[smb://WORKGROUP;admin@localhost/sharing](smb://WORKGROUP;admin@localhost/sharing)
