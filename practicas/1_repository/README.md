# Práctica 1: Repository

## Fecha: 21/09/2020

## Temas

* Git
* GitHub

## Recursos

[RepositoryPresentacion.pdf](RepositoryPresentacion.pdf) es la presentación utilizada durante la clase para explicar el uso básico de Git y GitHub.

[Practica1_Repository.md](Practica1_Repository.md) es el archivo que contiene las instrucciones de la práctica que tendrás que llevar a cabo.

### Pre-requisitos

Esta práctica requiere que cuentes con una cuenta en GitHub, así como que cuentes con la última versión de Git configurada y sincronizada con tu cuenta de GitHub. Para lograrlo puedes seguir los siguientes pasos:

* Descargar la última versión de Git desde [el sitio oficial](https://git-scm.com/downloads) para tu sistema operativo.
* Crear una cuenta gratuita en [GitHub](https://github.com/) con tu correo electrónico (ya sea el personal o el institucional).
* (**Opcional**) Descargar GitHub desktop desde [el sitio oficial](https://desktop.github.com/).
* Configurar Git con tus credenciales de GitHub. Para lograrlo tienes que hacer lo siguiente:
  - Abre una terminal/símbolo del sistema y ejecuta el siguiente comando `git config --global user.name "usuario"` cambiando `usuario` por el usuario de tu cuenta de GitHub. Puedes ver más información sobre este proceso [en este sitio de GitHub](https://docs.github.com/en/github/using-git/setting-your-username-in-git).
  - Una vez que tengas tu usuario, tendrás que seguir un procedimiento similar para tu correo electrónico, ejecutando el comando `git config --global user.email "tucorreo@dominio.com"` con el correo correspondiente a tu cuenta de GitHub. Si quieres más información sobre este proceso puedes encontrarla en [este sitio de GitHub](https://docs.github.com/en/github/setting-up-and-managing-your-github-user-account/setting-your-commit-email-address).

  Si tienes dificultades, puedes visitar [este sitio de GitHub](https://docs.github.com/en/github/getting-started-with-github/set-up-git) con la documentación oficial del proceso.

Una vez que cuentes con estos requisitos podrás llevar a cabo la primera práctica del curso.

## Sitios de interés

* [Especificaciones básicas del lenguaje de marcado MarkDown en GitHub.](https://docs.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax)
* [Especificaciones para sincronizar Git con tu cuenta de GitHub.](https://docs.github.com/en/github/getting-started-with-github/set-up-git)
* [Especificaciones para instalar GitHub Desktop en tu computadora.](https://docs.github.com/en/desktop/installing-and-configuring-github-desktop/setting-up-github-desktop)
* [Almacenar las credenciales de GitHub en la memoria de tu computadora.](https://docs.github.com/en/github/using-git/caching-your-github-credentials-in-git)

## Recursos adicionales
#### Comandos de Git

|Acción|Comando|
|--|--|
|Clonar un repo de GitHub|`git clone <GHRepoURL> <path>`|
|Añadir un archivo al siguiente *commit*|`git add <filename>`|
|Añadir todos los archivo al siguiente *commit*|`git add --all`|
|Hacer un *commit* (guardar una versión)|`git commit -m "<message>"`|
|Hacer un *push* (subir cambios a GitHub)|`git push <GHRepoURL>`|
|Hacer un *pull* (descargar cambios desde GitHub)|`git pull <GHRepoURL>`|

Para más información sobre su uso puedes visitar [este sitio](https://github.com/git-guides/git-init) con los comandos básicos de Git para GitHub.
