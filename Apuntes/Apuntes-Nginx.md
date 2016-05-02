# Apuntes NGINX

Nginx es un servidor web/proxy inverso ligero de alto rendimiento y un proxy para protocolos de correo electrónico (IMAP/POP3).

#### user www-data;
Nombre de usario que está utilizando por Nginx.

#### worker_processes;
Numero de procesadores en el que trabajará Nginx.

#### worker_connections;
Numero Maximo de conexiones que puede tener el sitio.

#### keepalive_timeout;
Tiempo de espera para las conexiones mantenidas por el cliente.

#### server_names_hash_bucket_size;
Longitud maxima que pueden tener los nombres de dominio.

---

#### Ocultar la Versión de Nginx
Despues de 'server_tokens off;' añadir : 

more_clear_headers 'Server';
more_clear_headers 'X-Power-by'

#### Acceder a los logs de Nginx
/var/log/nginx/access.log;
	
#### Acceder a los errores de Nginx
/var/log/nginx/error.log;