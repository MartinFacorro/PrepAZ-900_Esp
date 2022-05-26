# Presentación

- 👋 Hola, Soy @MartinFacorro
- 👀 Me interesa muchísimas cosas, dentro de la tecnología, soy un programador apasionado. Me gusta mucho trabajar en equipo, observar cómo se trabaja y entender el valor del capital humano. En otros ordenes de la vida, me gusta mucho la lectura, no puedo vivir sin estar con un libro en la mano. Su tuviese que recomendar un libro, ese seria "El Mundo de Sofia" una novela de Jostein Gaarder.
- 🌱 Actualmente estoy aprendiendo sobre la nube por supuesto, y continuamente aprendiendo sobre temás de desarrollo.
- 💞️ Estoy buscando colaborar en la comunidad de Desarrolladores.
- 📫 Cómo llegar a mí, podras encontrarme en:
  - Twitter <a href="https://twitter.com/FacorroMartin"> @FacorroMartin </a> 
  - LinkedIn <a href="https://www.linkedin.com/in/martin-facorro/"> Martin Facorro </a>
  - Facebook <a href="https://www.facebook.com/profile.php?id=100080665428602"> Martin Facorro </a>
  - Instagram <a href="https://www.instagram.com/facorro.martin/"> Martin Facorro </a>
  - Github <a href="https://github.com/MartinFacorro"> Martin Facorro </a>


# Preparación Azure AZ-900 español

En este camino del aprendizaje, mientras lo recorro, quiero compartir aquellos recursos que me sirven al momento de prepararme.

El objetivo es dar un aporte para vuestros caminos.

Como primer ítem a compartir. Como cada documentación que uno requiera recorrer, el mejor lugar donde encontrar información es en el site oficial.
Por lo que para iniciar el primer lugar para visitar es el siguiente: <a href="https://docs.microsoft.com/es-mx/learn/azure/"> Azure en Microsoft Learn | Microsoft Docs</a>

A saber, el examen de AZ-900 consta de los siguientes temás.
Este examen incluye seis áreas de dominios de conocimiento:

|                                **Área de domínio AZ-900**                | **Peso**              |
|--------------------------------------------------------------------------|-----------------------|
|                  Descripción de los conceptos de la nube                 | 20-25 %               |
|              Descripción de los servicios básicos de Azure               | 15-20 %               |
|Descripción de las principales soluciones y herramientas de administración de Azure | 10-15 %     |
| Descripción de las características de seguridad general y de seguridad de red | 10-15 %          |
|Descripción de las características de identidad, gobernanza, privacidad y cumplimiento | 20-25 %  |
|Descripción de los Acuerdos de Nivel de Servicio y la administración de costos de Azure | 10-15 % |



<hr />

# <img src="img\intro-to-azure-fundamentals.svg" alt="" style="height: 40px; width:50px;"/> Módulo 1 Conceptos de la nube

**cómputo en la nube**: prestación de servicios de cómputo a través de internet, permite el acceso bajo demanda a un grupo de recursos. Permite innovación más rápida, recursos flexibles y costos regulables.

## Modelos en la nube

### Nube privada

- Centro de datos propio
- La organización es responsable de operar los servicios que brinda.
- No proporciona accesos ajenos a la organización.

### Nube Publica

- Propiedad del Cloud Services o proveedor de hosting
- Proporciona recursos y servicios a múltiples organización y usuarios.
- Se accede a través de una red segura(por lo general internet).

### Nube hibrida

- Combina la nube publica con la privada.
- Permite la ejecución de aplicaciones de manera más adecuada.
- Se adecua, con legislaciones o regulaciones de información sensible, para que se mantenga en ubicaciones on-premise.

## Beneficios de la nube

- **Alta disponibilidad**: Capacidad que tienen las infraestructuras para mantenerse funcionando la mayor cantidad de tiempo posible, sin perjudicar la operación.

- **Tolerancia a fallos**: Capacidad de responder a una falla, sin generar la caída completa de los sistemás.

- **Escalabilidad**: Capacidad de agregar instancias o crecer verticalmente, por ejemplo, en la cantidad de máquinas virtuales para operar un sistema. (se realiza de forma manual o automática)

- **Elasticidad**: Capacidad de crecer horizontalmente, en este caso se incrementan los recursos de cómputo a un servicio o sistema. (se realiza de forma manual o automática)

- **Alcance global**: Esta relacionado con las capacidades de latencia por el lado del cliente. Relacionado a regiones, países. 

- **Capacidades de latencia del cliente**: Permite levantar servicios en la ubicación geográfica más cercada, en donde los usuarios los están consumiendo.

- **Agilidad**: Capacidad de generar o eliminar un recurso, un sistema de manera rápida y eficiente en el momento que lo creamos conveniente.

- **Consideraciones de costos predictivo**: Calculadora de costos, costos de capital.

## Costos de capital (Capex) (modelo on-premise)

- Gasto inicial de dinero en infraestructura física.
- Costos derivados de CapEx tienen un valor que se reduce con el tiempo.

## Gastos Operativos (OpEx)

- El gasto y la facturación en servicios o productos según sea necesario.
- Los gastos se deducen el mismo año.

## Modelo basado en el consumo

Los usuarios finales solo pagan por los recursos que utilizan.

- Mejor predicción de costos.
- Se proporcionan precios para recursos y servicios individuales.
- La facturación se basa en uso real.

## Servicios en la nube

### **Infraestructura como Servicio: (IaaS)**

<img src="img\IaaS.png" alt="" style="height: 240px; width:550px;"/>


Estructura más básica, el proveedor se ocupa de la planta física, de la seguridad, seguridad de red, proveen los servidores y almacenamiento.

### **Plataforma como servicio  (PaaS):**

<img src="img\PaaS.png" alt="" style="height: 240px; width:550px;"/>

Proporciona un entorno para desarrollar, probar e implementar aplicaciones, sin centrarse en la administración de la infraestructura subyacente.

Se utiliza para poder desarrollar, implementar software, si preocupaciones sobre la infraestructura.

### **Software como Servicio (Saas):**

<img src="img\SaaS.png" alt="" style="height: 240px; width:550px;"/>

Los usuarios usan aplicaciones basadas en la nube y se conectan a ellas a través de Internet. Algunos ejemplos: Microsoft 365, correo electrónico, calendario. Aplicaciones 100% en la nube.

### Modelo de Responsabilidad compartida.

La responsabilidad de acceso y de datos siempre es responsabilidad del cliente.

<img src="img\shared-responsibility.svg" alt="" style="height: 340px; width:550px;"/>

### Comparación de servicios en la nube

<img src="img/IaaS+PaaS+SaaS.png" alt="" style="height: 210px; width:550px;"/>

### Modelo de Responsabilidad compartida

<img src="img/ModeloDeResponsabilidadCompartida.png" alt="" style="height: 260px; width:550px;"/>


### ServerLess o cómputo sin servidor

Con el modelo de cómputo sin servidor, el proveedor de servicios en la nube otorga, escala y administra de manera automática, la infraestructura para ejecutar el código.


**Azure Functions: (Se necesita un desarrollador)** 

<img src="img/AzureFunctionsIcon.png" style="height:48px; widht:48px;" /> 

