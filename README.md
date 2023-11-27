# Se añade un DNS al Docker Compose y se colocan IPs fijas a los contenedores. Además se le coloca el prefijo ***"asir_"*** al nombre de los contenedores

![ Adición del DNS al compose ](./imagenes/1.png)

# El DNS resuelve dos dominios a la IP del apache:

![ Primer Dominio ](./imagenes/2.png)

![ Segundo Dominio ](./imagenes/3.png)

# Se configuran dos Virtual-Hosts separados para cada dominio en el mismo puerto (2000)

![ Primer VirtualHost ](./imagenes/4.png)

En el segundo host se emplea la directiva de **DirectoryIndex** para indicarle al host que el **"Index"** se llamará ***"hola.html"***

![ Segundo VirtualHost ](./imagenes/5.png)










