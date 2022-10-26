# Codenotch - Retos GIT - Día 6 
Projects for the bootcamp

## by **Roxy**
### **Instrucciones para subir proyecto a Github**
 

- Para subir un proyecto previamente creado en local hay que hacer lo siguiente: 


1. Abrir un terminal en el directorio donde se encuentra nuestro proyecto e iniicar GIT con el siguiente comando: 

    <code>git init</code>

2. Se habrá creado una carpeta **.git** con la información del proyecto que hemos creado. 
    Luego añadimos los ficheros o directorio que vamos a subir al hub con: 

    <code>git add . </code>

    - Si es un único fichero se puede hacer con: 
         <code>git add nombredelfichero</code>

3. Confirmamos los cambios que vamos a subir con una breve explicación de los cambios realizados.

     <code>git commit -m “Creado el proyecto inicial” </code>

4. Subiremos los cambios a GitHub. Para ello debemos saber la ruta del repositorio (acabada en .git) al que vamos a subir el proyecto. Este repositorio debe estar creado previamente en GitHub a tráves de su web.  Luego, enlazaremos nuestro repositorio local con el repositorio remoto desde la terminal con: 

    <code>git remote add origin URLrepositorio.git </code>

5. Subiremos entonces los cambios con el siguiente comando: 

    <code>git push origin master </code>