Funciones que se ejecutan como servicios. Ejecución en tiempo real, donde se crea el recurso, se utiliza y se desecha. La VENTAJA es el costo, ya que se paga por lo que se consume.  Las funciones se usan normalmente cuando se debe realizar un trabajo en respuesta a un evento (a menudo a través de una solicitud REST), un temporizador o un mensaje de otro servicio de Azure, y cuando ese trabajo puede completarse rápidamente, en segundos o en menos tiempo.

Ventajas:

- En lugar de escribir una aplicación completa, el desarrollador crea una función, la cual contiene código y metadatos sobre sus desencadenadores y enlaces. La plataforma programa automáticamente la función para que se ejecute y escala el número de instancias de proceso según la tasa de eventos de entrada.
- Permite código más productivo.
- Leguajes de desarrollo como C#, F#, Node.js, Java o PHP.
- Pagar solo por el tiempo en que Azure Functions esta en ejecución.

**Azure Logic Apps: (No requiere desarrollador)** 

<img src="img/Azure-Logic-Apps-logo.png" style="height:48px; widht:48px;" />

Las aplicaciones lógicas ejecutan flujos de trabajo diseñados para automatizar escenarios empresariales y compilados a partir de bloques lógicos predefinidos. Todos los flujos de trabajo de aplicación lógica de Azure comienzan con un desencadenador, que se activa cuando se produce un evento específico o cuando hay nuevos datos disponibles que cumplen determinados criterios. Con el lanzamiento de un desencadenador, el motor de Logic Apps crea una instancia de aplicación lógica que ejecuta las acciones del flujo de trabajo.

Estas acciones también pueden incluir conversiones de datos y controles de flujo, como instrucciones condicionales, instrucciones "switch", bucles y bifurcaciones.

Los flujos de trabajo se conservan como un archivo JSON con un esquema de flujo de trabajo conocido.

Azure Logic Apps es un servicio sin código o de poco código, no se necesitan desarrolladores. Un profesional de la nube o de TI debe pueden compilar y dar soporte a este flujo de trabajo.

**Comparación entre Functions y Logic Apps**

Functions y Logic Apps pueden crear orquestaciones complejas. Una orquestación es una colección de funciones o pasos que se ejecutan para realizar una tarea compleja.

- Con Functions, se escribe código para completar cada paso.
- Con Logic Apps, se usa una GUI para definir las acciones y cómo se relacionan entre sí.

Puede mezclar y combinar servicios cuando crea una orquestación, llamando a las funciones desde las aplicaciones lógicas y viceversa. Aquí se indican algunas diferencias comunes entre las dos.

# Módulo 2 Conceptos de la nube

## Componentes de Arquitectura

### Regiones

Es un conjunto de centros de datos, cada región tiene mas de un data center. Esto permite flexibilidad para los usuarios, ya que reduce la latencia para los clientes. Pudiendo elegir las zonas de mayor proximidad. Las regiones y zonas de disponibilidad de Azure están diseñadas para ayudarle a lograr resistencia y confiabilidad en las cargas de trabajo críticas para la empresa.

Zonas de disponibilidad
Las zonas de disponibilidad de Azure son ubicaciones separadas físicamente dentro de cada región de Azure y toleran los errores locales. Estos errores pueden abarcar desde errores de software y hardware hasta eventos como terremotos, inundaciones e incendios. La tolerancia a los errores se logra gracias a la redundancia y el aislamiento lógico de los servicios de Azure. Para garantizar la resistencia, se configuran un mínimo de tres zonas de disponibilidad independientes en todas las regiones habilitadas.
Estas zonas de disponibilidad de Azure se conectan mediante una red de alto rendimiento que cuenta con una latencia de ida y vuelta inferior a 2 milisegundos. Asimismo, le ayudan a sincronizar los datos y a mantenerlos accesibles cuando las cosas van mal. Cada zona consta de uno o varios centros de datos equipados con una infraestructura de alimentación, refrigeración y redes independientes. Las zonas de disponibilidad están diseñadas de manera que, si se ve afectada una zona, los servicios regionales, la capacidad y la alta disponibilidad serán compatibles con las dos zonas restantes.

<img src="img/availability-zones.png" style="height:48px; widht:48px;" />
Cada centro de datos se asigna a una zona física. Las zonas físicas se asignan a zonas lógicas de la suscripción de Azure. A las suscripciones de Azure se les asigna automáticamente esta asignación en el momento de crear una suscripción.

**Regiones Pareadas** a través La norma ISO22000 habla de la continuidad de negocios y recuperacion de desastres.
para cada región, existe una región par, a menos de 300 millas de distancia de la región original. Esto existe, para que haya replicación pares. Así ante un eventual caída, se recupere la información de la region par.

<img src="img/ZonasPareadas.png" style="height:48px; widht:48px;" />

### Zonas de disponibilidad

<img src="img/ZonasDisponibles.png" style="height:48px; widht:48px;" />

### Recursos principales

Los recursos de Azure son los componentes como almacenamiento, maquinas virtuales,  y redes que están disponibles para crear soluciones en la nube.

1. Maquinas Virtuales.
2. Cuentas de almacenamiento.
3. Redes Virtuales.
4. App Services.
5. SQL Database.
6. Funciones.

### Azure Resources Manager

<img src="img/ARM.png" style="height:48px; widht:48px;" />

### Suscripciones

<img src="img/susc.png" style="height:48px; widht:48px;" />

Para crear y usar los servicios de Azure, necesita una suscripción de Azure. Cuando trabaje con aplicaciones y necesidades empresariales propias, tendrá que crear una cuenta de Azure y se creará una suscripción de forma automática. Después de crear una cuenta de Azure, puede crear suscripciones adicionales.

### Grupos de Administración

Los **grupos de recursos** son contenedores lógicos, para administrar recursos. Los grupos de recursos permiten no tener que estar eliminando cada recuros.

Cada recurso puede pertenecer solo a un grupo de recursos. Los recursos pueden estar en distintas regiones dentro de un mismo grupo de recursos.
<img src="img/grupoAdmin.png" style="height:48px; widht:48px;" />

Se puede tener hasta 10mil niveles de administración, y 6 niveles.

### cómputo (Azure Compute Services)

Es el servicio mas utilizado. Es un servicio de computo bajo demanda que proporciona recursos de computo como discos, procesadores, memoria, redes y sistemas operativos.

#### Maquinas virtuales

Las maquinas virtuales de Azure, son emulaciones basadas en software de equipos físicos:

- Incluye un procesador virtual, memoria, almacenamiento y redes.
- Oferta de la IaaS que proporciona un control y una personalización total.

Al utilizar un cliente de escritorio remoto, puede usar y controlar la máquina virtual como si se estuviera sentado delante de ella.

#### Servicio de Aplicaciones (Application services)

Azure App Services es una plataforma totalmente administrada para crear, implementar y escalar aplicaciones web, y APIs rápidamente:

- Compatible con .NET, .NET Core, Node.js, Java, Python o PHP.
- Oferta de PaaS con requisitos de cumplimiento, seguridad y rendimiento de nivel empresarial.
- Puede satisfacer los exigentes requisitos de rendimiento, escalabilidad, seguridad y cumplimiento mientras usa una plataforma totalmente administrada para realizar el mantenimiento de la infraestructura. App Service es una oferta de plataforma como servicio (PaaS).

