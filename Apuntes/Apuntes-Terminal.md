# Apuntes Terminal

La consola o terminal (Shell) es un programa informatico donde interactua el usuario con el sistema operativo mediante una ventana que espera ordenes escritas por el usuario desde el teclado.

#### Cambiar password root
```sh
$ passwd
```
#### Cambiar password de un usuario
```sh
$ passwd Nombre-Usario
```
#### Crear un usuario
```sh
$ adduser Nombre-Usario
```
#### Dar permisos administrativos a un usuario
```sh
$ sudo adduser Nombre-Usario sudo
```
#### Borrar un usuario
```sh
$ deluser Nombre-Usario
```
#### Crear un grupo
```sh
$ addgroup Nombre-Grupo
```
#### Eliminar un grupo
```sh
$ delgroup Nombre-Grupo
```
----
#### Listar carpetas
```sh
$ ls
```
#### Listar carpetas ocultas
```sh
$ ls -a
```
#### Entrar a un directorio (carpeta)
```sh
$ cd Nombre-Directorio
```
#### Salir de un directorio
```sh
$ cd ..
```
---
#### Crear un directorio (carpeta)
```sh
$ mkdir Nombre-Carpeta
```
#### Crear un directorio oculto (carpeta)
```sh
$ mkdir .Nombre-Carpeta
```
#### Eliminar un directorio (carpeta)
```sh
$ rm -r Nombre-Carpeta
```

#### Cambiar nombre de un directorio (carpeta)
```sh
$ mv Nombre-Carpeta/ Nuevo-Nombre 
```
#### Copiar un directorio (carpeta)
```sh
$ cp -r Nombre-Carpeta/ Nombre-Copia 
```

---

#### Crear archivos
```sh
$ touch Nombre-Archivo.txt 
$ touch Nombre-Archivo.html
$ touch Nombre-Archivo.css
$ touch Nombre-Archivo.js  
etc ... 
```

#### Cambiar nombre del archivo
```sh
$ mv Nombre-Archivo.txt Nuevo-Nombre-Archivo.txt
```
#### Copiar archivo
```sh
$ cp Nombre-Archivo.txt Nuevo-Nombre-Copia.txt
```
#### Eliminar un archivo
```sh
$ rm Nombre-Archivo.txt 
```
#### Editar un archivo
```sh
$ vim Nombre-Archivo.txt 
```
#### Ver el contenido de un archivo
```sh
$ cat Nombre-Archivo.txt 
```
---
#### Actualizar lista de paquetes
```sh
$ apt-get update
```
#### Actualiza paquete
```sh
$ apt-get upgrade 
```
#### Eliminar paquete
```sh
$ apt-get remove Nombre-Paquete
```
#### Eliminar paquete y sus archivos de configuracion
```sh
$ apt-get purge Nombre-Paquete
```

#### Comprimir una carpeta
```sh
$ tar -zcvf nombre-archivo.tar.gz nombre-carpeta
```

---

#### Reiniciar sistema
```sh
$ sudo reboot
```

#### Crear llave SSH RSA 4096 a un usuario
```sh
$ ssh-keygen -t rsa -b 4096 -c "Nombre-Usuario"
```

--- 
















