# backend-development

### La unión entre el Frontend y el Backend se hace a través de una API: Application Programming Interface.
### Una API es una sección del backend que permite que el frontend pueda comunicarse con él a través de mensajes bidireccionales (de ida y vuelta).

## Tenemos dos grandes estándares para crear las APIs:
<ul>
  <li><strong>SOAP</strong>(Simple Objetct Access Protocol): Mueve la información a través de un lenguaje XML (Extensible Markup Language). Es similar al HTML, es un lenguaje de marcado. SOAP es un protocolo que ha quedado en el olvido.</li>
  <li><strong>Rest</strong> (Representational State Transfer): Utiliza otro lenguaje JSON (Javascript Objet Notation). Un JSON no es más que un diccionario de Python. Los diccionarios de Python son lo mismo que los objetos de JS.</li>
</ul>

<h3>El lenguaje que habla internet: HTTPS(Hypertext Transfer Protocol o protocolo de transferencia de hipertexto)</h3>
<p>En el internet siempre tenemos dos partes que se comunican, tanto clientes como servidores.
  -->El cliente son todos los dispositivos al alcance de nuestra mano(computadora, tablet, smarthphone)
  -->El servidor es una computadora que esta prendida 24/7 y es la que contiene la aplicacion que se va a ver en el lado del cliente.<br>
  Esta transferencia de informacion se realiza siempre con una peticion(request) por parte del cliente y una respuesta(response) por parte del servidor.
</p>

<p>Por ejemplo entro a google y quiero ir a una pagina web en particular, asi cumplo el papel de cliente y lo que hago
   es una peticion al servidor(computadora que tiene la aplicacion web) que me traiga dicha aplicacion web para que yo pueda visualizar(respuesta por parte del servidor a la peticion). Esta es la comunicacion que sucede entre cliente-servidor, el dispositivo se comunica con el servidor y trae la informacion.
</p>


### Otros protocolos:
  ~ IP: Internet Protocol, es el protocolo fundamental gracias al cual funciona internet. Le da una direccion particular a mi computadora para que pueda ser encontrada en la red.

  ~ TCP, UDP: Transmition Control Protocol, User Datagram Protocol, estos sirven para transmitir datos a traves de la IP.

  ~ TLS: Transport Leayer Security(seguridad de la capa de transporte), sirve para que los datos viajen de manera segura. 

  ~ DNS: Domain Name System(sistema de nombres de dominio), sirve para convertir una direccion IP(que viene del primer protocolo) en un Dominio(nombre de la web -> platzi.com)

  ~ HTTP: Este protocolo corre por encima de los anteriores, permite transferir la informacion entre cliente-servidor por medio de IP,TCP, TLS, UDP y DNS
  Esta informacion puede venir de varias formas, HTML, CSS, JS o APIs(aplication program interfaces).