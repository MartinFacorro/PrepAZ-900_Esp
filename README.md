# Presentación

- 👋 Hola, Soy @MartinFacorro
- 👀 Me interesa muchísimás cosas, dentro de la tecnología, soy un programador apasionado. Me gusta mucho trabajar en equipo, observar cómo se trabaja y entender el valor del capital humano. En otros ordenes de la vida, me gusta mucho la lectura, no puedo vivir sin estar con un libro en la mano. Su tuviese que recomendar un libro, ese seria "El Mundo de Sofia" una novela de Jostein Gaarder.
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
- Permite la ejecucion de aplicaciones de manera más adecuada.
- Se adecua, con legislaciones o regulaciones de información sensible, para que se mantenga en ubicaciones on-premise.

## Beneficios de la nube

- **Alta disponibilidad**: Capacidad que tienen las infraestructuras para mantenerse funcionando la mayor cantidad de tiempo posible, sin perjudicar la operación.

- **Tolerancia a fallos**: Capacidad de responder a una falla, sin generar la caída completa de los sistemás.

- **Escalabilidad**: Capacidad de agregar instancias o crecer verticalmente, por ejemplo, en la cantidad de máquinas virtuales para operar un sistema. (se realiza de forma manual o automática)

- **Elasticidad**: Capacidad de crecer horizontalmente, en este caso se incrementan los recursos de cómputo a un servicio o sistema. (se realiza de forma manual o automática)

- **Alcance global**: Esta relacionado con las capacidades de latencia por el lado del cliente. Relacionado a regiones, países. 

- **Capacidades de latencia del cliente**: Permite levantar servicios en la ubicación geográfica más cercada, en donde los usuarios los estan consumiendo.

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

Se utiliza para poder desarrollar, implementar software, si preocupaciones sobre la infrastructura.

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

Las aplicaciones lógicas ejecutan flujos de trabajo diseñados para automatizar escenarios empresariales y compilados a partir de bloques lógicos predefinidos. Todos los flujos de trabajo de aplicación lógica de Azure comienzan con un desencadenador, que se activa cuando se produce un evento específico o cuando hay nuevos datos disponibles que cumplen determinados criterios. Con el lanzamiento de un desencadenador, el motor de Logic Apps crea una instancia de aplicación lógica que ejecuta las acciones del flujo de trabajo.

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

### Regiones.

### Zonas de disponibilidad.

### Recursos principales.

### Azure Resources Manager

### Suscripciones

### Grupos de Administracion.

### cómputo (Azure Compute Services).

#### Maquinas virtuales.

#### Servicio de Aplicaciones (Application services).

#### Contenedores (Containers Instances).

#### Azure Kubernetes Services

#### Escritorio Virtual de Windows

### Redes.

#### Azure Virtual Network (VNet)

#### Virtual Private Network Gateway (VPN)

#### Azure Express Route

### Almacenamiento (Azure Storage Services).

#### Contenedores de almacenamiento (Blob Storage)

#### Disk Storage

#### Azure Files

#### Niveles de acceso al almacenamiento

### Bases de datos.

#### Azure Cosmos Database

#### Azure SQL Database

#### Azure Database for MySQL

#### Azure Database for PostgreSQL

#### Azure SQL Managed Instance

#### Azure MarketPlace