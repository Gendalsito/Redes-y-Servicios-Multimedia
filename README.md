# Redes-y-Servicios-Multimedia
Proyectos interesantes hechos en esta materia.

Parcial final de RySM, Servidor montado en una maquina Linux creado en VirtualBox (esto no esta en este repositorio) en la cual se despliega los datos arrojados por el objeto inteligente diseñado en proteus, usando la comunicación por puerto serial gracias a la aplicación VSPE ( Virtual Serial Ports Emulator), estos datos son recibidos en el proyecto creado en NetBeans JavaArduino En el cual se reciben estos datos usando el puerto serial COM 4, y con esto enviar los datos a una plataforma IoT (En este caso ThingSpeak).

En el servidor web montado, se visualizan los datos que tienen alojados la plataforma IoT usando una petición de HTTP gracias al protocolo REST montado en java

Proyecto Final

Exactamente lo mismo que el parcial solo que en este caso el servidor web fue montado en AWS y no en una máquina virtual. (Aquí se usó ubidots creando 3 nodos, prueba,nodo1 y nodo2 para que cada uno de los integrantes del grupo subiera datos desde su computador usando la simulación creada en proteus).
También se creo una pagina web en la que se visualizan los datos que se encuentran en ubidots.

Notas:


En el Arduino del proteus siempre se busca un archivo ino.hex el cual se crea al construir la lógica que queremos que sigan nuestros sensores en la IDE de Arduino, para esto es importante que en Arduino ir a : Archivo->Preferencias y en la parte inferior aparecerá un enlace con la ruta del "Preferences.txt" si queremos que esta ruta sea diferente debemos añadir en el archivo de preferencias el comando build.path con la ruta en la que queremos que se encuentre nuestro HEX, pero al hacer esto es importante CERRAR LA IDE DE ARDUINO ya que si se tiene abierta se creara siempre en el lugar por defecto y no se guardara lo que se haya hecho en el archivo de preferences.txt.


