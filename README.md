- 👋 Hola, Soy @MartinFacorro
- 👀 Me interesa muchisimas cosas, dentro de la tecnologia, soy un programador apasionado. Me gusta mucho trabajar en equipo, observar como se trabaja y entender el valor del capital humano. En otros ordenes de la vida, me gusta mucho la lectura, no puedo vivir sin estar con un libro en la mano. Su tuviese que recomendar un libro, ese seria "El Mundo de Sofia" una novela de Jostein Gaarder.
- 🌱 Actualmente estoy aprendiendo sobre la nube por supuesto, y continuamente aprendiendo sobre temas de desarrollo.
- 💞️ Estoy buscando colaborar en la comunidad de GitHub, por lo que este repo, es el primero.
- 📫 Cómo llegar a mí podes encontrarme en Twitter buscandome como @FacorroMartin. Tambien podes buscarme en LinkedIn como Martin Facorro.

# Preparacion Azure AZ-900 Español

En este camino del aprendizaje, mientras lo recorro, quiero compartir aquellos recursos que me sirven al momento de preparme.

El objetivo es dar un aporte para vuestros caminos.

Como primer item a compartir. Como cada documentacion que uno requiera recorrer, el mejor lugar donde encontrar informacion es en el site oficial.
Por lo que para iniciar el primer lugar para visitar es el siguiente: <a href="https://docs.microsoft.com/es-mx/learn/azure/"> Azure en Microsoft Learn | Microsoft Docs</a>

A saber, el examen de AZ-900 consta de los siguientes temas.
Este examen incluye seis áreas de dominios de conocimiento:

|                                **Área de dominio AZ-900**                | **Peso**              |
|--------------------------------------------------------------------------|-----------------------|
|                  Descripción de los conceptos de la nube                 | 20-25 %               |
|              Descripción de los servicios básicos de Azure               | 15-20 %               |
|Descripción de las principales soluciones y herramientas de administración de Azure | 10-15 %     |
| Descripción de las características de seguridad general y de seguridad de red | 10-15 %          |
|Descripción de las características de identidad, gobernanza, privacidad y cumplimiento | 20-25 %  |
|Descripción de los Acuerdos de Nivel de Servicio y la administración de costos de Azure | 10-15 % |



<hr />

# <img src="img\intro-to-azure-fundamentals.svg" alt="" style="height: 40px; width:50px;"/> Módulo 1 Conceptos de la nube

**Computo en la nube**: prestación de servicios de computo a través de internet, permite el acceso bajo demanda a un grupo de recursos. Permite innovación mas rapida, recursos flexibles y costos regulables.

## Modelos en la nube

### Nube privada

- Centro de datos propio
- La organización es responsable de operar los servicios que brinda.
- No proporciona accesos ajenos a la organización.

### Nube Publica

- Propiedad del Cloud Services o proveedor de hosting
- Proporciona recursos y servicios a multiples organización y usuarios.
- Se accede a través de una red segura(por lo general internet).

### Nube hibrida

- Combina la nube publica con la privada.
- Permite la ejecucion de aplicaciones de manera mas adecuada.
- Se adecua, con legislaciones o regulaciones de informacion sensible, para que se mantenga en ubicaciones on-premise.

## Beneficios de la nube

- **Alta disponibilidad**: Capacidad que tienen las infraestructuras para mantenerse funcionando la mayor cantidad de tiempo posible, sin perjudicar la operación.

- **Tolerancia a fallos**: Capacidad de responder a una falla, sin generar la caída completa de los sistemas.

- **Escalabilidad**: Capacidad de agregar instancias o crecer verticalmente, por ejemplo en la cantidad de maquinas virtuales para operar un sistema. (se realiza de forma manual o automática)

- **Elasticidad**: Capacidad de crecer horizontalmente, en este caso se incrementan los recursos de computo a un servicio o sistema. (se realiza de forma manual o automática)

- **Alcance global**: Esta relacionado con las capacidades de latencia por el lado del cliente. Relacionado a regiones, paises. 

- **Capacidades de latencia del cliente**: Permite levantar servicios en la ubicación geográfica mas cercada, en donde los usuarios los estan consumiendo.

- **Agilidad**: Capacidad de generar o eliminar un recurso, un sistema de manera rapida y eficiente en el momento que lo creamos conveniente.

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
Estructura mas básica, el proveedor se ocupa de la planta física, de la seguridad, seguridad de red, proveen los servidores y almacenamiento.

### **Plataforma como servicio  (SaaS):** 
Proporciona un entorno para desarrollar, probar e implementar aplicaciones, sin centrarse en la administración de la infraestructura subyacente.

Se utiliza para poder desarrollar, implementar software, si preocupaciones sobre la infrastructura.

### **Software como Servicio (Saas):** 
Los usuarios usan aplicaciones basadas en la nube y se conectan a ellas a través de Internet. Algunos ejemplos: Microsoft 365, correo electrónico, calendario. Aplicaciones 100% en la nube.

### Modelo de Responsabilidad compartida.
La responsabilidad de acceso y de datos siempre es responsabilidad del cliente.

<img src="img\shared-responsibility.svg" alt="" style="height: 340px; width:550px;"/>

### ServerLess o computo sin servidor.

**Azure Functions:** funciones que se ejecutan como servicios. Ejecución en tiempo real, donde se crea el recurso, se utiliza y se desecha. La VENTAJA es el costo, ya que se paga por lo que se consume.

**Azure Logic Apps:** servicio basado en la nube.


# Módulo 2 Conceptos de la nube

## Componentes de Arquitectura

### Regiones.

### Zonas de disponibilidad.

### Recursos principales.

### Azure Resources Manager

### Suscripciones

### Grupos de Administracion.

### Computo (Azure Compute Services).

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