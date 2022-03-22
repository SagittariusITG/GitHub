# Manejo de git por comandos

Lo primero es entrar en la carpeta que queramos enlazar con GitHub.

> Para crear un repositorio.

```sql
git init
```

> Para crear rama.

```sql
git branch -M [rama]

git remote add origin [url]
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

git commit -a -m [comentario] -- Desde el archivo sin preparar.
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