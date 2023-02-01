# **Control de la fuente usando Git y GitHub**
---
#### **Pregunta Examen: ¿Qué es un control de fuente o control de versiones?**
#### **Pregunta Examen: ¿Qué es commit?**
#### **Pregunta Examen: explicar commit con ejemplo del mundo real**
---
---


## **Objetivos**
---
>* Explicar el control de la fuente y por qué es importante 
>* Explicar y usar Git.
>* usar **GitHub**  para crear una cuenta personal para una cartera de proyectos.
>* Explicar y usar los comandos principales.
>* Usar **ramas de función** para implementar cambios de código.
>---
---
## **¿Qué es cun control de versiones?**
---
> El control de versiones, también conocido como **"control de código fuente"**, es la práctica de **rastrear y gestionar los cambios** en el código de software. 
> 
> Los *sistemas de control de versiones* son **herramientas de software** que **ayudan** a los equipos de software a gestionar los cambios en el código fuente **a lo largo del tiempo**. 
> 
> A medida que los entornos de desarrollo se aceleran, los sistemas de control de versiones ayudan a los equipos de software a trabajar de forma más rápida e inteligente. Son especialmente útiles para los equipos de DevOps, ya que les ayudan a reducir el tiempo de desarrollo y a aumentar las implementaciones exitosas.
> 
> El software de control de versiones realiza un seguimiento de todas las modificaciones en el código en un tipo especial de base de datos. Si se comete un error, los desarrolladores pueden ir hacia atrás en el tiempo y comparar las versiones anteriores del código para ayudar a resolver el error, al tiempo que se minimizan las interrupciones para todos los miembros del equipo.
---
## **¿Qué es Git?**
---
#### **Linus Torvalds**: ingeniero de software finlandés-estadounidense,2​ conocido por iniciar y mantener el desarrollo del kernel (en español, núcleo) Linux, basándose en el sistema operativo libre Minix creado por Andrew S. Tanenbaum y en algunas herramientas, varias utilidades y los compiladores desarrollados por el proyecto GNU. Actualmente es responsable de la coordinación del proyecto. También ha desarrollado el software de control de versiones Git. 
---
## **Para configurar Git**
---
Pasos 1 y 2 para definir quien esta trabajando
1. ***git config --global*** user.name "Nombre de Usuario".
2. ***git config --global*** user.email example@gmail.com
   * **git config --list** para ver si esta configurado
  ---
3. ***git init*** para convertir mi carpeta local en un respositorio
   * aparecera en la carpeta una etiqueta *master/main*
   * quiere decir que es una **rama**
4. ***git status*** para saber que hay dentro del respositorio.
5. ***git add nombreDelArchivo.extension*** para agregar el archivo (**staging area**).
6. ***git commit*** para tomar la captura 
7. ***git commit -m "[Más el comentario de actualización]"*** para colocar un comentario de actualización en la rama master/main. Se le asignará un identificador. Y aparecerá un mensaje de confimación como se muestra acontinuación:
   
  ```
   [main (root-commit) 1ab1474] Mi primer actualización, se crea hallo.js
 1 file changed, 5 insertions(+)
 create mode 100644 hallo.js 
 ```
---
8. ***git log***  para tener informacion de los comentarios realizados
9. ***git checkout*** es para saltar a una actualización en el tiempo
10. 




---
## ****
---

---