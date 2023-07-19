---
title: Tutorial Bash
author: Cristian Segura
date: mar 18 jul 2023 14:16:50 -04
---


# Tutorial Bash




# 1. Introducción

**¿Qué es Bash?**

Bash es una interfaz de línea de comandos utilizada inicialmente (o Shell)




* https://es.wikipedia.org/wiki/Bash


# 2. Comandos & Aplicaciones Útiles

# 2.0  El prompt de Bash

Al entrar a un terminal ejecutando Bash aparece una lína similar a la que se muestra:

~~~{.bash}
csegura@csegura-VirtualBox:~$
~~~

Al imprimir esta línea, llamada "línea de comando" (en inglés *command line*), el sistema nos está indicando que se encuentra a la espera que escribamos algún comando. Pero antes de escribir nada es interesante entender el significado de la línea que estamos viendo.


En la línea de comando se puede observar, en la mayoría de los casos, la siguiente sintaxis:

~~~{.bash}
<user>@<hostname>:~$
~~~


Los campos que aparecen son:

* El campo `<user>` indica el nombre del usuario actual.
* El símbolo de arroba `@` (llamado `at` en inglés) significa `en` o `dentro de`.
* El campo `<hostname>` indica nombre del host (o *hostname* en la jerga de redes de computadoras) es el nombre que se le asigna a la computadora que está corriendo Bash. En general este nombre puede ser cualquier tira de caracteres. Nombres típicos son: `localhost`, `ubuntu`, `lnxsrv`, etc.. (básicamente cualquier nombre se le quiera dar a la máquina). Es interesante notar que `<user>@<hostname>` le recuerda que se encuentra en la máquina llamada `<hostname>` utilizando el usuario `<user>`.
* El símbolo virgulilla `~` indica que nos encontramos en el directorio `HOME` del usuario `<user>`. Veremos más en detalle este punto cuando revisemos los comandos para navegar por el sistema de archivos.
* El símbolo virgulilla `$` : este símbolo que se termina el prompt y que todo lo que está a la derecha es un comando que se le estará ingresando a Bash.

Por ejemplo cuando abro una terminal con Bash aparece el siguiente prompt:


~~~{.bash}
csegura@csegura-VirtualBox:~$
~~~





# 2.1  Sistema de Archivos

* `pwd` : imprime (*print*) el nombre del directorio actual (*working directory*)

~~~{.bash}
csegura@csegura-VirtualBox:~$ pwd
/home/csegura
~~~



* ls:


# 2.1  Sistema de Archivos









# Referencias

* Wikipedia Bash; https://es.wikipedia.org/wiki/Bash
* Wikipedia Prompt; https://es.wikipedia.org/wiki/Prompt
* Wikipedia Virgulilla; https://es.wikipedia.org/wiki/Virgulilla



