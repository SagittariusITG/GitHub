# Manejo de git por comandos

Lo primero es entrar en la carpeta que queramos enlazar con GitHub.

> Para crear un repositorio.

```
git init
```

> Para clonar un repositorio.

```
git clone [url]
```

> Ver el estado del repositorio

```
git status
```

> Para preparar los documentos modificados.

```
git add [archivo]
```

> Para hacer commits.

```
git commit -m [comentario]

git commit -a -m [comentario] -- Desde el archivo sin preparar.
```

> Para subr a GitHub.

```
git psuh [url] -- Crea una rama nueva.

git remote -u origin [url]

git push -u origin [rama]

git push -- Si la rama está especificada.
```