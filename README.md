# Reading_Notes_Class03

En el mundo de la programación la gestión de versiones es fundamental para garantizar un flujo de trabajo fluido y colaborativo, el versionamiento local, remoto y distribuido son componentes esenciales para un mejor desarrollo de proyectos.
En esta oportunidad vamos a comprender los conceptos de versionamiento local, remoto y distributivo.
## Desarrollo
### El versionamiento local:
Se refiere al proceso de controlar y gestionar las versiones de un proyecto dentro de un terminal local. 
### El versionamiento remoto:
Esto implica la colaboración entre múltiples desarrolladores que trabajan en el mismo proyecto, pero desde ubicaciones diferentes. En este contexto, los repositorios remotos, alojados en plataformas como GitHub, juegan un papel importante ya que los desarrolladores pueden clonar e  enviar sus cambios a estos repositorios remotos.
```
git clone URL_del_repositorio_en_GitHub
```

### El versionamiento distribuido:
Como muestra en el papaer lleva a la colaboración un paso más allá, el cual permitie que cada desarrollador tenga una copia completa del repositorio en su terminal local. Esto significa que cada desarrollador tiene acceso a todo el historial de versiones y puede trabajar de forma independiente sin conexión a internet.

## Conclusión
En resumen, el versionamiento local, remoto y distribuido son aspectos esenciales de la gestión de versiones en el desarrollo de software. La herramienta Git y las plataformas de alojamiento de repositorios remotos, hace que los desarrolladores pueden colaborar de manera eficiente, rastrear cambios y mantener la integridad del proyecto.

## Preguntas

### ¿Qué es el control de versiones?
El control de versiones es un sistema que registra los todos cambios realizados en un conjunto de archivos a lo largo del tiempo, permitiendo rastrear, gestionar y revertir un cambios en el desarrollo de un proyecto, en el cual existen CVS, 

### ¿Qué es la "clonación" en Git?
La clonación en Git es el proceso de crear una copia exacta de un repositorio Git en un servidor remoto en tu máquina local.
```
git clone URL_del_repositorio
```
### ¿Cuál es el comando para rastrear y preparar archivos?
El comando para rastrear y preparar archivos en Git es git add.
```
git add nombre_del_archivo
```
### ¿Cuál es el comando para tomar una instantánea de los archivos modificados?
El comando para tomar una instantánea de los archivos modificados y prepararlos para un commit es git add ..
```
git add .
```
###¿Cuál es el comando para enviar los archivos modificados a GitHub?
El comando para enviar los archivos modificados al repositorio remoto en GitHub es git push.
```
git push
```
