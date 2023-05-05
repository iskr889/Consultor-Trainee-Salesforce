## EJERCICIO 2

**Guía de preguntas que están orientadas a la comprensión del protocolo HTTP**

**1. ¿Qué es un servidor HTTP?**

Es un software que se ejecuta en un servidor de computadora y que ofrece servicios de alojamiento de sitios y aplicaciones web a través del protocolo HTTP. Éste recibe solicitudes de los clientes y responde a las mismas enviando los recursos solicitados, como páginas web por ejemplo. 

[![servertiming.webp](https://i.postimg.cc/HkpnXr1b/servertiming.webp)](https://postimg.cc/dLxJKt10)

**2. ¿Qué son los verbos HTTP? Mencionar los más conocidos**

Son un conjunto de comandos que se utilizan en el protocolo HTTP para indicar la acción que se desea realizar en un recurso determinado. Cada solicitud se realiza utilizando uno de estos verbos, que se envía al servidor para que éste sepa qué acción realizar. Los verbos HTTP más conocidos son: GET, POST, PUT, DELETE y HEAD 


**3. ¿Qué es un request y un response en una comunicación HTTP? ¿Qué son los headers?**

La comunicación entre un cliente y un servidor se realiza a través de una request (solicitud) y un response (respuesta). La solicitud es enviada por el cliente al servidor para solicitar un recurso o realizar una acción, mientras que la respuesta es enviada por el servidor al cliente para proporcionar el recurso o información solicitada.  

Por otro lado, los headers (encabezados) son campos que brindan información adicional en las solicitudes o respuestas. Los de solicitud indican autenticación, tipo de contenido, codificación de caracteres, etc. Los de respuesta indican el tipo de contenido, fecha/hora de la respuesta, servidor, etc.  


**4. ¿Qué es un queryString? (En el contexto de una url)**

El queryString es la parte de la URL que sigue al signo de interrogación "?" y que contiene uno o más parámetros de búsqueda para solicitar información específica de un servidor web. 


**5. ¿Qué es el response Code? ¿Qué significado tiene los posibles valores devueltos?**

Es un número de tres dígitos que indica el estado de la respuesta del servidor a una solicitud HTTP. Los códigos se dividen en cinco clases principales que representan diferentes rangos de números, ya que son una forma estandarizada de comunicar el resultado de una solicitud HTTP al cliente. 

[![1-w-iicb-G7-L3x-EQTArj-HUS6g.jpg](https://i.postimg.cc/6QJHMxzV/1-w-iicb-G7-L3x-EQTArj-HUS6g.jpg)](https://postimg.cc/cvhMJjp6)

**6. ¿Cómo se envía la data en un Get y cómo en un POST?**

En una solicitud GET, la información se envía al servidor a través de la URL, mientras que en una solicitud POST, la información se envía en el cuerpo de la solicitud HTTP.  


**7. ¿Qué verbo http utiliza el navegador cuando accedemos a una página?**
 
Cuando accedemos a una página web, el navegador utiliza el verbo HTTP GET para solicitar la página y recibir la respuesta del servidor. 


**8. Explicar brevemente qué son las estructuras de datos JSON y XML dando ejemplo de estructuras posibles.**

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


## EJERCICIO 3

La diferencia entre los requests GET en el punto 1 y 3 radica en que en el punto 1 se obtienen todos los contactos almacenados en la base de datos en formato JSON, mientras que en el punto 3 se obtienen todos los contactos incluyendo el contacto creado en el request POST. 

[![free-Code-Camp-Cover-1.png](https://i.postimg.cc/WbYQj4ws/free-Code-Camp-Cover-1.png)](https://postimg.cc/dLdWjwff)

## EJERCICIO 5

Explicar que son conceptualmente, qué datos almacenan en forma estándar y cómo se relacionan el resto
(algunos no se relacionan entre sí) cada uno de los siguientes objetos de Salesforce:

Lead: prospectos comerciales.
Account: cuenta de cliente.
Contact: persona relacionada a una cuenta.
Opportunity: oportunidad de venta.
Product: producto de una oportunidad.
PriceBook: catálogo de precios.
Quote: cotización.
Asset: bien vendido o entregado.
Case: registro de servicio o soporte.
Article: documento de conocimiento o información.

## EJERCICIO 6

**Soluciones de Salesforce**
A. Salesforce es una plataforma en línea para la gestión de relaciones con clientes (CRM).
B. Sales Cloud es una aplicación de Salesforce para la gestión de ventas y oportunidades.
C. Service Cloud es una aplicación de Salesforce para la gestión de servicio al cliente.
D. Health Cloud es una aplicación de Salesforce para la gestión de atención médica y pacientes.
E. Marketing Cloud es una aplicación de Salesforce para la gestión de marketing y publicidad.

**Funcionalidades de Salesforce**
A. RecordType es una forma de categorizar y personalizar objetos de Salesforce.
B. ReportType es una plantilla que se utiliza para crear informes en Salesforce.
C. Page Layout es la forma en que los campos y secciones se organizan en una página de registro en Salesforce.
D. Compact Layout es una forma de ver un resumen de los campos en un registro en Salesforce.
E. Perfil es un conjunto de permisos y configuraciones que determinan lo que un usuario puede ver y hacer en Salesforce.
F. Rol es una forma de asignar niveles de acceso a los datos de Salesforce para los usuarios.
G. Validation Rule es una regla que se utiliza para validar los datos ingresados por el usuario antes de que se guarden en Salesforce.
H. Master Detail y Lookup son dos tipos de relaciones entre objetos de Salesforce, en las que Master Detail es más estricta y afecta a la funcionalidad de la eliminación.
I. Sandbox es un ambiente de pruebas aislado del ambiente de producción en Salesforce.
J. ChangeSet es una forma de mover configuraciones y código personalizado de un ambiente Salesforce a otro.
K. Import Wizard de Salesforce es una herramienta para importar datos en masa a Salesforce desde una variedad de fuentes.
L. La funcionalidad Web-to-Lead de Salesforce permite a las empresas generar formularios web que se pueden utilizar para capturar información de clientes potenciales directamente en Salesforce.
M. La funcionalidad Web-to-Case de Salesforce permite a las empresas generar formularios web que se pueden utilizar para capturar información de casos directamente en Salesforce.
N. La funcionalidad Omnichannel de Salesforce es una herramienta de enrutamiento de casos y chats para garantizar que los casos y chats se dirijan a los agentes correctos en tiempo real.
O. Chatter es una plataforma de colaboración empresarial de Salesforce que permite a los usuarios compartir información y colaborar en tiempo real.

**Conceptos generales**
A. SaaS significa Software as a Service, es un modelo de entrega de software en el que el proveedor de servicios aloja la aplicación y la hace accesible a través de Internet.
B. Sí, Salesforce es una plataforma de CRM en la nube que se ofrece como servicio.
C. Cloud significa que la solución está alojada en la nube, en servidores remotos, y es accesible a través de Internet.
D. On-Premise significa que la solución está alojada en los servidores de la empresa que la adquiere, y se ejecuta localmente en sus sistemas informáticos.
E. Un pipeline de ventas es el conjunto de oportunidades de venta que un representante de ventas está trabajando actualmente.
F. Un funnel de ventas es el proceso de convertir clientes potenciales en clientes, dividiéndose en distintas fases.
G. Customer Experience se refiere a la experiencia completa de un cliente al interactuar con una empresa, incluyendo los puntos de contacto y las emociones que experimenta.
H. Omnicanalidad significa que la empresa está presente en distintos canales y que los clientes pueden interactuar con ella a través de múltiples canales.
I. B2B significa business-to-business, es decir, una empresa que vende productos o servicios a otras empresas. B2C significa business-to-consumer, es decir, una empresa que vende productos o servicios directamente a los consumidores finales. Un KPI (Key Performance Indicator) es una métrica utilizada para medir el rendimiento y el éxito de una empresa en relación con sus objetivos.
J. Una API (Application Programming Interface) es un conjunto de reglas y protocolos que permiten a las aplicaciones interactuar entre sí. Una Rest API es una API que utiliza el protocolo HTTP para intercambiar datos.
K. Un Proceso Batch es un proceso informático que se ejecuta en segundo plano y procesa grandes cantidades de datos en lotes.
L. Kanban es un sistema de gestión visual que ayuda a los equipos a controlar su trabajo y a visualizar el flujo de trabajo.
M. Un ERP (Enterprise Resource Planning) es un software que se utiliza para gestionar los procesos empresariales, como la contabilidad, la gestión de inventarios y la producción.
N. Salesforce no es un ERP, aunque cuenta con funcionalidades que se integran con sistemas ERP.

[![salesforce-eco-system.jpg](https://i.postimg.cc/SRMzsRYH/salesforce-eco-system.jpg)](https://postimg.cc/7JqLtxVN)
