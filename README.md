Santiago San Román  
*[santi72alc@gmail.com](mailto:santi72alc@gmail.com)*  
Enero 2020


# <center>Práctica DevOps
## <center>Configuración de servidores y despliegue de aplicaciones

***

En esta práctica se realiza la configuración de un servidor y el despliegue de dos aplicaciones en el mismo.

En esta práctica se hace uso de un servidor activo en AWS (*Amazon Web Services*) con un volumen de HD de 8GB, en la cual se alojan nuestros elementos necesarios para la elaboración y comprobación de la práctica.

Para la práctica, por una parte, se ha clonado y configurado una aplicación de chat "(github) [Node-Chat](https://github.com/igorantun/node-chat)" y, por otra parte, se utiliza la aplicación aportada para el módulo "(github) [Desarrollo de backend con NodeJS](https://github.com/Santi72Alc/04-practicaNodeJSBasico)" del curso realizado actualmente "Full Stack Web Developer VII" de Keepcoding, usando en ella el gestor/motor de BD "[Mongo database](https://www.mongodb.com/es)" y ficheros estáticos.

***Aplicación 1. Node-Chat.***
>Se despliega una aplicación clonada que ejecuta un chat en pleno funcionamiento. 
A esta aplicación se accede mediante el nombre del dominio asignado a tal efecto.  
Acceso (por DNS): [Node-Chat](http://ec2-18-217-159-220.us-east-2.compute.amazonaws.com)  

***Aplicación 2. myShop.***
>Es desplegada la aplicación del ejercicio de backend con node realizada durante el curso 2019.
Esta aplicación se despliega practicando y utilizando el uso de distintas características del servidor nginx.
La configuración del servicio se realiza de manera que los ficheros estáticos sean servidos por el propio servicio nginx, liberando así al servidor de la propia aplicación (express).

> Utilizamos tambien en esta aplicación un motor de base de datos ([MongoDB](https://www.mongodb.com/es)), el cual configuramos para que dé soporte de los datos necesarios a dicha aplicación.

>El fichero estático más notable servido en estático para esta aplicación es [index.jpeg](https://github.com/Santi72Alc/04-practicaNodeJSBasico/blob/master/public/images/index.jpeg) que se carga en la página inicial de la app.  
Acceso (por IP): [myShop](http://18.217.159.220/)

**Acceso a la práctica :**  
Dirección DNS (IPv4) : [ec2-18-217-159-220.us-east-2.compute.amazonaws.com](http://ec2-18-217-159-220.us-east-2.compute.amazonaws.com)  
Dirección IP : [18.217.159.220](http://18.217.159.220) 
