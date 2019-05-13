# lifebank
Repositorio para almacenar los avances alcanzados prueba Desarrollador.

/*=======================================================================================
======== Instrucciones Generales. ======================
========================================================================================*/

Para el correcto funcionamiento del servicio de Lifebank-authentication-svc se requiere: 

1. Tener instalado Lombok, en su ordenador o en el contenedor donde se hará el despliegue. 
2. Crear una base de datos postgres 9.6 con el nombre: "lifebank"
3. Ejecutar los script de la carpeta "lb_op_autenticacion" en el orden enumerado 1,2 y 
   para el script 3 se debera de reemplazar "[usuario_a_conceder_permisos]" con el nombre del usuario_a_conceder_permisos, 
   no es necesario la ejecucion del script 3 si se ejecutara de forma local. 
4. importar el proyecto como maven project en el ide de su preferencia. 
5. En la carpeta de entrega se encuentra otro directorio donde se encuentra el listado de 
   usuario registrados en la base de datos en la ruta: "\Sql\Lista de Usuarios". 
6. En el directorio "\Json" , se encuentran la dirección  del endpoint y los json de Request 
   y response del servicio.
7. Se deberá de ejecutar el request Post desde Insomnia, Postman o cualquier otra herramienta 
   que permite realizar peticiones HTTP al API, con el formato descrito en la carpeta antes 
   mencionada, no olvidar proveer el valor "ipAddress:" en el header con la direccion IP.
8. Listo.

Nota: - si no se ejecuta el algorito SHA-512, debera proceder a modificar las configuraciones de su jre 
	  que se encuenta ubicado en la siguiente ruta: "C:\Program Files (x86)\Java\jre1.8.0_171\lib\security" ó 
	  en donde tenga instalado JAVA y se reemplazar con los archivo del zip ubicado en la carpeta utiles, ubicado en 
	  la carpeta de entregada.
      - Los archivos de sql de la carpeta "lb_operaciones", son los archivos del esquema completo de la base de datos central del banco,
	no es necesario ejecutar para el funcionamiento del servicio, pues servirá como repositorio general de la información que manejen 
	todos los servicios descritos en el diagrama Arquitectura de Servicios.

Atentamente,
Salvador René Cruz López. 
SRCRUZ




   
