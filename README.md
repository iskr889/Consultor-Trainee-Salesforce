Las siguientes preguntas están orientadas a la comprensión del protocolo HTTP. Son agnósticas al lenguaje 

de programación, la idea es comprender los conceptos del estándar: 
  

1. ¿Qué es un servidor HTTP? 

Es un software que se ejecuta en un servidor de computadora y que ofrece servicios de alojamiento de sitios y aplicaciones web a través del protocolo HTTP. Éste recibe solicitudes de los clientes y responde a las mismas enviando los recursos solicitados, como páginas web por ejemplo. 


2. ¿Qué son los verbos HTTP? Mencionar los más conocidos 

Son un conjunto de comandos que se utilizan en el protocolo HTTP para indicar la acción que se desea realizar en un recurso determinado. Cada solicitud se realiza utilizando uno de estos verbos, que se envía al servidor para que éste sepa qué acción realizar. Los verbos HTTP más conocidos son: GET, POST, PUT, DELETE y HEAD 


3. ¿Qué es un request y un response en una comunicación HTTP? ¿Qué son los headers? 

La comunicación entre un cliente y un servidor se realiza a través de una request (solicitud) y un response (respuesta). La solicitud es enviada por el cliente al servidor para solicitar un recurso o realizar una acción, mientras que la respuesta es enviada por el servidor al cliente para proporcionar el recurso o información solicitada.  

Por otro lado, los headers (encabezados) son campos que brindan información adicional en las solicitudes o respuestas. Los de solicitud indican autenticación, tipo de contenido, codificación de caracteres, etc. Los de respuesta indican el tipo de contenido, fecha/hora de la respuesta, servidor, etc.  


4. ¿Qué es un queryString? (En el contexto de una url) 

El queryString es la parte de la URL que sigue al signo de interrogación "?" y que contiene uno o más parámetros de búsqueda para solicitar información específica de un servidor web. 


5. ¿Qué es el response Code? ¿Qué significado tiene los posibles valores devueltos? 

Es un número de tres dígitos que indica el estado de la respuesta del servidor a una solicitud HTTP. Los códigos se dividen en cinco clases principales que representan diferentes rangos de números, ya que son una forma estandarizada de comunicar el resultado de una solicitud HTTP al cliente. 


6. ¿Cómo se envía la data en un Get y cómo en un POST? 

En una solicitud GET, la información se envía al servidor a través de la URL, mientras que en una solicitud POST, la información se envía en el cuerpo de la solicitud HTTP.  


7. ¿Qué verbo http utiliza el navegador cuando accedemos a una página? 
 
Cuando accedemos a una página web, el navegador utiliza el verbo HTTP GET para solicitar la página y recibir la respuesta del servidor. 


8. Explicar brevemente qué son las estructuras de datos JSON y XML dando ejemplo de estructuras posibles. 

JSON y XML son formatos de texto que se utilizan para intercambiar datos entre diferentes aplicaciones y sistemas. JSON es un formato de intercambio de datos que es fácil de leer y escribir para los humanos, y fácil de analizar y generar para las máquinas. Consta de pares de clave-valor, donde los valores pueden ser cualquier tipo de datos, incluidos otros objetos JSON. Por ejemplo: 

jsonCopy code 

{ 
   "nombre": "Juan", 
   "edad": 25, 
   "direccion": { 
      "calle": "Calle Mayor", 
      "numero": 5 
   }, 
   "telefonos": [ 
      { 
         "tipo": "movil", 
         "numero": "555-1234" 
      }, 
      { 
         "tipo": "casa", 
         "numero": "555-5678" 
      } 
   ] 
} 

Por otro lado, XML es un lenguaje de marcado que permite etiquetar elementos y atributos para describir datos. Es fácilmente legible por humanos y fácil de analizar por máquinas. Ejemplo: 

phpCopy code 

<persona> 
   <nombre>Juan</nombre> 
   <edad>25</edad> 
   <direccion> 
      <calle>Calle random</calle> 
      <numero>5</numero> 
   </direccion> 
   <telefonos> 
      <telefono tipo="movil">555-1234</telefono> 
      <telefono tipo="casa">555-5678</telefono> 
   </telefonos> 
</persona> 

 

9. Explicar brevemente el estándar SOAP 

SOAP es un protocolo estándar de comunicación basado en XML para intercambiar información estructurada entre aplicaciones web. Define un conjunto de reglas para el formato del mensaje, la codificación de los datos y el protocolo de comunicación entre el cliente y el servidor 


10. Explicar brevemente el estándar REST Full 

REST es un estándar para servicios web que utiliza URIs y métodos HTTP para manipular recursos. Se usa para crear servicios web escalables y flexibles. 


11. ¿Qué son los headers en un request? ¿Para qué se utiliza el key Content-type en un Header? 

Los headers son campos en una solicitud HTTP que proporcionan información adicional.  

El Content-type se utiliza para indicar el tipo de contenido que se está enviando. 
