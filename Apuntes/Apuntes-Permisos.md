# Sistema de Permisos

Chmod es una llamada al sistema y su comando asociado en el sistema operativo UNIX que permite cambiar los permisos de acceso de un fichero o directorio.

#### [ Archivo ] Acceso total a todos
```sh
$ chmod 777 Nombre-Archivo
```

#### [ Archivo ] Acceso total al dueño - Lectura y Escritura para los demas
```sh
$ chmod 766 Nombre-Archivo
```

#### [ Archivo ] Acceso total al dueño - Solo Lectura para los demas
```sh
$ chmod 744 Nombre-Archivo
```

#### [ Archivo ] Acceso total al dueño - Sin permisos para los demas
```sh
$ chmod 700 Nombre-Archivo
```

---

#### [ Directorio ] Acceso total a todos
```sh
$ chmod 777 Nombre-Directorio
```

#### [ Directorio ] Acceso total al dueño - Lectura y Escritura para los demas
```sh
$ chmod 766 Nombre-Directorio
```

#### [ Directorio ] Acceso total al dueño - Solo Lectura para los demas
```sh
$ chmod 744 Nombre-Directorio
```

#### [ Directorio ] Acceso total al dueño - Sin permisos para los demas
```sh
$ chmod 700 Nombre-Directorio
```

#### [ Directorio ] Acceso total al dueño - Solo pueden entrar los demas
```sh
$ chmod 711 Nombre-Directorio
```