# Línea de comandos Linux

## Comando **printf** y comando **echo**

## Comando **pwd**

Usamos el comando **pwd** para imprimir el directorio actual

**Input**
```bash
$ pwd
```

**Output**
```bash
/workspaces/carlosp-11-cmline
```
***

## Comando **ls**

Usamos el comando **ls** para imprimir el contenido del directorio actual. 

**Input**
```bash
$ ls
```

**Output**
```bash
README.md
```

Podemos agregar la opción **-l** para imprimir un elemento por línea (además esta forma de impresión incluye las propiedades de los archivos), o la opción  **-a** para imprimir también los archivos ocultos. Se pueden usar selectores "*" para filtrar los resultados, por ejemplo:

**Input**
```bash
$ ls .*
```

**Output**
```bash
.:
README.md

..:
carlosp-11-cmline

.git:
FETCH_HEAD  HEAD  branches  config  description  hooks  index  info  lfs  logs  objects  packed-refs  refs
```

***
## Comando **cat** 

Usamos **cat** para imprimir el contenido de un archivo de texto.

***
## Comando **rm**

Empleamos el comando **rm** para eliminar archivos. Si añadimos la opción -R, eliminará recursivamente todos los archivos del directorio.

***
## Comando **cd**

Empleamos el comando **cd** para cambiar de directorio indicando la ruta exacta a la que queremos dirigirnos. Si sólo queremos subir un nivel, usamos el comando añadiendo dos puntos: **cd ..**

***

## Comando **cp**

Usamos este comando para copiar uno o varios archivos o directorios en el directorio actual o en otro directorio cuya ruta especifiquemos.

**Input**
```bash
$ cp README.md /otraCarpeta/hola.md
```

***

## Comando **mv**

Este comando funciona para mover archivos de un directorio a otro. En caso de mover el archivo al mismo directorio de origen este comando se puede usar para renombrar un archivo.

***

## Comando **mkdir**

Usamos este comando para crear un directorio nuevo dentro del directorio actual.

***

## Comando **find**

Empleamos este comando para buscar un archivo. Requiere de parámetros como **-type f** para indicar que es un archivo y **-name "nombreDelArchivo"** apra indicar el nombre del archivo.

***

## Comando **clear**

Utilizamos este comando para despejar la pantalla.