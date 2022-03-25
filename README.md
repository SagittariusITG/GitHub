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