**Tipos de servicios de aplicaciones**

Con App Service, puede hospedar la mayoría de los estilos de servicio de aplicación más comunes, como los siguientes:

- Aplicaciones web: compatibilidad completa para hospedar aplicaciones web mediante ASP.NET, ASP.NET Core, Java, Ruby, Node.js, PHP o Python. Puede elegir Windows o Linux como sistema operativo del host.
- Aplicaciones de API: puede compilar API web basadas en REST mediante el lenguaje y el marco que prefiera. Se obtiene compatibilidad completa con Swagger y la posibilidad de empaquetar y publicar la API en Azure Marketplace. Las aplicaciones producidas se pueden consumir desde cualquier cliente basado en HTTP o HTTPS.
- Trabajos web: Se puede usar la característica WebJobs para ejecutar un programa (.exe, Java, PHP, Python o Node.js) o un script (.cmd, .bat, PowerShell o Bash) en el mismo contexto que una aplicación web, aplicación de API o aplicación móvil. Los puede programar o ejecutar un desencadenador. Los trabajos web suelen usarse para ejecutar tareas en segundo plano como parte de la lógica de aplicación.
- Aplicaciones móviles: Use la característica Mobile Apps de App Service a fin de compilar rápidamente un back-end para aplicaciones iOS y Android. Con unos pocos clics en Azure Portal, puede realizar lo siguiente:

- Almacenar los datos de aplicaciones móviles en una base de datos SQL basada en la nube.
- Autenticar a clientes con proveedores sociales comunes, como MSA, Google, Twitter y Facebook.
- Enviar notificaciones de inserción.
- Ejecutar lógica de back-end personalizada en C# o Node.js.



En el lado de la aplicación móvil, hay compatibilidad con el SDK para aplicaciones nativas de iOS y Android, Xamarin y React.

App Service controla la mayoría de las decisiones sobre la infraestructura que se tratan en el hospedaje de aplicaciones accesibles desde la web:

- La implementación y administración se integran en la plataforma.
- Los puntos de conexión se pueden proteger.
- Los sitios se pueden escalar rápidamente para controlar cargas de tráfico elevado.
- El equilibrio de carga integrado y el administrador de tráfico proporcionan alta disponibilidad.

Todos estos estilos de aplicación se hospedan en la misma infraestructura y comparten estas ventajas. Esto convierte a App Service en la elección ideal para hospedar aplicaciones orientadas a la web.

#### Contenedores (Azure Container Services)

Los contenedores de Azure son un entorno virtualizado ligero que no requiere administracion del sistema operativo y puede responder a los cambios bajo demanda:

- **Azure Container Instances**: una oferta de PaaS que ejecuta un contenedor en Azure son la necesidad de administrar una maquina virtual o servicios adicionales.
- **Azure Kubernetes Services**: un servicio completo con arquitecturas distribuidas y grandes volúmenes de contenedores.

Los contenedores son una excelente opción si quiere ejecutar varias instancias de una aplicación en un solo equipo host.

#### Escritorio Virtual de Windows

Windows Virtual Desktop es la virtualización de aplicaciones y escritorios que se ejecuta en la nube:

- Cree un entorno de virtualizacion de escritorio completo sin tener que ejecutar servidores de puerta de enlace adicionales.
- Publique grupos de hosts ilimitados para adaptarse a diversas cargas de trabajo.
- Reduzca los costos con recursos agrupados para múltiples sesiones.

Azure Virtual Desktop proporciona administración centralizada de la seguridad de los escritorios de los usuarios con Azure Active Directory (Azure AD). Puede habilitar la autenticación multifactor para proteger los inicios de sesión de los usuarios. También puede proteger el acceso a los datos mediante la asignación a los usuarios de controles de acceso basados en roles (RBAC) detallados.

Los datos y las aplicaciones se separan del hardware local y se ejecutan en un servidor remoto. Se reduce el riesgo de dejar los datos confidenciales en un dispositivo personal.

Las sesiones de usuario están aisladas en entornos de una o varias sesiones.

### Redes

Incluye una gama de opciones para conectar el mundo exterior a servicios y características de los centros de datos globales de Azure.

#### Azure Virtual Network (VNet)
Permite que los recursos de Azure se comuniquen entre si, con internet y con redes locales.
Una red de Azure se puede considerar una extensión de la red local con recursos que vincula otros recursos de Azure.

Las redes virtuales de Azure proporcionan las importantes funcionalidades de red siguientes:

- Aislamiento y segmentación: permite crear varias redes virtuales aisladas.
- Comunicación con Internet: Una máquina virtual en Azure se puede conectar a Internet de forma predeterminada.
- Comunicación entre recursos de Azure: los recursos de Azure para que se comuniquen entre sí de forma segura.
- Comunicación con los recursos locales: permiten vincular entre sí los recursos del entorno local y dentro de la suscripción de Azure. Existen tres mecanismos para lograr esa conectividad:

  - Redes virtuales privadas de punto a sitio.
  - Redes virtuales privadas de sitio a sitio.
  - Azure ExpressRoute.

- Enrutamiento del tráfico de red: De forma predeterminada, Azure enruta el tráfico entre las subredes de todas las redes virtuales conectadas, las redes locales e Internet.

- Filtrado del tráfico de red: Azure permiten filtrar el tráfico entre las subredes mediante:

 - Grupos de seguridad de red.
 - Aplicaciones Virtuales de red.

- Conexión de redes virtuales: uede vincular redes virtuales entre sí mediante el emparejamiento de red virtual. El emparejamiento permite que los recursos de cada red virtual se comuniquen entre sí. Estas redes virtuales pueden estar en regiones distintas, lo que permite crear una red global interconectada con Azure.

#### Virtual Private Network Gateway (VPN)

Se usa para enviar tráfico cifrado entre una red virtual de Azure y una ubicacion local a través de la internet pública. Se implementan para conectar entre sí dos o más redes privadas de confianza a través de una red que no es de confianza (normalmente, la red pública de Internet). El tráfico se cifra mientras viaja por la red que no es de confianza para evitar ataques de interceptación o de otro tipo.

#### Azure Express Route

Extiende las redes locales hacia Azure a traves de una conexion privada que facilita un proveedore de conexion.

### Almacenamiento (Azure Storage Services)

Servicio que puede usar para almacenar archivos, mensajes, tablas y otros tipos de información. Los clientes como sitios web, aplicaciones móviles, aplicaciones de escritorio y muchos otros tipos de soluciones personalizadas pueden leer y escribir datos en Azure Storage. Azure Storage también se usa en máquinas virtuales de infraestructura como servicio y en servicios en la nube de plataforma como servicio.

#### Contenedores de almacenamiento (Blob Storage)

Servicio de almacenamiento para objetos muy grandes, como archivos de vídeo o mapas de bits.
Los blobs no están limitados a formatos de archivo comunes. Un blob podría contener gigabytes de datos binarios transmitidos desde un instrumento científico, un mensaje cifrado para otra aplicación o datos en un formato personalizado para una aplicación que se está desarrollando. 

Blob Storage resulta ideal para lo siguiente:

- Visualización de imágenes o documentos directamente en un explorador.
- Almacenamiento de archivos para acceso distribuido.
- Streaming de audio y vídeo.
- Almacenamiento de datos para copia de seguridad y restauración, recuperación ante desastres y archivado.
- Almacenamiento de datos para el análisis en local o en un servicio hospedado de Azure.
- Almacenamiento de hasta 8 TB de datos para máquinas virtuales.

