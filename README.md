## Despliegue de apps Spring Boot en Heroku

Crear archivo system.properties en el proyecto con el contenido:

java.runtime.version=18

1. Crear cuenta en heroku.com y github.com
2. Tener configurado git en el ordenador 
     1. git config --global user.name "jorgegomez"
     2. git config --global user.email jorgegomez.dev@gmail.com
3. Subir el proyecto a GitHub desde IntteliJ IDEA desde la opcion: a VCS > Share Project on GitHub
4. Desde Heroku, crear la app y elegir metodo GitHub y buscar el respositorio subido
5. Habilitar deploy automatico y ejecutar el Deploy 