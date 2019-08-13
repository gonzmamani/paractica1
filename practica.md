
#PRÁCTICA N° 1
-------

#SISTEMAS EMPRESARIALES
##1) Explique que son los sistemas empresariales
**SISTEMAS EMPRESARIALES** Un sistema empresarial es un sistema central de la organización, que garantiza que la información se pueda transmitir atraves de todas las funciones empresariales, y todos los niveles de gestión, para soportar la operación y administración de una empresa. PANORAMA DE LOS SISTEMAS EMPRESARIALES: SISTEMA DE PROCESO DE TRANSACCIONES Y PLANEACIONDE RECURSOS EMPRESARIALES. Todas las organizaciones de procesamiento de transacción de datos (TPC), que capturan y procesan información con el detalle necesario para actualizar registros acerca de sus operaciones empresariales, la entrada de estos sistemas son las transacciones empresariales como: pedidos, órdenes de compras, recibos y facturas entre otros.
ACTIVIDADES DE PROCESAMIENTO DE TRANSACCIONES Los TPS realizan un conjunto común de actividades de procesamiento básico de datos, el ciclo del procesamiento de transacciones, es el proceso de recolección, edición y manipulación de datos empresariales, las principales actividades TPS son: 1.-Recoleccion de datos; captura y recopilación de datos para completar el proceso de transacciones ya sea de manera manual o automatizada 2.-Edicion de datos; en esta etapa se verifica la validez y la integridad delos datos para detectar algún problema. 3.-Manipulacion de datos; proceso que realiza cálculos y otras transformaciones de datos relacionados con transacciones empresariales. 4.-Almacenamiento de datos; involucra la actualización de una o mas bases de datos con nuevas transacciones. 5.-Produccion de datos; involucra la generación de registros, documentos y reportes de salida que pueden ser impresos o aparecer en pantallas de computadoras
##2) Describa cuales son las características más importantes de una aplicación empresarial
**Características**

A la hora de escoger un software tecnológico determinado lo recomendable es acudir a profesionales que te asesoren para conseguir una solución que tenga lo siguiente:

-  	Que sea **flexible y escalable** para que crezca según las necesidades de la empresa. Es decir, se trata de que el software sea capaz de adaptarse a las funciones y necesidades que vayan surgiendo en la organización.

-  	Que sea **ágil y multidispositivo**. Los usuarios deben poder acceder a los datos desde cualquier lugar de forma segura y fiable.

-  	Que sea **sencillo**. Para no perder tiempo con programas informáticos complicados. Lo ideal es que las herramientas sean muy intuitivas y fáciles de usar. Es importante también contar con un buen soporte por si surge cualquier tipo de problema
   
-	Que sea **medible**. Cada acción y los resultados obtenidos deben quedar registrados para proceder con su análisis. Este punto es de vital importancia para el buen desarrollo de un negocio, sobre todo cuando se trata de emprendedores.
##3) Investigue y proponga cinco (5) instituciones que requerirían aplicaciones de misión crítica. Justifique su respuesta
##4) Explique cuáles son las diferencias entre la escalabilidad horizontal y escalabilidad vertical
**Escalabilidad Horizontal y Vertical**

En la práctica existen muchas formas de hacer que un software sea escalable ya que podemos combinar técnicas de software y hardware e incluso arquitecturas de RED (por qué no), pero en esta ocasión me quiere centrar en la escalabilidad horizontal y vertical, porque sin duda es una de las características más importantes para sistemas de alta demanda o uso crítico.
Bien, como ya dijimos existen dos tipos de escalamiento, Horizontal y Vertical, ¿pero que quiere decir cada uno?

**Escalabilidad vertical**

La escalabilidad vertical o hacia arriba, este es el más simple, pues significa crecer el hardware de uno de los nodos, es decir aumentar el hardware por uno más potente, como disco duro, memoria, procesador, etc. pero también puede ser la migración completa del hardware por uno más potente. **El esfuerzo de este crecimiento es mínimo**, pues no tiene repercusiones en el software, ya que solo será respaldar y migrar los sistemas al nuevo hardware.
 
 
 
