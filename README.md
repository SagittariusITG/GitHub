# Manejo de git por comandos

Lo primero es entrar en la carpeta que queramos enlazar con GitHub.

> Para crear un repositorio.

```sql
git init
```

> Para crear rama.

```sql
git branch -M [rama] -- Renombrar rama.

git remote add origin [url]

git branch -d [rama] -- Eliminar rama (La une con la main a menos que estemos en esa rama).

git branch -D [rama] -- Eliminar forzado.
```

> Mostrar ramas.

```sql
git branch -- Ver las ramas.
```

> Para cambiar de rama.

```sql
git checkout [rama]
```

> Para clonar un repositorio.

```sql
git clone [url]
```

> Ver el estado del repositorio

```sql
git status
```

> Para preparar los documentos modificados.

```sql
git add [archivo]
```

> Para hacer commits.

```sql
git commit -m [comentario]

git commit -a -m [comentario] -- Desde el archivo sin preparar (sin el add).
```

> Para subr a GitHub.

```sql
git psuh [url] -- Crea una rama nueva.

git remote -u origin [url]

git push -u origin [rama]

git push -- Si la rama está especificada.

git push -u origin main -- Para subir archivo una vez creado una rama.
```

> Para ver todos los registros (modificaciones etc)

```sql
git log -- Ver commits.

git log -p -- Ver commits + detalles.

git log -1 -- para ver el último registro.
```

> Detalle de las modificaciones

```sql
git diff
```

# Teoria git

> ¿Qué es un controlador de versiones?

```
Un control de versiones es un sistema que registra los cambios realizados en un archivo o conjunto de archivos a lo largo del tiempo, de modo que puedas recuperar versiones específicas más adelante.
```

> Tipos de controles de versiones.

* Sistemas de Control de Versiones Locales.

```
Realizado por mucha gente y basado en copiar varias veces el archivo.
```

* Sistemas de Control de Versiones Centralizados.

```
Estos sistemas tienen un único servidor que contiene todos los archivos versionados y varios clientes que descargan los archivos desde ese lugar central.
```

* Sistemas de Control de Versiones Distribuidos.

```
En estos sistemas los clientes no solo descargan la última copia instantánea de los archivos, sino que se replica completamente el repositorio.
```

> Estados de git.

* Confirmaddo → Datos almacenados de manera segura en BD local.
* Modificado → Modificado, falta confirmar en la BD local.
* Preparado → Archivo marcado como modificado en su versión actual listo para confirmar.