Los blobs se almacenan en contenedores, lo que ayuda a organizar los blobs en función de sus necesidades empresariales.

#### Disk Storage

Proporciona discos para que las maquinas virtuales, aplicaciones y otros servicios accedan y los utilicen.

#### Azure Files

Recursos compartidos de archivos que puede administrar como un servidor de archivos y acceder a ellos del mismo modo. Los recursos compartidos de Azure se pueden montar simultáneamente en implementaciones de Windows, Linux y macOS en la nube o locales. Las aplicaciones que se ejecutan en máquinas virtuales o servicios en la nube de Azure pueden montar un recurso compartido de almacenamiento de archivos para acceder a datos de archivos, del mismo modo que una aplicación de escritorio montaría un recurso compartido SMB normal.

Todos estos servicios comparten varias características:

- **Durabilidad** y alta disponibilidad con redundancia y la replicación.
- **Seguridad** mediante el cifrado automático y control de acceso basado en rol.
- **Escalabilidad** con un almacenamiento prácticamente ilimitado.
- **Administración** y control del mantenimiento y de cualquier problema crítico que pueda surgir.
- **Accesibilidad** desde cualquier parte del mundo a través de HTTP o HTTPS.

#### Niveles de acceso al almacenamiento
Los datos almacenados en la nube pueden crecer a un ritmo exponencial. Para administrar los costos de las crecientes necesidades de almacenamiento, resulta útil organizar los datos en función de atributos como la frecuencia de acceso y el período de retención planeada.  algunos datos se accede con frecuencia al principio de su duración, mientras que el acceso cae drásticamente a medida que envejecen los datos. Algunos datos permanecen inactivos en la nube y, después de que se almacenan, no se accede a ellos prácticamente nunca.

Azure proporciona varios niveles de acceso, que puede usar para equilibrar los costos de almacenamiento con sus necesidades de acceso.

- **Nivel de acceso frecuente**: optimizado para almacenar datos a los que se accede con frecuencia (por ejemplo, imágenes para el sitio web).
- **Nivel de acceso esporádico**: optimizado para datos a los que se accede con poca frecuencia y que se almacenan al menos durante 30 días (por ejemplo, las facturas de los clientes).
- **Nivel de acceso de archivo**: conveniente para datos a los que raramente se accede y que se almacenan durante al menos 180 días con requisitos de latencia flexibles (por ejemplo, copias de seguridad a largo plazo).

Las siguientes consideraciones se aplican a los distintos niveles de acceso:

- Solo los niveles de acceso frecuente y esporádico se pueden establecer en el nivel de cuenta. El nivel de acceso de archivo no está disponible en el nivel de cuenta.
- Los niveles frecuente, esporádico y de archivo se pueden establecer en el nivel de blob durante la carga o después de esta.
- Los datos del nivel de acceso esporádico pueden tolerar una disponibilidad ligeramente inferior, pero aun así requieren una gran durabilidad, una latencia de recuperación y unas características de rendimiento similares a las de los datos de acceso frecuente. En el caso de los datos de acceso esporádico, un contrato de nivel de servicio (SLA) con una disponibilidad ligeramente inferior y unos costos de acceso mayores, en comparación con los datos de acceso frecuente, es aceptable a cambio de unos costos de almacenamiento menores.
- El almacenamiento de archivo almacena datos sin conexión y ofrece los menores costos de almacenamiento, pero los mayores costos de acceso y rehidratación de datos.

### Bases de datos.

#### Azure Cosmos Database

Base de datos distribuida globalmente que admite opciones NoSQL.

#### Azure SQL Database

Base de datos relacional totalmente administrada con escalado automático, inteligencia integral y seguridad sólida.

#### Azure Database for MySQL

Base de datos relacional MySQL totalmente administrada y escalable con alta disponibilidad y seguridad.

#### Azure Database for PostgreSQL

Base de datos relacional PostgreSQL totalmente administrada y escalable con alta disponibilidad y seguridad.

#### Azure Database for MariaDB

Base de datos relacional MariaDB totalmente administrada y escalable con alta disponibilidad y seguridad.

#### SQL Server en Azure Virtual Machines

Servicio que hospeda aplicaciones empresariales de SQL Server en la nube.

#### Azure Synapse Analytics

Almacén de datos totalmente administrado con seguridad integral en todos los niveles de escala sin costo adicional.

#### Azure SQL Managed Instance

Permite a los clientes de SQL Server subir y trasladar sus aplicaciones locales a la nube con cambios mínimos en aplicaciones y la base de datos:

  - Plataforma como servicio totalmente administrada y permanente.
  - Conserva todas las capacidades de una PaaS (parches automáticos y actualizaciones de versiones, copias de seguridad automáticas y alta disponibilidad).
  - Intercambie licencias existentes por tarifas con descuento en SQL Managed Instance mediante Azure Hybrid Benefit.

#### Móvil

Con Azure, los desarrolladores pueden crear servicios de back-end móviles para aplicaciones iOS, Android y Windows de forma rápida y sencilla. Las características que solían tardar tiempo y aumentaban los riesgos del proyecto, como la incorporación del inicio de sesión corporativo y la posterior conexión a recursos locales como SAP, Oracle, SQL Server y SharePoint, ahora se incluyen con facilidad.

Estas son otras características de este servicio:

- Sincronización de datos sin conexión.
- Conectividad a datos locales.
- Difusión de notificaciones de inserción.
- Escalado automático para satisfacer las necesidades del negocio.

#### WEB

En el mundo empresarial actual es fundamental tener una experiencia web excelente. Azure incluye soporte técnico de primera clase para compilar y hospedar aplicaciones web y servicios web basados en HTTP. Los siguientes servicios de Azure se centran en el hospedaje web.

**Azure App Service**: Creación rápida de aplicaciones en la nube eficaces basadas en web.

**Azure Notification Hubs**: Envíe notificaciones push a cualquier plataforma desde cualquier back-end.

**Azure API Management**: Publique API para desarrolladores, asociados y empleados de forma segura y a escala.

**Azure Cognitive Search**: Esta búsqueda completamente administrada se implementa como servicio.

**Característica Web Apps de Azure App Service**: Cree e implemente rápidamente aplicaciones web críticas a escala.

**Servicio Azure SignalR**: Agregue funcionalidades web en tiempo real con facilidad.

#### Azure MarketPlace

Permite a los clientes encontrar, probar, comprar y aprovisionar aplicaciones y servicios de cientos de proveedores de servicios lideres. Todos certificados para ejecutarse en Azure:

  * Plataformas de contenedores de código abierto.
  * Imágenes de bases de datos y maquinas virtuales.
  * Software de desarrollo e implementación de aplicaciones.
  * Herramientas de desarrollo.
  * y mas.

# Modulo 03 Soluciones principales

## Azure Internet of Things IoT
Esta capacidad de los dispositivos de obtener y luego retransmitir informacion para le analisis de datos, se conoce como IoT (Internet de las cosas).

Algunos sensores comunes que miden los atributos del mundo físico incluyen:

- Sensores de entorno que capturan los niveles de temperatura y humedad.
- Escáneres de códigos de barras, códigos QR o reconocimiento óptico de caracteres (OCR).
- Sensores de proximidad y ubicación geográfica.
- Sensores de luz, color e infrarrojos.
- Sensores de sonido y ultrasonido.
- Sensores táctiles y de movimiento.
- Sensores de inclinación y acelerómetros.
- Sensores de humo, gas y alcohol.
- Detectores de errores para determinar cuándo hay un problema con el dispositivo.
- Sensores mecánicos que detectan anomalías o deformaciones.
- Sensores de flujo, nivel y presión para medir gases y líquidos.




### Azure IoT Central

es una solución global de IoT SaaS totalmente administrada que facilita la conexión, la supervisión y la administración de sus activos de IoT a gran escala. La interfaz de usuario (UI) visual facilita la conexión rápida de nuevos dispositivos y la inspección a medida que comienzan a enviar mensajes de telemetría o de error. Puede ver el rendimiento general de todos los dispositivos en conjunto y configurar alertas que envían notificaciones cuando un dispositivo concreto necesita mantenimiento.

### Azure IoT Hub

es un servicio administrado hospedado en la nube que actua como un centro de mensajes centrarl para la comunicacion bideccional entre aplicaciones IoT y los dispositivos que administra. También admite varios patrones de mensajería, como telemetría de dispositivo a la nube, carga de archivos desde dispositivos y métodos de solicitud-respuesta para controlar los dispositivos desde la nube. Una vez que un centro de IoT recibe los mensajes de un dispositivo, puede enrutarlos a otros servicios de Azure.



### Azure IoT Sphere

es una plataforma de aplicaciones segura de alto nivel con funciones de seguridad y comunicacion integradas para dispositivos conectados a internet.
Azure Sphere consta de tres partes:
• La primera parte es la unidad de microcontrolador (MCU) de Azure Sphere, que se encarga de procesar el sistema operativo y las señales de los sensores conectados. 
• La segunda parte es un sistema operativo (SO) Linux personalizado, que controla la comunicación con el servicio de seguridad y puede ejecutar el software del proveedor.
• La tercera parte es el servicio de seguridad de Azure Sphere, también conocido como AS3. Su trabajo es asegurarse de que el dispositivo no se ha puesto en peligro de forma malintencionada. Cuando el dispositivo intenta conectarse a Azure, primero debe autenticarse, por dispositivo, mediante autenticación basada en certificado. Si se autentica correctamente, AS3 comprueba que el dispositivo no se haya alterado. Una vez que ha establecido un canal de comunicación seguro, AS3 inserta en el dispositivo las actualizaciones de software del sistema operativo o desarrolladas por el cliente (y aprobadas). Los datos se presentan en cualquier formato y tamaño. Cuando hablamos sobre macrodatos, nos referimos a grandes volúmenes de datos. Los datos de los sistemas del tiempo, sistemas de comunicaciones, investigación genómica, plataformas de imágenes y muchos otros escenarios generan cientos de gigabytes de datos. Esta cantidad de datos hace que resulte difícil analizar y tomar decisiones. A menudo es tan grande que las formas de procesamiento y análisis tradicionales ya no son adecuadas.

## Big Data y Analytics

**Azure Synapse Analytics**: Data Warehouse basado en la nube. Ejecute análisis a gran escala mediante un almacenamiento de datos empresarial basado en la nube que aprovecha las ventajas del procesamiento paralelo masivo para ejecutar rápidamente consultas complejas en petabytes de datos.

**Azure HDInsight**: Servicio de análisis de código abierto, totalmente administrado. Procese grandes cantidades de datos con los clústeres administrados de Hadoop en la nube.

**Azure Databricks**: Servicio de análisis basado en Apache Spark. Integre este servicio de análisis colaborativo basado en Apache Spark con otros servicios de macrodatos en Azure.

## Inteligencia Artificial
 la inteligencia artificial se basa en una amplia gama de servicios, donde el principal es el aprendizaje automático. El aprendizaje automático es una técnica de ciencia de datos que permite a los equipos utilizar datos existentes para prever tendencias, resultados y comportamientos futuros. Mediante el aprendizaje automático, los equipos aprenden sin necesidad de programarlos explícitamente.
 Las previsiones o predicciones del aprendizaje automático pueden hacer que las aplicaciones y los dispositivos sean más inteligentes. 

**Azure Machine Learning Service**: Entorno basado en la nube que puede usar para desarrollar, entrenar, probar, implementar, administrar y realizar un seguimiento de los modelos de aprendizaje automático. Puede generar y ajustar automáticamente un modelo. Le permite comenzar a entrenar en el equipo local y luego escalar horizontalmente a la nube.

**Azure ML Studio**: Área de trabajo visual colaborativa donde puede compilar, probar e implementar soluciones de aprendizaje automático mediante algoritmos de aprendizaje automático predefinidos y módulos de control de datos.

**Cognitive Services**: es un conjunto de productos estrechamente relacionados. Puede usar estas API precompiladas en las aplicaciones para solucionar problemas complejos.
Azure Cognitive Services se puede dividir en las categorías siguientes:

- Servicios de **lenguaje**: permita que las aplicaciones procesen lenguaje natural con scripts precompilados, evalúen opiniones y aprendan a reconocer lo que quieren los usuarios.
- Servicios de **voz**: convierta voz en texto y texto en voz de sonido natural. Traduzca de un idioma a otro y habilite el reconocimiento y la verificación del hablante.
- Servicios de **visión**: agregue capacidades de reconocimiento e identificación al analizar imágenes, vídeos y otro contenido visual.
- Servicios de **decisión**: agregue recomendaciones personalizadas para cada usuario que mejoren automáticamente cada vez que se usen, modere contenido para supervisar y quitar el contenido ofensivo o arriesgado y detecte anomalías en los datos de series temporales.

**Azure Bot Service** Bot Framework son plataformas para crear agentes virtuales que comprenden y responden a preguntas como un ser humano. Azure Bot Service se diferencia de Azure Machine Learning y Azure Cognitive Services en que tiene un caso de uso concreto: crear un agente virtual que pueda comunicarse de forma inteligente con los usuarios. En segundo plano, el bot que crea usa otros servicios de Azure, como Azure Cognitive Services, para comprender lo que solicitan sus homólogos humanos.

Los bots se pueden usar para convertir tareas sencillas y repetitivas, como tomar una reserva de cena o recopilar información de perfil, en sistemas automatizados que ya no requieran la intervención humana directa. Los usuarios conversan con un bot mediante texto, tarjetas interactivas y voz. Una interacción con un bot puede ser tanto una pregunta y una respuesta rápidas como una conversación sofisticada que proporciona acceso a servicios de forma inteligente.

## ServerLess(Cómputo sin servidor).

ServerLess es una evolución de la nube, donde los programadores se pueden dedicar a programar sin preocuparse por la infraestructura del servidor. Se utiliza a partir de un Web Request. Se usa para describir un entorno de ejecución que se configura y administra de manera automática. El cliente tan solo debe escribir código o conectar y configurar los componentes en un editor visual y, después, especificar las acciones que desencadenan la funcionalidad, como un temporizador o una solicitud HTTP. Lo mejor de todo es que únicamente se paga en función del uso real del código y que no hay que preocuparse de las interrupciones, dado que el código puede hacer un escalado instantáneo para satisfacer la demanda.