¿Bastante fácil no?, la realidad es que este tipo de escalamiento tiene algunos aspectos negativos, ya que nuestro **crecimiento está ligado al hardware**, y este; tarde o temprano tendrá un límite, llegara el momento que tengamos el mejor procesador, el mejor disco duro, la mejor memoria y no podamos crecer más o podríamos a lo mejor comprar el siguiente modelo de servidores que nos costara un ojo de la cara y el rendimiento solo mejorar un poco, lo que nos traerá el mismo problema el próximo año.
Ahora bien, no significa que este modelo de escalamiento sea malo, ya que lo podemos combinar con el escalamiento horizontal para obtener mejores resultados.
 
**Ventajas:**

-	No implica un gran problema para las aplicaciones, pues todo el cambio es sobre el hardware

-	Es mucho más fácil de implementar que el escalamiento horizontal.

-	Puede ser una solución rápida y económica (compara con modificar el software)
 
**Desventajas:**

-	El crecimiento está limitado por el hardware.

-	Una falla en el servidor implica que la aplicación se detenga.

-	No soporta la Alta disponibilidad.

-	Hacer un upgrade del hardware al máximo pues llegar a ser muy caro, ya que las partes más nuevas suelen ser caras con respecto al rendimiento de un modelo anterior.
 
**Escalabilidad horizontal**
 
El escalamiento horizontal es sin duda el más potente, pero también el más complicado. Este **modelo implica tener varios servidores (conocidos como Nodos)** trabajando como un todo. Se crea una red de servidores conocida como **Cluster**, con la finalidad de repartirse el trabajo entre todos nodos del cluster, cuando el performance del cluster se ve afectada con el incremento de usuarios, se añaden nuevos nodos al cluster, de esta forma a medida que es requeridos, más y más nodos son agregados al cluster.
 
 
 
Para que el escalamiento horizontal funcione deberá existir un servidor primario desde el cual se administra el cluster. Cada servidor del cluster deberá tener un software que permite integrase al cluster, por ejemplo, para las aplicaciones Java, tenemos los servidores de aplicaciones como Weblogic, Widfly, Websphere, etc. y sobre estos se montan las aplicaciones que queremos escalar.
 
**Ventajas:**

-	El crecimiento es prácticamente infinito, podríamos agregar cuantos servidores sean necesarios
-	Es posible combinarse con el escalamiento vertical.
-	Soporta la alta disponibilidad
-	Si un nodo falla, los demás sigue trabajando.
-	Soporta el balanceo de cargas.
 
**Desventajas:**

-	Requiere de mucho mantenimiento
-	Es difícil de configurar
-	Requiere de grandes cambios en las aplicaciones (si no fueron diseñadas para trabajar en cluster)
-	Requiere de una infraestructura más grande.

##5) Que es un servidor Web y que es un servidor de aplicaciones
**¿Qué es un servidor web?**

Quienes tengan conocimientos sobre lo que es un servidor no deben confundirlo con un servidor web, porque son dos cosas distintas, aunque sí es cierto que uno forma parte del otro, ya que de hecho el servidor web es uno de los componentes de un servidor. El server (o servidor) es el equipo en el cual se alojan los sitios o aplicaciones web, mientras que el servidor web es un software que forma parte del servidor.

El **servidor web** (también llamado webserver en inglés) es el software que se encarga de despachar el contenido de un sitio web al usuario.
Este proceso de despacho, que a simple vista parece muy simple, es en realidad más complejo de lo que parece, pues toda la «magia» de un webserver ocurre fuera de quien está navegando por un sitio web. Existen multitud de servidores web, y entre los más conocidos podemos encontrar por ejemplo a Apache, Nginx, LiteSpeed o IIS.
Los servidores web varían mucho de uno a otro, por ejemplo si comparamos Apache y Nginxveremos que tienen diferencias muy notorias, aunque el objetivo final es el mismo: despachar contenido al usuario.
El proceso de despacho comienza en nuestro navegador web. Al escribir la dirección de un sitio web y presionar enter comienza la siguiente secuencia: el sistema hace una búsqueda DNS para encontrar en cuál servidor está alojado el sitio en cuestión.
Cuando el server es encontrado, el navegador le pide el contenido del sitio web, y acto seguido el webserver procesa este pedido y envía dicho contenido al navegador, lo cual da como resultado la visualización del sitio en nuestra pantalla.

