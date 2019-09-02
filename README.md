# Repositorios administrados

Practica para repasar y practicar como se crean y suben los controles de versiones en diferentes hosting de
repositorios.

## Getting Started

Este archivo es creado para demostrar con ejemplos como se crean los repositorios para distintos hosting (github,gitlab,BitBucket)

### Prerequisites

Se requerira tener instalado git en la computadora para el caso de linux ejecutar lo siguiente

    sudo apt update
    sudo apt install git


## Running the tests

Los siguientes comandos sirven para la subida de archivos y commits para

    - [GitHub]  
        git init
        git add README.md
        git commit -m "first commit"
        git remote rename origin github-origin
        git remote add origin git@github.com:Bunyzilla/video-club.git
        git push -u origin master

    - [GitLab]  (Repositorio Existente)
        git remote rename origin gitlab-origin
        git remote add origin git@gitlab.com:Bunyzilla/video-club.git
        git push -u origin --all
        git push -u origin --tags

    - [Bitbucket] (Repositorio Existente)
        > git remote rename origin bitbucket-origin
        > git remote add origin git@bitbucket.org:Bunyzilla/video-club.git
        > git push -u origin master



## Built With

* [VisualStudioCode](https://code.visualstudio.com/) - Code editing.Redefined.

## Authors

* **Flor Alejandra Legarda Araujo** - *Initial work* - [VideoClub](https://github.com/Bunyzilla/video-club)

## License

This project is licensed under the MIT License.