**Azure Functions**: puede hospedar un único método o función mediante un lenguaje de programación popular en la nube que se ejecuta en respuesta a un evento. Un ejemplo de un evento podría ser una solicitud HTTP, un mensaje nuevo en una cola o un mensaje en un temporizador.

Por su naturaleza atómica, Azure Functions puede servir para muchos propósitos en el diseño de una aplicación. Las funciones se pueden escribir con muchos lenguajes de programación comunes, como C#, Python, JavaScript, Typescript, Java y PowerShell.
Azure Functions se escala automáticamente, y los cargos se acumulan solo cuando se desencadena una función. Estas características convierten a Azure Functions en una elección sólida cuando la demanda es variable. Por ejemplo, podría recibir mensajes de una solución de IoT que supervisa una flota de vehículos de reparto. Probablemente llegarán más datos durante el horario comercial. Azure Functions se puede escalar horizontalmente para adaptarse a esas horas de más trabajo.

Una función de Azure es un entorno sin estado. Una función se comporta como si se reiniciara cada vez que responde a un evento. Esta característica resulta muy conveniente para procesar los datos entrantes. Y si el estado es necesario, la función se puede conectar a una cuenta de almacenamiento de Azure.

Azure Functions puede realizar tareas de orquestación mediante una extensión llamada Durable Functions, que permite a los desarrolladores encadenar funciones al tiempo que se mantiene el estado.


**Azure Logic Apps**: es una plataforma de desarrollo de poco código o sin código hospedada como un servicio en la nube. El servicio le ayuda a automatizar y organizar tareas, procesos empresariales y flujos de trabajo cuando tiene que integrar aplicaciones, datos, sistemas y servicios en empresas u organizaciones. Logic Apps simplifica el diseño y la creación de soluciones escalables en la nube, en el entorno local o en ambos. Esta solución abarca la integración de aplicaciones, la integración de datos, la integración de sistemas, la integración de aplicaciones empresariales (EAI) y la integración de negocio a negocio (B2B).

Azure Logic Apps está diseñado en un entorno web y puede ejecutar una lógica que los servicios de Azure desencadenan sin escribir ningún código. Las aplicaciones se pueden compilar vinculando desencadenadores con acciones mediante conectores. Un desencadenador es un evento (como un temporizador) que hace que una aplicación se ejecute, que un mensaje nuevo se envíe a una cola o que se emita una solicitud HTTP. Una acción es una tarea o paso que se puede ejecutar. Hay acciones lógicas, como las que encontraría en la mayoría de los lenguajes de programación. Entre los ejemplos de acciones se incluyen trabajar con variables, instrucciones de decisión y bucles, y tareas que analizan y modifican datos.

**Diferencias**: Azure Functions es un servicio informático sin servidor, y Azure Logic Apps está diseñado para ser un servicio de orquestación sin servidor. Azure Functions es un servicio informático sin servidor, y Azure Logic Apps está diseñado para ser un servicio de orquestación sin servidor. 


## DevOps

DevOps reúne a individuos, procesos y tecnología mediante la automatización de la entrega de software para ofrecer un valor continuo a los usuarios. Con Azure DevOps puede crear, compilar y publicar canalizaciones que proporcionan integración, entrega e implementación continuas a las aplicaciones. Puede integrar los repositorios y las pruebas de aplicaciones, realizar la supervisión de aplicaciones y trabajar con artefactos de compilación. También puede trabajar con elementos de trabajo pendiente para realizar el seguimiento, automatizar la implementación de la infraestructura e integrar una gama de herramientas y servicios de terceros como Jenkins y Chef.

**GitHub**: Hosting de desarrollo de software con control de versiones, gestión de código fuente y administracion de errores y tareas.

**GitHub Actions for Azure**:

**Azure DevOps**: Use herramientas de colaboración de desarrollo como canalizaciones de alto rendimiento, repositorios Git privados gratuitos, paneles Kanban configurables y completas pruebas de carga basadas en la nube y automatizadas. Anteriormente conocido como Visual Studio Team Services.

**Azure DevTest Labs**: Cree rápidamente entornos de Windows y Linux a petición para probar o realizar demostraciones de las aplicaciones directamente desde canalizaciones de implementación.


## Herramientas de Administración de Azure

Azure Portal es una consola unificada basada en web que proporciona una alternativa a las herramientas de línea de comandos. Con Azure Portal, puede administrar la suscripción de Azure mediante una interfaz gráfica de usuario. Puede:

- Compile, administre y supervise todo, desde aplicaciones web sencillas hasta complejas implementaciones en la nube.
- Cree paneles personalizados para una vista organizada de recursos.
- Configure opciones de accesibilidad para una experiencia óptima.

**Herramientas de Administración**

- Azure Portal
- Azure PowerShell
- Azure Mobile App
- Interfaz de la linea de comandos (CLI)
- Azure API Rest
- Azure Cloud Shell
**Azure Resource Manager (ARM)**

##Plantillas de Azure Resource Manager (ARM)
Las plantillas de ARM son archivos JavaScript Object Notation (JSON) que se pueden usar para crear e implementar la infraestructura de Azure sin tener que escribir comandos de programación.

- Sintaxis declarativa
- Resultados repetibles
- organización
- archivos modulares
- Validación incorporada
- Código exportable.


##Azure Advisor
Analiza los recursos de Azure implementados y hace recomendaciones en mejores practicas para optimizar las implementaciones de Azure.

- Confiabilidad
- Seguridad
- Rendimiento
- Costo
- Excelencia operativa

##Azure Monitor
Maximiza la disponibilidad y el rendimiento de aplicaciones y servicios ya que recopila, analiza y actúa basado en temeraria desde entornos en la nube y locales.

- Application Insigths
- Log Analytics
- Alertas Inteligentes
- Acciones de Automatización
- Paneles personalizados.

## Azure Service Health
Permite revisar de manera personalizada el estado de los servicios y las regiones que se utilizan

- Comunicación sobre las interrupciones.
- Mantenimiento planificado
- otros avisos de salud

#Modulo 4

##Azure Security Center
Es un servicios de supervisión que ofrece protección contra amenazas tanto en Azure como en centros de datos locales.

- Proporciona recomendaciones de seguridad
- Detecta y bloquea malware.
- Analiza e identifica posibles ataques.
- Control de accesos para los puertos cuando es necesario.

### Capacidades

1. **Cumplimiento de directivas**: esta construido sobre controles de Azure Policy para que pueda configurar y supervisar sus directivas de forma que se ejecuten en grupos de administración, entre suscripciones e incluso para un tenant entero.
2. **Alertas de seguridad**: Recopila, analiza e integra de forma automática datos de los recursos de Azure, como la proteccion de Endpoints o Firewall, para detectar amenazas reales. Luego se muestra la lista de alertas de seguridad priorizadas en Security Center junto con información que necesita para investigar y remediar rápidamente cualquier ataque.
3. **Puntuación de seguridad**: evalúa continuamente sus recursos en busca de problemas de seguridad; luego agrega todos los resultados en una sola puntuación para que pueda conocer realmente su nivel de seguridad actual.
4. **Protección de seguridad de recursos**: Visibilidad de seguridad y recomendaciones basadas en cargas de trabajo reales con instrucciones sobre como implementarlas.




