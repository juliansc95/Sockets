# Sockets
Segunda parte taller jugando con Sockects

Integrantes: 
Julian Andres Silva - 1325577 <br>
Johan Andres Garzon - 1325214 <br>
Johan Andres Benavides -1323294 <br>

Proposito de los programas:

socket-02.py : Se crea un socket de tipo IPv4 y orientado a conexion TCP,se puede mostrar un mensaje de error en caso de que el socket no se pueda crear,  tomamos la ip del host www.google.com y la almacenamos en una variable llamada remote_ip, se puede generar un mensaje de error en caso de que no se pueda obtener el hostname, y al final mostramos en pantalla un mensaje donde se ve el nombre del host y su direccion IP

socket-03.py : Ademas de lo anterior, se agrega que se conecta el socket al host (www.google.com) y se muestra en pantalla un mensaje mostrando que la conexion fue correcta

socket-04.py : Agregando lo de los 2 progamas anteriores, se añade que se envia un mensaje al servidor y se muestra un mensaje si el mensaje fue enviado con exito, si no se genera un mensaje de error.

socket-05.py : Se tiene lo de los pogramas anteriores y ademas se agrego una parte donde se obtiene respuesta del servidor y se imprime en pantalla dicha respuesta

Para ejecutar estos programas es: python "nombre del archivo"


echo-client.py : Se crea un socket de tipo IPv4 y con protocolo TCP el cual envia un mensaje a un servidor y despues recibe la respuesta del servidor, imprime en pantalla el mensaje y cierra la conexion.

Para ejecutarlo el comando es: python echo-client.py --port 2048


echo-server.py : Se crea un socket de tipo IPv4 y con protocolo TCP que sirve como servidor, el cual recibe el mensaje de los clientes, los replica,lo envia de vuelta al cliente y muestra en pantalla el mensaje y al final cierra la conexion con el cliente.

Para ejecutarlo el comando es: python echo-server.py --port 2048 

Primero se debe ejecutar el echo-server.py y luego echo-client.py