**Servidor de aplicaciones**

Un servidor de aplicaciones es un programa de servidor en un equipo en una red distribuida que proporciona la lógica de negocio para un programa de aplicación. El servidor de aplicaciones se ve frecuentemente como parte de una aplicación de tres niveles, que consta de un servidor gráfico de interfaz de usuario (GUI), un servidor de aplicaciones (lógica empresarial) y un servidor de bases de datos y transacciones. De manera más descriptiva, se puede visualizar como la división de una aplicación en:

1. Una interfaz gráfica de usuario de primer nivel, de front-end, basada en el navegador web, normalmente en un equipo de cómputo personal o una estación de trabajo.
2. Una aplicación de lógica de negocio de nivel medio o conjunto de aplicaciones, posiblemente en una red de área local o un servidor de intranet.
3. Un servidor de back-end, base de datos y transacciones de tercer nivel, a veces en un mainframe o servidor grande.
Las bases de datos de aplicaciones más antiguas y las aplicaciones de administración de transacciones forman parte del backend o tercer nivel. El servidor de aplicaciones es el intermediario entre bases de datos basadas en navegador y bases de datos de back-end y sistemas heredados.

##6) Con un gráfico explique cómo funciona el protocolo HTTP
  ![PROTOCOLO HTTP](https://www.google.com/search?q=Con+un+gráfico+explique+cómo+funciona+el+protocolo+HTTP&source=lnms&tbm=isch&sa=X&ved=0ahUKEwjcnbX--IDkAhWDjlkKHTULAq0Q_AUIESgB&biw=591&bih=531#imgrc=uY4Y7bu_QOJbPM:)

##7) Explique los elementos importantes de REQUEST en HTTP
 **HTTP Request**

 
		
	HTTP Request ( metodoHTTP ; url ; contenido ; respuesta {; nomEncab ; valoresEncab}{; *} ) -> Resultado 	
		
	Parámetro		Tipo		 		Descripción	
	metodoHTTP 		Texto		 		Método HTTP para la petición	
	url 		Texto		 		URL a la cual enviar la petición	
	contenido 		Texto, BLOB, Imagen, Objeto		 		Contenido del cuerpo(body)de la petición	
	respuesta 		Texto, BLOB, Imagen, Objeto		 		Resultado de la petición	
	nomEncab 		Array texto		 		Nombres de los encabezados de la petición	
					 		Nombres de los encabezados devueltos	
	valoresEncab 		Array texto		 		Valores de los encabezados de la petición	
					 		Valores de los encabezados devueltos	
	* 		Operador		 		Si se pasa, la conexión se mantiene (keep-alive)
Si se omite, la conexión se cierra automáticamente	
	Resultado 		Entero largo		 		Código de estado HTTP	
		
**Descripción**
  
El comando HTTP Request permite enviar todo tipo de petición HTTP a un URL específico y procesar la respuesta del servidor HTTP.
Pase en el parámetro metodoHTTP el método HTTP de la petición. Puede utilizar una de las siguientes constantes, del tema HTTP Client:
Constante	Tipo	Valor	Comentario
HTTP DELETE method	Cadena	DELETE	Ver el RFC 2616
HTTP GET method	Cadena	GET	Ver el RFC 2616. Equivale a utilizar el comando HTTP Get
HTTP HEAD method	Cadena	HEAD	Ver el RFC 2616
HTTP OPTIONS method	Cadena	OPTIONS	Ver el RFC 2616
HTTP POST method	Cadena	POST	Ver el RFC 2616
HTTP PUT method	Cadena	PUT	Ver el RFC 2616
HTTP TRACE method	Cadena	TRACE	Ver el RFC 2616

##8) Explique los elementos importantes de RESPONSE en HTTP
 <https://developer.mozilla.org/es/docs/Web/HTTP/Messages>
##9) Describa con un gráfico la arquitectura Java EE 
![ARQUITECTURA DE JAVA EE](https://www.google.com/search?q=ARQUITECTURA+DE+JAVA+ee&source=lnms&tbm=isch&sa=X&ved=0ahUKEwiXwpmv-oDkAhUHo1kKHSfSA-8Q_AUIESgB&biw=591&bih=531#imgrc=Next7lc1tvK4xM:)
##10) Explique cuáles son los contenedores, componentes y servicios de Java EE
**CONTENEDORES JAVA EE**

Escribir aplicaciones empresariales seria muy complejo y difícil de codificar, ya que implicaría muchas lineas de código complejo para el manejo de transacciones y la gestión de estados, multihilos y otros detalles de bajo nivel,  la arquitectura Java EE hace que las aplicaciones sean fáciles de escribir porque la lógica de negocio se divide en componentes reutilizables y adicionalmente se cuenta con un servidor de aplicaciones que proporciona servicios en la forma de contenedor para los diferentes tipos de componentes, debido a esto no se tiene que desarrollar estos servicios, sino enfocarse en el desarrollo.

1. 	**SERVICIOS DEL CONTENEDOR**  Los contenedores son la interface entre un componente y el bajo nivel, es especifico para la plataforma, antes de que se pueda ejecutar el componente web, el bean o la aplicación cliente deben ser cargados en un modulo java EE y desplegarlo en el contenedor. al momento de desplegarlo cada componente puede tener su propia configuración en cuanto a seguridad, gestión de transacciones JNDI etc.
2.	**TIPOS DE CONTENEDORES**
En la siguiente figura se muestra los tipos de contenedores para los diferentes componentes:

 

***El servidor y los contenedores son:***

**Java EE Server:** La porción de tiempo de ejecución de un producto Java EE. provee los contenedores web y de ejb.

**Contenedor EJB:** Maneja la ejecución de los enterprise beans.

**Contenedor Web:** Maneja la ejecución de las paginas web, servlets y algunos componentes ejb para las aplicaciones Java EE.

**Contenedor de aplicación cliente:** Maneja la ejecución de la aplicación cliente no necesita un servidor de aplicaciones.

**Contenedor Applet:** Maneja la ejecución de applets, no necesita servidor de aplicaciones, consiste en un browser y el plugin web de java.

 
##11) Investigue los métodos más utilizados de las clases HttpServlet, HttpServletRequest y HttpServletResponse, y para cada uno de los métodos muestre un ejemplo.
**HttpServlet**

A la hora de enviar información a un Servlet tenemos dos formas: mediante el método GET y mediante el método POST. Existen una serie de diferencias entre pasarlos de una forma u otra:

**Metodo POST.** Este método solo esta accesible desde los formularios. Se envían los parámetros de forma implícita junto a la página, es decir, al pasar los parámetros, nosotros no vemos reflejado en ningún sitio qué parámetros son y cual es su valor.

**Método GET.** Este método envía los parámetros de forma explicita junto a la página, mostrando en la barra de navegación los parámetros y sus valores. Son esas largas cadenas que aparecen en algunas páginas en nuestra barra de navegación, del estilo: buscar?id=1806&valor=0987&texto=todo&...
Las cadenas toman el aspecto parametro1=valor1&parametro2=valor2&....&parametroN=valorN. Es decir es una concatenación a través de & de pares parámetro-valor.
Los métodos de la clase HttpServlet que manejan peticiones de cliente toman dos argumentos.

Un objeto **HttpServletRequest**, que encapsula los datos desde el cliente.

Un **objeto HttpServletResponse**, que encapsula la respuesta hacia el cliente.

- **Objetos HttpServletRequest**

Un objeto **HttpServletRequest** proporciona acceso a los datos de cabecera HTTP, como cualquier cookie encontrada en la petición, y el método HTTP con el que se ha realizado la petición. El objeto HttpServletRequest también permite obtener los argumentos que el cliente envía como parte de la petición.
Para acceder a los datos del cliente

El método **getParameter** devuelve el valor de un parámetro nombrado. Si nuestro parámetro pudiera tener más de un valor, deberíamos utilizar getParameterValues en su lugar. El método getParameterValues devuelve un array de valores del parámetro nombrado. (El método getParameterNames proporciona los nombres de los parámetros.
Para peticiones GET de HTTP, el método getQueryString devuelve en un String una línea de datos desde el cliente. Debemos analizar estos datos nosotros mismos para obtener los parámetros y los valores.
Para peticones POST, PUT, y DELETE de HTTP.
Si esperamos los datos en formato texto, el método getReader devuelve un BufferedReader utilizado para leer la línea de datos.
Si esperamos datos binarios, el método getInputStream devuelve un ServletInputStream utilizado para leer la línea de datos.
Nota:
Se debe utilizar el método getParameter[Values] o uno de los métodos que permitan analizar los datos. No pueden utilizarse juntos en una única petición.

- **Objetos HttpServletResponse**
Un objeto HttpServletResponse proporciona dos formas de devolver datos al usuario.

El método **getWriter** devuelve un Writer
El método **getOutputStream** devuelve un ServletOutputStream
Se utiliza el método getWriter para devolver datos en formato texto al usuario y el método getOutputStream para devolver datos binarios.

Si cerramos el Writer o el ServletOutputStream después de haber enviado la respuesta, permitimos al servidor saber cuando la respuesta se ha completado.
####EJEMPLO
 **Manejar Peticiones GET**

Manejar peticiones GET implica sobreescribir el método doGet. El siguiente ejemplo muestra a BookDetailServlet haciendo esto. Los métodos explicados en Peticiones y Respuestas se muestran en negrita.
public class BookDetailServlet extends HttpServlet {

    public void doGet (HttpServletRequest request,
                       HttpServletResponse response)
        throws ServletException, IOException
    {
        ...
	// selecciona el tipo de contenido en la cabecera antes de acceder a Writer
        response.setContentType("text/html");
        PrintWriter out = response.getWriter();

	// Luego escribe la respuesta
        out.println("<html>" +
                    "<head><title>Book Description</title></head>" +
                    ...);

        //Obtiene el identificador del libro a mostrar
        String bookId = request.getParameter("bookId");
        if (bookId != null) {
            // Y la información sobre el libro y la imprime
            ...
        }
        out.println("</body></html>");
        out.close();
    }
    ...
}
El servlet extiende la clase HttpServlet y sobreescribe el método doGet. Dentro del método doGet, el método getParameter obtiene los argumentos esperados por el servlet.

Para responder al cliente, el método doGet utiliza un Writer del objeto HttpServletResponse para devolver datos en formato texto al cliente. Antes de acceder al writer, el ejemplo selecciona la cabecera del tipo del contenido. Al final del método doGet, después de haber enviado la respuesta, el Writer se cierra.

  **Manejar Peticiones POST**

Manejar peticiones POST implica sobreescribir el método doPost. El siguiente ejemplo muestra a ReceiptServlet haciendo esto. De nuevo, los métodos explicados en Peticiones y Respuestas se muestran en negrita.
public class ReceiptServlet extends HttpServlet { 

    public void doPost(HttpServletRequest request,
                       HttpServletResponse response)
	throws ServletException, IOException
    {
        ...
        // selecciona la cabecera de tipo de contenido antes de acceder a Writer
        response.setContentType("text/html");
        PrintWriter out = response.getWriter();
        
        // Luego escribe la respuesta
        out.println("<html>" +
                    "<head><title> Receipt </title>" +
                    ...);
        
        out.println("<h3>Thank you for purchasing your books from us " +
                    request.getParameter("cardname") +
                    ...);
        out.close();
    }
    ...
}
El servlet extiende la clase HttpServlet y sobreescribe el método doPost. Dentro del método doPost, el método getParameterobtiene los argumentos esperados por el servlet.
Para responder al cliente, el método doPost utiliza un Writer del objeto HttpServletResponse para devolver datos en formato texto al cliente. Antes de acceder al writer, el ejemplo selecciona la cabecera del tipo de contenido. Al final del método doPost, después de haber enviado la respuesta, el Writer se cierra.