##Azure Defender 
herramienta antimalware basada en al nube.

## Azure Sentinel
se encarga de la gestión  de la información. Tiene características de respuestas automatizadas, se encarga de recopilar datos de usuarios, de sus dispositivos, aplicaciones, de la infraestructura  pueden ser locales, en Azure, u otras nubes. Con esa información recopilada, es capaz de detectar amenazas, además tiene un motor de IA, que permite disminuir al máximo los falsos positivos.

Otra ventaja es la de conectarse con las integraciones.

- **Microsoft 365**: Suite de productividad en la nube.

- **Azure Active Directory**: Servicio de directorio.

- **Azure advance Threat Protection**: Suite antimalware.

- **Microsoft Cloud App Security**: Tareas de manejo de seguridad a nivel de aplicaciones o servicios para evitar fuga de información.

## Azure Key Vault
Almacén de claves de Azure y luego crea un secreto de contraseña en dicho almacén de claves.  

## Host dedicado de Azure

Servicio que permite arrendar servidores físicos, para alojar uno o mas servidores virtuales, asociados a una suscripción. Este host es similar a los utilizados en Azure, con la salvedad de que este Host se reserva para uso propio y no se comparte.

## Defensa en profundidad
Enfoque por capas para asegurar los sistemas informáticos.
Proporciona múltiples niveles de protecion.
Los ataques contra una capa están aislados de las capas subsiguientes.

### Capas

- Seguridad Física
- Identidad y acceso
- Perímetro
- Red
- Procesamiento
- Aplicación
- Datos

### Seguridad compartida.
La migración desde los centros de datos controlados por el cliente a los basados en la nube cambia la responsabilidad de la seguridad.
La seguridad se convierte en una preocupación compartida entre los proveedores y los clientes de la nube.

## Network Security Group (NSG)
Filtra el trafico de red hacia y desde los recursos de Azure en redes virtuales de Azure.

- Establezca reglas de entrada y salida para filtrar por dirección IP, puerto y protocolo de origen y destino.
- Añada varias reglas según sea necesario dentro de los limites de la suscripción.
- Azure aplica reglas de seguridad predeterminadas de linea base a los nuevos NSG.
- Anule las reglas predeterminadas con nuevas reglas de mayor prioridad.
- No es un Firewall.

## Azure Firewall
Un Firewall como Servicio (FaaS) con estado y administrado que otorga o niega el acceso al servidor en función de la dirección IP de origen para proteger los recursos de red.

- Aplica reglas de filtrado del trafico entrante y saliente.
- Alta disponibilidad incorporada.
- Escalabilidad ilimitada en la nube.
- Utiliza el registro de Azure Monitor.

### Diferencia entre Firewall y NSG
El Firewall es complementario al NSG. El firewall permite proteger los servicios de la red, basados en la dirección de IP.

El NSG es seguridad dentro de los recursos.

El Firewall es seguridad perimetral.

## Protección contra ataques de denegación de servicio (DDoS)
Los ataques DDoS satura y agotan los recursos de la red haciendo que las aplicaciones sean lentas o no respondan.

- Corrige el trafico de red no deseado antes de que afecte a la disponibilidad del servicio.
- El nivel de servicio básico se habilita automáticamente en Azure.
- El nivel de servicio estándar añade capacidades de mitigación, ajustadas para proteger los recursos de Azure Virtual Network.


## Defensa en profundidad revisada
Combinar soluciones de seguridad de red.

- **NSG** con **Azure Firewall** para conseguir una defensa en profundidad.
- La **Capa perimetral** protege los limites de sus redes con Azure DDoS Protection y Azure Firewall.
- **Capa de red**: solo permite que el trafico pase entre los recursos de la red con reglas de entrada y salida de **Network Security Group** (NSG)


# Modulo 5 Identidad, gobernanza, privacidad y cumplimiento normativo.

## Comparación entre autenticación y autorización

**Autenticación**

- Identifica a la persona o el servicio que intenta acceder a un recurso.
- Solicita credenciales de acceso legitimas.
- Bases para crear principios seguros de identidad y control.

**Autorización**

- Determina el nivel de acceso de una persona o servicio autenticados.
- Define a que datos pueden acceder y que pueden hacer con ellos.
- 

## Azure Multi-Factor Authentication
Proporciona seguridad adicional para sus identidades al requerir dos o mas elementos para la autenticación completa.

## Azure Active Directory (AAD)
Es el servicio de administración de identidad y acceso basado en la nube de Microsoft.

- Autenticación (los empleados inician sesión para acceder a los recursos)
- Inicio de sesión único (SSO)
- Administración de aplicaciones.
- Negocio a negocio (B2B)
- Servicios de identidad de negocio a cliente (B2C)
- Administración de dispositivos.

## Acceso condicional
Es lo que utiliza Azure Active Directory para reunir señales, tomar decisiones y aplicar las directivas de la organización.

- Usuario o pertenencia a un grupo.
- Ubicación de la IP
- Dispositivo
- Aplicación
- Detección de riesgos

## Control de Acceso Basado en Roles (RBAC)
Administración de acceso granular.
Separación de tareas dentro del equipo y conceder a los usuarios solo el acceso que necesitan para realizar sus trabajos.
Permite el acceso a Azure Portal y controla el acceso de los recursos.

## Azure Policy
ayuda a hacer cumplir los estándares de la organización y evaluar el cumplimiento a escala. Proporciona gobierno y consistencia de recursos con cumplimiento normativo, seguridad, costes y administración.

- Evalúa e identifica los recursos de Azure que no cumplen las directivas.
- Proporciona definiciones de directivas e iniciativas integradas en categorías como almacenamiento, redes, proceso, security center y supervisión.

## Azure Blueprints
Permite que los equipos de desarrollo puedan construir y poner en marcha nuevos entornos rápidamente. Los equipos de desarrollo pueden generar confianza rápidamente a través del cumplimiento de las políticas de la organización con un conjunto de componentes integrados (como redes ) para acelerar la creación y la entrega.

- Asignaciones de roles.
- Asignaciones de directivas.
- Plantillas de Azure Resource Manager
- Grupos de recursos
- No es igual a políticas, ya que en BP se incorporan los roles, directivas y grupos de recursos específicos. Permite levantar entornos de desarrollo de manera rapida.

## Seguridad, Privacidad y cumplimiento

### Seguridad por diseño.
Gracias a la seguridad inteligente incorporada. Microsoft ayuda a proteger contra ciber amenazas conocidas y desconocidas mediante la automatización y la inteligencia artificial.

### Privacidad
Nos comprometemos a garantizar la privacidad de las organizaciones a través de acuerdos contractuales y proporcionando control y transparencia al usuario.

## Cumplimiento
Representa las leyes y regulaciones locales y brindamos una cobertura integral de las ofertas de cumplimiento.

## Terminos y requisitos de cumplimiento
Microsoft ofrece el conjunto de ofertas de cumplimiento mas completo (incluidas las certificaciones y las garantías) que cualquier otro proveedor de servicios en la nube.
Algunas de las ofertas.

- CJIS Criminal Justice Information Services
- HIPAA: Health Insurance Portability and Accountability Act
- Certificación CSA Star
- ISO/IEC 27018
- EU Model Clauses
- NIST National Institute of Standars and Technology


