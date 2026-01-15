# Usuarios y permisos en Linux

La gestión de usuarios y permisos es un concepto fundamental en Linux y un pilar básico para la seguridad del sistema.

## Usuarios en Linux
Linux es un sistema multiusuario. Cada usuario tiene permisos específicos que determinan qué acciones puede realizar.

- `root` → usuario con privilegios totales
- Usuarios estándar → usuarios con permisos limitados

Comandos útiles:
- `whoami` → muestra el usuario actual
- `id` → muestra UID, GID y grupos
- `su` → cambiar de usuario
- `sudo` → ejecutar comandos con privilegios elevados

## Permisos de archivos
Cada archivo y directorio tiene tres tipos de permisos:
- Lectura (`r`)
- Escritura (`w`)
- Ejecución (`x`)

Y se aplican a:
- Usuario propietario
- Grupo
- Otros usuarios

Ejemplo:

-rwxr-xr--
- Usuario: `rwx`
- Grupo: `r-x`
- Otros: `r--`

## Modificación de permisos
- `chmod` → cambiar permisos
- `chown` → cambiar propietario
- `chgrp` → cambiar grupo

Ejemplo: chmod 755 archivo.sh


## Importancia en ciberseguridad
Una mala gestión de permisos puede permitir accesos no autorizados o escaladas de privilegios.  
Comprender cómo funcionan los usuarios y permisos es esencial para asegurar sistemas Linux.

---

📌 Apuntes creados como parte del aprendizaje inicial de Linux orientado a ciberseguridad.
