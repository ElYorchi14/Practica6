# Practica 8 Jorge Alberto Palacios Burguete

## ¿Cómo se inicializa un repositorio en Git?
Se crea con el comando git init

```bash
git init
```

## ¿Cómo creas un repositorio en GitHub?
En la página de github hay una sección arriba a la derecha que te permite crear un nuevo repositorio

## ¿Cómo vinculas un repositorio local de Git con uno remoto de GitHub?

```bash
git remote add origin https://github.com/usuario/repositorio.git
git push -u origin main
```

Agregas el link del repositorio al lado del comando git remote add (link) origin después pusheas al origin y ya estaría

## ¿Cuál es el flujo básico de trabajo en Git y GitHub?
Primero es el working directory luego el staged, luego commited y el último es el remoto

## ¿Para que sirve el archivo .gitignore?
Te sirve para ignorar un tipo de archivo y que no se vea en el repositorio, ya sea por nombre de archivo o por tipo de extención

## ¿Cuál es el proposito de una rama?
Dividir la carga de trabajo en distintas ramas para no afectar la rama main o principal

## ¿Qué es una fusión?
Es la forma de unir dos ramas diferentes

## Explica los diferentes tipos de fusión que existen
Está el fast-forward que hace la función automaticamente y también el manual merge con este tenemos que hacer la fusión manualmente de la manera en la que querramos que se unan las ramas

## ¿Cómo puedes ver el historial de tu repositorio?
Con el comando git log que nos muestra de manera detallada los commits hechos en todas las ramas

```bash
git log
```
También existe git log --oneline que te muestra un poco menos de información pero te dice el nombre de los commits

```bash
git log --oneline
```
## ¿Cuál es el proposito de una etiqueta?
Es para darle una versión a nuestro proyecto con el comando git tag (Versión)

```bash
git tag v1.0.0
```