## Declaracion de privacidad de Microsoft
La declaración de privacidad de Microsoft proporciona transparencia y honestidad acerca de como Microsoft maneja los datos de usuario recopilados en sus productos y servicios.
La declaración de privacidad explica:

- Que datos procesa Microsoft
- Como lo procesa Microsoft
- Para que se utilizan los datos.

## Condiciones de los servicios en linea y anexo de protección de datos

**Condiciones de los servicios en linea**: la licencia define los términos y condiciones de los productos y servicios en linea que se adquieren mediante los programas de licencias por volumen de Microsoft.

**Anexo de protección de datos** establece las obligaciones, con respecto al procesamiento y la seguridad de los datos del cliente y los datos personales, en relación con los servicios en linea.

## Trust Center
Obtenga inflacionario sobre seguridad, privacidad, cumplimientos, directivas, caracteristicas y practicas en los productos en la nube de Microsoft.

El sitio web del Trust Center proporciona lo siguiente

- Información exhaustiva y especializada
- Listas seleccionadas de los recursos recomendados ordenados por tema.
- Información especifica de cada rol para gerentes de negocios, administración, ingenieros, evaluadores de riesgos, oficiales de privacidad y equipos legales.

## Documentacion de cumplimiento de Azure
Microsoft ofrece un conjunto completo de ofertas de cumplimiento para ayudar a su organización a cumplir con los requisitos nacionales, regionales y específicos de la industria que rigen la recopilación y el uso de datos.

- Global
- Gobierno de Estados Unidos
- Industria
- Regional

## NIST
Regiones soberanas de Azure (Gobierno de Estados Unidos)
Cumple las necesidades de seguridad y cumplimiento de las agencias federales de estados Unidos, los gobiernos estatales, y locales, y sus proveedores de soluciones.

### Azure Government

- Instancia separada de Azure.
- Físicamente aislado de los recursos de otros usuarios no gubernamentales.
- Accesible solo para el personal autorizado y seleccionado.
- Ciertas regiones de Azure son para el gobierno de Estados Unidos, nadie mas puede usar esos centros de datos de Azure.

## Instancia separada de Azure Cloud Services y administrada por 21Vianet

### Regiones soberanas de Azure (Azure China)
Microsoft es el primer proveedores extranjero de servicios en la nube publica de China que cumple con las regulaciones gubernamentales.

#### Características de Azure China

- Instancia físicamente separada de Azure Cloud Services y administrada por 21Vianet
- Todos los datos se quedan dentro de china para asegurar el cumplimiento.

# Modulo 06

## Planificación y gestión de costos

- Identificar los factores que puedan afectar los costos ( tipos de recursos, servicios, ubicaciones o trafico de entrada y salida)
- Identificar los factores que puedan reducir los costos (instancias reservadas, capacidad reservada, Hybrid Benefit o precios al contado)
- Describir la funcionalidad y el uso de la calculadora de precios y del costo total de propiedad (TCO)
- Describir la funcionalidad y el uso de Azure Cost Managment.


## 6 factores que afectan los costos

1. Tipos de recursos: los costos son específicos por recurso, por lo que la utilización que registra un medido y la cantidad de medidores asociados con un recurso dependen del tipo de recurso.
2. servicios: Las tasas de uso de Azure y los periodos de facturación pueden diferir entre los clientes de Enterprise, Web direct y CSP. 
3. ubicaciones o trafico de entrada y salida: La infraestructura de Azure se distribuye globalmente y los costos de uso pueden variar entre las ubicaciones que ofrecen productos, servicios y recursos de Azure.
4. Ancho de banda: Algunas transferencias de datos entrantes son gratuitas, como los datos que entran a los centros de datos de Azure. Para las transferencias de datos de salida, como los datos que salen de los centros de datos de Azure, los precios se basan en zonas.

5. Instancias reservadas: Con Azure Reservations, se compromete a adquirir planes de uno o tres años que incluyen varios productos. Con reservation puede reducir los costos de recursos hasta un 72% en los precios de pagos por uso.
6. Ventaja híbrida de Azure: Para clientes con Software Assurance, Azure Hybrid Benefit permite usar licencias locales en Azure, a un costo reducido.

## Calculadora de precios
Es una herramienta que le ayuda a estimar el costo de los productos de Azure. Las opciones que puede configurar en la calculadora de precios varían entre productos, pero las opciones básicas de configuración incluyen:

- Región
- Nivel
- Operaciones de facturación
- Opciones de soporte técnico
- Programas y ofertas
- Precios de desarrollo/pruebas de Azure

## Calculadora del costo de propiedad total
Herramienta para estimar los ahorros de costos que puede realizar migrando a Azure.
Un informe que compara los costos de las infraestructuras locales con los costos del uso de productos y servicios de Azure.

## Azure Cost Managment

- Creación de informes de facturacion
- Datos enriquecidos
- Fijar Presupuestos máximos
- Alertas si se exceden los limites de costos
- Recomendaciones sobre los costos

## Reduccion de costos

- Realizar: Estimaciones de costos usando la calculadora de precios y la calculadora de TCO de Azure.
- Monitorear: El uso con *Azure Advisor* e implementar las recomendaciones.
- Usar: limites de gastos.
- Usar: Azure Reservations y Azure Hybrid Benefit.
- Elegir: Ubicaciones y regiones de bajo costo.
- Mantener: Al día las ofertas mas recientes para clientes y suscripciones de Azure.
- Aplicar: Etiquetas para identificar a los propietarios de los recursos.

## Ciclos de vida de los servicios y los SLA de Azure

## SLA para productos y servicios
Los objetivos de rendimiento se expresan como tiempo de actividad y garantías de conectividad.
Alcance de los destinos de rendimiento de 99% a 99,999%.
Si un servicio no cumple con las garantías, se puede acreditar un porcentaje de las tarifas mensuales del servicio.

SLA     | Tiempo de actividad inactividad
99%     | 7h, 18m, 17s
99,5%   | 3h, 39m, 8s
99,9%   |     43m, 49s
99,95%  |     21m, 54s
99,99%  |      4m, 22s
99,999% |          26s

## Acciones que afectan a los SLA
Disminuye el SLA

- Agregar mas servicios
- Escoger servicios gratis o sin SLA

Aumenta el SLA

- Availability Zones
- Sistemas redundantes

Muchos factores pueden degradar o mejorar un SLA. Una toma de decisiones basada en los objetivos empresariales determinara las metas del SLA.

## Programa Preview de Azure

Con las versiones preliminares de Azure, los usuarios pueden probar la versión beta y otras características de pre lanzamiento, productos, servicios, software y regiones para que den su opinión.

- Versión preliminar publica: todos los clientes de Azure pueden evaluar las nuevas funciones.
- Disponibilidad General (GA): una vez finalizada la versión preliminar publica, todos los clientes de Azure pueden usar las nuevas funciones, la disponibilidad varia según la región.

## Servicios de supervisioon y actualizaciones de características

Las actualizaciones de Azure proporcionan información sobre los productos, los servicios y las características de Azure, así como las hojas de ruta de productos y la disponibilidad.

Ver los detalles sobre todas las actualizaciones de Azure y su estado.

Examine y busque actualizaciones.

Subscribase a las notificaciones de actualización de Azure por RSS.

