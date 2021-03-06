# **Microsoft Azure Fundamentals Course**

Información resumida de [Adam Marczak - Azure for Everyone](https://www.youtube.com/channel/UCdmEIMC3LBil4o0tjaTbj0w) y [Microsoft Learn AZ-900 Contenido Autodirigido](https://docs.microsoft.com/es-es/learn/certifications/exams/az-900)

## **Temario**
- [**Microsoft Azure Fundamentals Course**](#microsoft-azure-fundamentals-course)
  - [**Temario**](#temario)
  - [**Cloud Computing y Conceptos clave**](#cloud-computing-y-conceptos-clave)
    - [**Cloud Computing**](#cloud-computing)
    - [**Conceptos clave**](#conceptos-clave)
  - [**Recorrido rápido por los servicios generales de Azure**](#recorrido-rápido-por-los-servicios-generales-de-azure)
    - [**Process**](#process)
    - [**Network**](#network)
    - [**Storage**](#storage)
    - [**Databases**](#databases)
    - [**Web**](#web)
    - [**IoT**](#iot)
    - [**Macrodata**](#macrodata)
    - [**AI**](#ai)
    - [**DevOps**](#devops)
  - [**Principios de economía de escala**](#principios-de-economía-de-escala)
  - [**CapEx vs OpEx y sus diferencias**](#capex-vs-opex-y-sus-diferencias)
  - [**Modelo basado en el consumo**](#modelo-basado-en-el-consumo)
  - [**IaaS vs PaaS vs SaaS Modelo de servicio cloud**](#iaas-vs-paas-vs-saas-modelo-de-servicio-cloud)
    - [**Características de los modelos de servicio**](#características-de-los-modelos-de-servicio)
    - [**Matriz de responsabilidad**](#matriz-de-responsabilidad)
  - [**Modelos de implementación de nube pública, privada e híbrida**](#modelos-de-implementación-de-nube-pública-privada-e-híbrida)
    - [**Nube pública**](#nube-pública)
    - [**Nube privada**](#nube-privada)
    - [**Nube híbrida**](#nube-híbrida)
  - [**Geografía, Regiones y Zonas de disponibilidad**](#geografía-regiones-y-zonas-de-disponibilidad)
    - [**Data Center**](#data-center)
    - [**Región**](#región)
    - [**Zona de disponibilidad**](#zona-de-disponibilidad)
    - [**Conjunto de disponibilidad**](#conjunto-de-disponibilidad)
    - [**Pares de regiones**](#pares-de-regiones)
    - [**Geografías**](#geografías)
  - [**Resources, Resources Groups y Resource Manager**](#resources-resources-groups-y-resource-manager)
    - [**Resource**](#resource)
    - [**Resources Groups (Grupo de recursos)**](#resources-groups-grupo-de-recursos)
    - [**Resource Manager (Administrador de recursos)**](#resource-manager-administrador-de-recursos)
    - [**Información adicional**](#información-adicional)
  - [**Servicios de cómputo (Azure Compute)**](#servicios-de-cómputo-azure-compute)
    - [**Virtualización**](#virtualización)
    - [**Azure Virtual Machine (Máquina virtual)**](#azure-virtual-machine-máquina-virtual)
    - [**Azure Virtual Machine Scale Sets (Conjuntos de escalado de máquinas virtuales)**](#azure-virtual-machine-scale-sets-conjuntos-de-escalado-de-máquinas-virtuales)
    - [**Azure Batch**](#azure-batch)
    - [**Azure Virtual Desktop**](#azure-virtual-desktop)
    - [**Contenedores**](#contenedores)
    - [**Azure Containers Instance (Instancias de contenedores)**](#azure-containers-instance-instancias-de-contenedores)
    - [**Azure Kubernetes Services (AKS)**](#azure-kubernetes-services-aks)
    - [**Azure App Service**](#azure-app-service)
      - [**Tipos de servicios de aplicaciones**](#tipos-de-servicios-de-aplicaciones)
    - [**Azure Functions**](#azure-functions)
    - [**Azure Logic Apps**](#azure-logic-apps)
    - [**Resumen**](#resumen)
  - [**Servicios de red**](#servicios-de-red)
    - [**Azure Networking (Redes Azure)**](#azure-networking-redes-azure)
    - [**Azure Virtual Network (Red virtual)**](#azure-virtual-network-red-virtual)
    - [**Azure VPN Gateway**](#azure-vpn-gateway)
      - [**Redes privadas virtuales basadas en directivas**](#redes-privadas-virtuales-basadas-en-directivas)
      - [**Redes privadas virtuales basadas en rutas**](#redes-privadas-virtuales-basadas-en-rutas)
      - [**Tamaños de las instancias de VPN Gateway**](#tamaños-de-las-instancias-de-vpn-gateway)
    - [**Azure ExpressRoute**](#azure-expressroute)
    - [**Azure Load Balancer (Equilibrador de carga)**](#azure-load-balancer-equilibrador-de-carga)
    - [**Azure Application Gateway**](#azure-application-gateway)
    - [**Azure Content Delivery Network (Red de entrega de contenidos)**](#azure-content-delivery-network-red-de-entrega-de-contenidos)
  - [**Servicios de almacenamiento**](#servicios-de-almacenamiento)
    - [**Tipos de datos**](#tipos-de-datos)
    - [**Storage Account (Cuenta de almacenamiento)**](#storage-account-cuenta-de-almacenamiento)
    - [**Blob Storage**](#blob-storage)
    - [**Queue Storage**](#queue-storage)
    - [**Table Storage**](#table-storage)
    - [**File Storage**](#file-storage)
    - [**Disk Storage**](#disk-storage)
  - [**Servicios de bases de datos**](#servicios-de-bases-de-datos)
    - [**Tipos de datos en las BD**](#tipos-de-datos-en-las-bd)
    - [**Azure Cosmos DB**](#azure-cosmos-db)
    - [**Azure SQL Database**](#azure-sql-database)
    - [**Azure SQL product family**](#azure-sql-product-family)
  - [**Azure Marketplace**](#azure-marketplace)
  - [**Servicios IoT**](#servicios-iot)
    - [**Azure IoT Hub**](#azure-iot-hub)
    - [**Azure IoT Central**](#azure-iot-central)
    - [**Azure Sphere**](#azure-sphere)
  - [**Servicios Big Data & Analytics**](#servicios-big-data--analytics)
    - [**Azure Synapse Analytics**](#azure-synapse-analytics)
    - [**Azure HDInsight**](#azure-hdinsight)
    - [**Azure Databricks**](#azure-databricks)
    - [**Azure Data Lake Analytics**](#azure-data-lake-analytics)
  - [**Servicios de IA**](#servicios-de-ia)
    - [**Azure Machine Learning**](#azure-machine-learning)
    - [**Azure Cognitive Service**](#azure-cognitive-service)
    - [**Azure Bot Service**](#azure-bot-service)
  - [**Servicios serverless computing**](#servicios-serverless-computing)
    - [**Azure Functions**](#azure-functions-1)
    - [**Azure Logic Apps**](#azure-logic-apps-1)
    - [**Azure Event Grid**](#azure-event-grid)
  - [**Soluciones DevOps**](#soluciones-devops)
    - [**Azure DevOps Services**](#azure-devops-services)
    - [**Azure DevTest Labs**](#azure-devtest-labs)
  - [**Azure Tools**](#azure-tools)
    - [**Azure Portal**](#azure-portal)
    - [**Azure PowerShell**](#azure-powershell)
    - [**Azure CLI**](#azure-cli)
    - [**Azure Cloud Shell**](#azure-cloud-shell)
  - [**Soluciones de supervisión**](#soluciones-de-supervisión)
    - [**Azure Advisor**](#azure-advisor)
    - [**Azure Monitor**](#azure-monitor)
    - [**Azure Service Health**](#azure-service-health)
  - [**Servicios de seguridad de red**](#servicios-de-seguridad-de-red)
    - [**Azure Firewall**](#azure-firewall)
    - [**Azure DDoS Protección**](#azure-ddos-protección)
  - [**Grupos de seguridad Azure**](#grupos-de-seguridad-azure)
    - [**Grupos de seguridad de red**](#grupos-de-seguridad-de-red)
    - [**Grupos de seguridad de aplicaciones**](#grupos-de-seguridad-de-aplicaciones)
    - [**Combinación de servicios de Azure para una solución de seguridad de red completa**](#combinación-de-servicios-de-azure-para-una-solución-de-seguridad-de-red-completa)
  - [**Rutas definidas por el usuario (UDR) con tablas de rutas**](#rutas-definidas-por-el-usuario-udr-con-tablas-de-rutas)
    - [**Enrutamiento(Routing)**](#enrutamientorouting)
    - [**User-defined Routes(UDR)**](#user-defined-routesudr)
  - [**Azure Identity Services**](#azure-identity-services)
    - [**Identidad**](#identidad)
    - [**Autenticación(AuthN)**](#autenticaciónauthn)
    - [**Autorización(AuthZ)**](#autorizaciónauthz)
    - [**Gestión de Acceso**](#gestión-de-acceso)
    - [**Azure AD**](#azure-ad)
    - [**Autenticación multifactor (MFA)**](#autenticación-multifactor-mfa)
    - [**Acceso condicional**](#acceso-condicional)
  - [**Herramientas de seguridad**](#herramientas-de-seguridad)
    - [**Azure Security Center**](#azure-security-center)
    - [**Azure Sentinel**](#azure-sentinel)
    - [**Azure Key Vault**](#azure-key-vault)
    - [**Azure Dedicated Host**](#azure-dedicated-host)
  - [**Gobernanza en Azure**](#gobernanza-en-azure)
    - [**Azure Role-based Access Control (RBAC)**](#azure-role-based-access-control-rbac)
    - [**Azure Resource Locks**](#azure-resource-locks)
    - [**Azure Resource Tags**](#azure-resource-tags)
    - [**Azure Policy**](#azure-policy)
    - [**Azure Blueprints**](#azure-blueprints)
    - [**Cloud Adoption Framework for Azure**](#cloud-adoption-framework-for-azure)
      - [**Adopción de la nube**](#adopción-de-la-nube)
      - [**Marco de adopción de la nube**](#marco-de-adopción-de-la-nube)
      - [**Estrategía**](#estrategía)
      - [**Plan**](#plan)
      - [**Comienzo**](#comienzo)
      - [**Adopción**](#adopción)
      - [**Gobierno y Administración**](#gobierno-y-administración)
      - [**Organizar**](#organizar)
  - [**Core tenets of Security,Privacy,Compliance(Trust Center,DPA,OST y más)**](#core-tenets-of-securityprivacycompliancetrust-centerdpaost-y-más)
    - [**Azure Government**](#azure-government)
    - [**Azure China 21Vianet**](#azure-china-21vianet)
    - [**Regiones soberanas de Azure**](#regiones-soberanas-de-azure)
  - [**Planeación y administración de costos de Azure**](#planeación-y-administración-de-costos-de-azure)
    - [**Cost Reduction Methods, Reservations, Hybrid benefit, Spot VM, Pricing y TCO**](#cost-reduction-methods-reservations-hybrid-benefit-spot-vm-pricing-y-tco)
      - [**Reservaciones en Azure**](#reservaciones-en-azure)
      - [**Máquinas virtuales al contado de Azure**](#máquinas-virtuales-al-contado-de-azure)
      - [**Beneficio de uso híbrido**](#beneficio-de-uso-híbrido)
      - [**Herramientas**](#herramientas)
    - [**Azure Cost Managment**](#azure-cost-managment)
      - [**Administración de costos de Azure**](#administración-de-costos-de-azure)
      - [**Minimización de costos en Azure**](#minimización-de-costos-en-azure)
  - [**SLA y SLA Compuesto en Azure**](#sla-y-sla-compuesto-en-azure)
    - [**Acuerdo de nivel de servicio de aplicación**](#acuerdo-de-nivel-de-servicio-de-aplicación)
    - [**Formulas**](#formulas)
    - [**Elementos clave**](#elementos-clave)
  - [**Ciclo de vida de un servicio en Azure | Public preview and General availability**](#ciclo-de-vida-de-un-servicio-en-azure--public-preview-and-general-availability)
    - [**Ciclo de vida del servicio**](#ciclo-de-vida-del-servicio)
    - [**Información clave de vista previa pública**](#información-clave-de-vista-previa-pública)

## **Cloud Computing y Conceptos clave**
### **Cloud Computing**
**Cloud Computing o Informática en la nube** es un modelo de prestación de servicios a través de internet (nube). Esto incluye pero no se limita a
- **Compute power** - Es decir, servidores como Windows, Linux, entornos de alojamiento, etc.
- **Storage** - Como archivos y/o bases de datos
- **Networking** - En **Azure** pero también fuera cuando se conecta a la red de su empresa
- **Analytics** - Servicios de visualización y datos de telemetría  


<img src="Images/Cloud-Computing.png" alt="Cloud-Computing" width="400" class="center"/>

### **Conceptos clave**
**Notará una similitud en Scalability y Elasticity. Pero la diferencia radica en que Scalability es una propiedad de los recursos que ofrece Azure y Elasticity es la gestión dinámica(o también automática) que ofrece Azure usando la propiedad Scalability de los recursos**

- **Scalability** - Es la capacidad de escalar, así que asigna y desasigna recursos en cualquier momento.  
<img src="Images/Scalability.png" alt="Scalability" width="400"/>

- **Elasticity** - Es la capacidad de escalar dinámicamente.  
<img src="Images/Elasticity.png" alt="Elasticity" width="400"/>

- **Agility** - Es la capacidad de reaccionar rápido (escala rápidamente).  
<img src="Images/Agility.png" alt="Agility" width="400"/>

- **Fault tolerance** - Es la capacidad de mantener el tiempo de actividad del sistema mientras ocurren fallas físicas y de componentes de servicio.  
<img src="Images/Fault-Tolerance.png" alt="Fault-Tolerance" width="400"/>

- **Disaster Recovery** - Es el proceso y principio de diseño que permite que un sistema se recupere de desastres naturales o inducidos por el hombre.  
<img src="Images/Disaster-Recovery.png" alt="Disaster-Recovery" width="400"/> 

- **High Availability** - Es el nivel acordado de tiempo de actividad operativa para el sistema. Es un cálculo simple del tiempo de actividad del sistema frente a toda la vida útil del sistema.  
`disponibilidad = tiempo de actividad/(tiempo de actividad + tiempo de inactividad)`  
<img src="Images/High-Availability.png" alt="High-Availability" width="400"/>  

## **Recorrido rápido por los servicios generales de Azure**
<img src="Images/Servicios-Azure.png" alt="Servicios-Azure" width="900"/>

### **Process**
**Azure Virtual Machines** - Máquinas virtuales (VM) Windows o Linux hospedadas en Azure.  
**Azure Virtual Machine Scale Sets** - Escalado de máquinas virtuales Windows o Linux hospedadas en Azure.  
**Azure Kubernetes Service** - Administración de clústeres para máquinas virtuales que ejecutan servicios en contenedores.  
**Azure Service Fabric** - Plataforma de sistemas distribuidos que se ejecuta en Azure o en el entorno local.  
**Azure Batch** - Servicio administrado para aplicaciones informáticas de alto rendimiento y paralelas.  
**Azure Container Instances** - Aplicaciones en contenedores que se ejecutan en Azure sin necesidad de aprovisionar servidores ni máquinas virtuales.  
**Azure Functions** - Un servicio de procesos sin servidor y controlado por eventos.  
### **Network**
**Azure Virtual Network** - Conecta máquinas virtuales a conexiones de red privada virtual (VPN) entrantes.  
**Azure Load Balancer** - Equilibra las conexiones entrantes y salientes a aplicaciones o puntos de conexión de servicio.  
**Azure Application Gateway** - Optimiza la entrega de granjas de servidores de aplicaciones y, al mismo tiempo, aumenta la seguridad de las aplicaciones.  
**Azure VPN Gateway** - Accede a redes de Azure Virtual Network mediante puertas de enlace de VPN de alto rendimiento.  
**Azure DNS** - Proporciona respuestas DNS ultrarrápidas y disponibilidad de dominio extremadamente alta.  
**Azure Content Delivery Network** - Entrega contenido de gran ancho de banda a los clientes globalmente.  
**Azure DDoS Protection** - Protege las aplicaciones hospedadas en Azure frente a ataques por denegación de servicio distribuido (DDoS).  
**Azure Traffic Manager** - Distribuye el tráfico de red entre las regiones de Azure en todo el mundo.  
**Azure ExpressRoute** - Se conecta a Azure mediante conexiones seguras de gran ancho de banda dedicadas.  
**Azure Network Watcher** - Supervisa y diagnostica problemas de red mediante el análisis basado en el escenario.  
**Azure Firewall** - Implementa un firewall de alta seguridad y alta disponibilidad con escalabilidad ilimitada.  
**Azure Virtual WAN** - Crea una red de área extensa (WAN) unificada que conecta sitios locales y remotos.  
### **Storage**
**Azure Blob Storage** - Servicio de almacenamiento para objetos muy grandes, como archivos de vídeo o mapas de bits.  
**Azure File Storage** - Recursos compartidos de archivos que puede administrar como un servidor de archivos y acceder a ellos del mismo modo.  
**Azure Queue Storage** - Almacén de datos para la puesta en cola y la entrega confiable de mensajes entre aplicaciones.  
**Azure Table Storage** - Table Storage es un servicio que almacena datos estructurados no relacionales (también conocidos como datos NoSQL estructurados) en la nube, lo que proporciona un almacén de claves y atributos con un diseño sin esquema.  
### **Databases**
**Azure Cosmos DB** - Base de datos distribuida globalmente que admite opciones NoSQL.  
**Azure SQL Database** - Base de datos relacional totalmente administrada con escalado automático, inteligencia integral y seguridad sólida.  
**Azure Database for MySQL** - Base de datos relacional MySQL totalmente administrada y escalable con alta disponibilidad y seguridad.  
**Azure Database for PostgreSQL** - Base de datos relacional PostgreSQL totalmente administrada y escalable con alta disponibilidad y seguridad.  
**SQL Server en Azure Virtual Machines** - Servicio que hospeda aplicaciones empresariales de SQL Server en la nube.  
**Azure Synapse Analytics** - Almacén de datos totalmente administrado con seguridad integral en todos los niveles de escala sin costo adicional.  
**Azure Database Migration Service** - Servicio que migra bases de datos a la nube sin cambios en el código de aplicación.  
**Azure Cache for Redis** - Servicio totalmente administrado que almacena en caché datos estáticos y usados con frecuencia para reducir la latencia de datos y aplicaciones.  
**Azure Database for MariaDB** - Base de datos relacional MariaDB totalmente administrada y escalable con alta disponibilidad y seguridad.  
### **Web**
**Azure App Service** - Creación rápida de aplicaciones en la nube eficaces basadas en web.  
**Azure Notification Hubs** - Envíe notificaciones push a cualquier plataforma desde cualquier back-end.  
**Azure API Management** - Publique API para desarrolladores, asociados y empleados de forma segura y a escala.  
**Azure Cognitive Search** - Esta búsqueda completamente administrada se implementa como servicio.  
**Característica Web Apps de Azure App Service** - Cree e implemente rápidamente aplicaciones web críticas a escala.  
**Servicio Azure SignalR** - Agregue funcionalidades web en tiempo real con facilidad.  
### **IoT**
**IoT Central** - Solución global de software como servicio (SaaS) de IoT totalmente administrada que facilita la conexión, la supervisión y la administración de los recursos de IoT a escala.  
**Azure IoT Hub** - Centro de mensajería que proporciona comunicaciones y supervisión seguras entre millones de dispositivos de IoT.  
**IoT Edge** - Servicio totalmente administrado que permite insertar los modelos de análisis de datos directamente en los dispositivos IoT, lo que les permite responder rápidamente a los cambios de estado sin necesidad de consultar modelos de IA basados en la nube.  
### **Macrodata**
**Azure Synapse Analytics** - Ejecute análisis a gran escala mediante un almacenamiento de datos empresarial basado en la nube que aprovecha las ventajas del procesamiento paralelo masivo para ejecutar rápidamente consultas complejas en petabytes de datos.  
**HDInsight de Azure** - Procese grandes cantidades de datos con los clústeres administrados de Hadoop en la nube.  
**Azure Databricks** - Integre este servicio de análisis colaborativo basado en Apache Spark con otros servicios de macrodatos en Azure.  
### **AI**
**Azure Machine Learning Service** - Entorno basado en la nube que puede usar para desarrollar, entrenar, probar, implementar, administrar y realizar un seguimiento de los modelos de aprendizaje automático. Puede generar y ajustar automáticamente un modelo. Le permite comenzar a entrenar en el equipo local y luego escalar horizontalmente a la nube.  
**Azure ML Studio** - Área de trabajo visual colaborativa donde puede compilar, probar e implementar soluciones de aprendizaje automático mediante algoritmos de aprendizaje automático predefinidos y módulos de control de datos.  
**Cognitive Services** - Es un conjunto de productos estrechamente relacionados. Puede usar estas API precompiladas en las aplicaciones para solucionar problemas complejos:  
  - **Visión** - Use algoritmos de procesamiento de imágenes para identificar, subtitular, indexar y moderar imágenes y vídeos.  
  - **Voz** - Convierta voz en texto, use la voz para la comprobación o agregue reconocimiento del hablante a la aplicación.  
  - **Asignación de conocimiento** - Asigne información y datos complejos para resolver tareas como las de recomendaciones inteligentes y búsqueda semántica.  
  - **Bing Search** - Agregue las Bing Search API a sus aplicaciones y aproveche la capacidad de combinar miles de millones de páginas web, imágenes, vídeos y noticias con una sola llamada API.  
  - **Procesamiento de lenguaje natural** - Permita que las aplicaciones procesen lenguaje natural con scripts precompilados, evalúen opiniones y aprendan a reconocer lo que quieren los usuarios.  
### **DevOps**
**Azure DevOps** - Use herramientas de colaboración de desarrollo como canalizaciones de alto rendimiento, repositorios Git privados gratuitos, paneles Kanban configurables y completas pruebas de carga basadas en la nube y automatizadas. Anteriormente conocido como Visual Studio Team Services.  
**Azure DevTest Labs** - Cree rápidamente entornos de Windows y Linux a petición para probar o realizar demostraciones de las aplicaciones directamente desde canalizaciones de implementación.  
## **Principios de economía de escala**
El principio de economías de escala establece que a medida que las empresas crecen, se vuelven más efectivas en la gestión de operaciones compartidas. Ya sea recursos humanos y contratación, impuestos, contabilidad, operaciones internas, marketing, grandes compras a través de contratos que significan mejores descuentos, etc.  
Por eso, las empresas pueden ahorrar/ganar más, lo que a cambio les permite reducir el costo de sus servicios para sus clientes. Esto se llama **'precio por unidad'**.  
No es posible ir a 0 porque, al final, se debe ejecutar alguna infraestructura subyacente para proporcionar los servicios. Pero cuanto mayor sea la escala, más beneficios se pueden transferir a los clientes.  
De hecho, en la escala actual, Microsoft ya puede ofrecer múltiples servicios de forma gratuita debido a lo pequeña que es una fracción del costo para ellos.  
<div>
    <img src="Images/Economies-of-scale.png" alt="Economies-of-scale" width="380"/>  
    <img src="Images/Economies-of-scale-2.png" alt="Economies-of-scale-2" width="430"/>  
</div> 

## **CapEx vs OpEx y sus diferencias**
Diferencias entre gastos de capital(CapEx) y gastos operativos(OpEx)

/  |Gastos de capital|Gastos operacionales
---|---|---
Costo inicial|Significativo|Ninguno
Costo continuo|Bajo|Basado en el uso
Deducción fiscal|Tiempo extraordinario|Mismo año
Terminación anticipada|No|En cualquier momento
Mantenimiento|Significativo|Bajo
Valor en el tiempo|Disminuyen|Sin cambio
<div>
<img src="Images/CapEx.png" alt="CapEx" title="CapEx" width="300"/> 
<img src="Images/OpEx.png" alt="OpEx" title="OpEx" width="300"/> 
</div>  

Pregunta: `Having your own datacenter infraesutrcture has a big ______ cost associated`.  
Respuesta: `Initial`.  

## **Modelo basado en el consumo**
El modelo basado en el consumo es un modelo de precios que se utiliza en la nube para que a los clientes solo se les cobre en función de su uso de recursos.  
Este modelo se caracteriza por  

- **Sin costo inicial asociado**
- **No se desperdician recursos** como tal, *no se incurre en cargos por recursos no utilizados*. No utilizado en este caso es diferente por servicio. Por ejemplo, Se considera que se usa el almacenamiento de blobs que almacena cualquier dato, ya que consume el espacio de almacenamiento. Las máquinas virtuales que se ejecutan consumen CPU, memoria y otros recursos incluso si no hay tráfico. Por lo tanto, se consideran utilizados y generarán cargos.
- **Paga por lo que necesitas**
- **Deja de pagar cuando no lo haces**  
**El consumo** es la métrica virtual que se usa para calcular cuánto se usó cada recurso (servicio) en Azure. Cada servicio tiene muchas métricas más pequeñas que rastrean su consumo para ofrecer el mejor modelo de precios posible. Esas métricas se rastrean en un nivel muy granular.  
<img src="Images/Consumption-based-model.png" alt="CapEx" title="CapEx" width="400"/> 

[Consumption based Model - AZ-900 - Chapter Demo](https://youtu.be/NdqncsMtryY?list=PLGjZwEtPN7j-Q59JYso3L4_yoCjj2syrM) 

## **IaaS vs PaaS vs SaaS Modelo de servicio cloud**
Como servicio significa qué capa en particular administrará y todas las capas por encima.

- La capa de **Software** consiste en la aplicación (código y conjunto de la aplicación) y los datos de la aplicación. 
- La capa de **Platform** significa todo el software de soporte y el sistema oeprativo necesarios para alojar la aplicación.
- La capa de **Infraestructure** consta de hardware, la infraestructura y la virtualización necesarias para alojar la plataforma.

<img src="Images/Traditional.png" alt="Traditional" width="800"/> 

### **Características de los modelos de servicio**
- **IaaS** - Se aplica el modelo de responsabilidad compartida; el usuario administra y mantiene los servicios que ha aprovisionado, y el proveedor de nube administra y mantiene la infraestructura en la nube.
- **IaaS** - Es el servicio en la nube más flexible, ya que se dispone de control para configurar y administrar el hardware que ejecuta una aplicación.
- **PaaS** - Es más ágil que IaaS.
- **PaaS** - Es posible que en las plataformas en la nube haya una serie de limitaciones que pueden afectar al modo en el que una aplicación se ejecuta.

### **Matriz de responsabilidad**
Como tal, la siguiente tabla representa las responsabilidades.  
Layer(Capa)     |On-Premises|IaaS          |PaaS           |SaaS
---             |---       |---           |---            |---
Application     |Tú        |Tú           |Tú            |Cloud provider
Data            |Tú        |Tú           |Tú            |Cloud provider
Runtime         |Tú        |Tú           |Cloud provider |Cloud provider
Middleware      |Tú        |Tú           |Cloud provider |Cloud provider
Operating System|Tú        |Tú           |Cloud provider |Cloud provider
Virtualization  |Tú        |Cloud provider|Cloud provider |Cloud provider
Servers         |Tú        |Cloud provider|Cloud provider |Cloud provider
Networking      |Tú        |Cloud provider|Cloud provider |Cloud provider
Storage         |Tú        |Cloud provider|Cloud provider |Cloud provider

\  |Algunos Casos de Uso| Algunos Servicios de Azure
---|---|---
IaaS|<ul><li>Migración de cargas de trabajo</li><li>Test y Desarrollo</li><li>Almacenamiento</li><li>Backups y Recovery</li></ul>|<ul><li>Virtual Machine</li><li>Virtual Network</li><li>Managed Disk</li></ul>
PaaS|<ul><li>Development framework</li><li>Analytics & Business intelligence</li></ul>|<ul><li>SQL</li><li>App Service</li><li>Logic Apps</li><li>Function Apps</li></ul>
SaaS|<ul><li>Compra de aplicaciones shell</li></ul>|<ul><li>One Drive</li><li>Outlook</li><li>Skype</li></ul>

**NOTA** : Si instala SQL Server en una máquina virtual manualmente o al usar una imagen lista para usar, sigue siendo una máquina virtual. Eso significa que los clientes aún necesitan administrar todos
los aspectos de la plataforma. Esto incluye el sistema operativo,configuraciones, parches, middleware, configuraciones de tiempo de ejecución de SQL Server, etc. Como tal, sigue siendo una infraestructura como servicio.  
Azure tiene una opción para Azure SQL Server en máquina virtual donde todas las actualizaciones/copias de seguridad están automatizadas pero incluso Microsoft en su sitio web considera esta opción como IaaS,pero la línea es muy delgada aquí.

## **Modelos de implementación de nube pública, privada e híbrida**
El modelo de implementación en la nube es una separación simple que describe dónde se implementan los recursos de la empresa. Siempre que sea en un entorno de proveedor de nube pública o en un centro de datos privado.
### **Nube pública**
✅ Cloud Provider  ✖  Own Datacenter    
**Caracteristicas claves**
- Todo se ejecuta en el hardware del proveedor de la nube
- Sin hardware local
- Algunos servicios comparten hardware con otros clientes 

<table>
  <tr>
    <th>Ventajas</th>
    <th>Desventajas</th>
  </tr>
  <tr>
    <td><ul><li>Sin CapEx</li><li>Alta disponibilidad</li><li>Agilidad</li><li>Precios por pago de uso</li><li>Sin mantenimiento de hardware</li><li>No se requieren habilidades técnicas profundas</li></ul></td>
    <td><ul><li>No se pueden cumplir todas las políticas de seguridad y cumplimiento</li><li>Sin propiedad sobre la infraestructura física</li><li>No se pueden hacer escenarios específicos raros</li></ul></td>
  </tr>
</table>

### **Nube privada**
✖  Cloud Provider  ✅ Own Datacenter  
**Caracteristicas claves**
- Todo se ejecuta en su propio centro de datos
- Se debe proporcionar autoservicio
- Tú mantienes el hardware

<table>
  <tr>
    <th>Ventajas</th>
    <th>Desventajas</th>
  </tr>
  <tr>
    <td><ul><li>Puede soportar cualquier escenario</li><li>Control total sobre la seguridad y la infraestructura</li><li>Puede cumplir con cualquier política de seguridad y cumplimiento</li></ul></td>
    <td><ul><li>Se requiere inversión inicial</li><li>Agilidad limitada restringida por la capacidad del servidor y las habilidades del equipo</li><li>Muy dependiente de las habilidades y la experiencia en TI</li></ul></td>
  </tr>
</table>

### **Nube híbrida**
✅ Cloud Provider  ✅ Own Datacenter  
**Caracteristicas claves**  
- Combina la nube pública y privada

<table>
  <tr>
    <th>Ventajas</th>
    <th>Desventajas</th>
  </tr>
  <tr>
    <td><ul><li>Gran flexibilidad</li><li>Puede ejecutar cualquier aplicación heredada en la nube privada</li><li>Puede utilizar la infraestructura existente</li><li>Cumplir con los requisitos de seguridad y cumplimientos</li><li>Puede aprovechar todos los beneficios de la nube pública</li></ul></td>
    <td><ul><li>Puede ser más caro</li><li>Complicado de manejar debido a un paisaje más grande</li><li>Más dependiente de las habilidades y la experiencia en TI de los tres modelos</li></ul></td>
  </tr>
</table>

## **Geografía, Regiones y Zonas de disponibilidad**
  * Products available by region: https://azure.microsoft.com/en-us/global-infrastructure/services/
  * 🌐 Azure Speed Test 2.0: http://azurespeedtest.azurewebsites.net/

### **Data Center**
- **Instalación física**.
- **Hosting** para grupo de **servidores** en red.
- Infraestructura propia de **energía**, **refrigeración** y **redes**.

<img src="Images/Data-center.png" alt="Data Center" width="400"/> 

### **Región**
- **Área geográfica** en el planeta.
- **Uno, pero generalmente más centros de datos** conectados con una **red de baja latencia** (<2 milisegundos).
- **Ubicación** para sus servicios.
- Algunos servicios están **disponibles solo en ciertas regiones**.
- Algunos servicios son **servicios globales**, por lo que no se asignan/implementan en una región específica.
- Disponible globalmente con más de **50+ regiones**.
- **Regiones gubernamentales** especiales (US DoD Central, US Gov Virginia, etc.).
- **Regiones asociadas** especiales (Este de China, Norte de China).
<div>
<img src="Images/Regions.png" alt="Regions" width="900"/> 
<img src="Images/Regions-2.png" alt="Regions" width="400"/> 
</div>

### **Zona de disponibilidad**
Debido a que no tiene control sobre en qué centro de datos se implementa sus servicios, se ofrece esta característica única dónde cada **centro de datos recibe un número**, que representa un grupo de instalaciones separadas físicamente 

- **Característica regional**.
- Agrupación de instalaciones **separadas físicamente**.
- Diseñado para **proteger de fallas en el centro de datos**.
- Si la zona se cae, **otros continúan trabajando**.
- Dos **categorías** de servicio:
  - Servicios **zonales** (Máquinas Virtuales, Discos, etc.).
  - Servicios con **redundancia de zona** (SQL, Storage, etc.).
- **No todas** las regiones son **compatibles**.
- La **región** admitida **tiene tres o más zonas**.
- Una **zona de disponibilidad** es **uno o más centros de datos**(No necesariamente debe ser uno).

### **Conjunto de disponibilidad**
- **Característica de un DataCenter**.
- Ubicaciones separadas, pero dentro del mismo datacenter.  
- Garantizan que máquinas virtuales o servicios IaaS implementados en Azure se distribuyan entre varios nodos de hardware aislados en un clúster.

<img src="Images/Availability-zone.png" alt="Availability Zone" width="800"/> 

### **Pares de regiones**
- Cada **región** está **emparejada** con otra región, lo que la convierte en un par de regiones.
- Los **pares de regiones son estáticos** y no se pueden elegir.
- Cada par reside dentro de la **misma geografía**.`La excepción es Brazil South`.
- **Aislamiento físico** con al menos 300 millas de distancia (cuando sea posible).
- Algunos servicios tienen **replicación proporcionada por la plataforma**.
- **Actualizaciones planificadas** en los pares.
- **Residencia de datos** mantenida para recuperación ante desastres.
Algunos ejemplos de regiones pares: 

Región Par A|Región Par B
---|---
East US|West US
UK West|UK South
North Europe|West Europe

<img src="Images/Regions-pairs.png" alt="Region Pairs" width="800"/> 

### **Geografías**
- **Mercado discreto**
- Normalmente **contiene dos o más regiones**.
- Garantiza que se cumplan los requisitos de **residencia**, **soberanía**, **resiliencia** y **cumplimiento** de los **datos**.
- **Tolerante a fallas** para proteger de fallas en toda la región.
- Dividido en áreas : **Américas**, **Europa**, **Asia Pacífico**, **Oriente Medio** y **África**.
- Cada **región pertenece solo a una Geografía**.

## **Resources, Resources Groups y Resource Manager**
### **Resource**
- Objeto **utilizado para administrar servicios** en Azure.
- Representa el **ciclo de vida del servicio** (**o de otra forma: los servicios comprados**).
- Guardado como **definición JSON**.

<img src="Images/Resources.png" width="500"/>

### **Resources Groups (Grupo de recursos)**
- **Agrupación** de recursos.
- Contiene recursos **lógicamente relacionados**.
- Normalmente se organiza por
  - **Tipo**
  - **Ciclo de vida** (aplicación, entorno)
  - **Departamento**
  - **Facturación**,
  - **Ubicación** o
  - **combinación de esos**

<img src="Images/Resource-group.png" width="400"/>

### **Resource Manager (Administrador de recursos)**
- **Capa de gestión** para todos los recursos y grupos de recursos
- Lenguaje **unificado**.
- **Controla el acceso** y **los recursos**.

<img src="Images/Resource-manager.png" width="600"/>

### **Información adicional**
- Cada **recurso** debe estar en **uno y solo un grupo de recursos**.
- Los **grupos de recursos tienen su propia ubicación** asignada.
- Los recursos de los grupos de recursos pueden **residir en ubicaciones diferentes**.
- Los recursos **se pueden mover** entre los grupos de recursos.
- Los **grupos de recursos no se pueden anidar**.
- Organícese en función de las necesidades de su organización, pero tenga en cuenta
  - Facturación
  - Seguridad y gestión de acceso
  - Ciclo de vida de la aplicación

## **Servicios de cómputo (Azure Compute)**
Es un servicio de informática a petición para ejecutar aplicaciones basadas en la nube. 

### **Virtualización**
- Emulación de máquinas físicas
- Configuración de hardware virtual diferente por máquina/aplicación
- Diferentes sistemas operativos por máquina/aplicación
- Separación total de ambientes
  - sistemas de archivos,
  - servicios,
  - puertos,
  - middleware,
  - configuración

<img src="Images/Virtualization.png" width="800"/>

### **Azure Virtual Machine (Máquina virtual)**
- Infraestructura como servicio (IaaS).
- Control total sobre el sistema operativo y el software.
- Soporta mercado e imágenes personalizadas.
- El más adecuado para
  - Software personalizado que requiere una configuración de sistema personalizada
  - Escenarios de elevación y cambio
- Puede ejecutar cualquier aplicación/escenario
  - aplicaciones web y servicios web,
  - bases de datos,
  - aplicaciones de escritorio,
  - jumpboxes,
  - gateways, etc.

**NOTA:** Deshabilitar una máquina virtual significa que se deshabilita la CPU y la red pero los discos son persistentes.  
**NOTA 2:** Si despliegas dos máquinas virtuales del mismo tamaño, ambas no generarán siempre el mismo coste mensual.  
**NOTA 3:** Puedes ver las notificaciones de fallos de servicio que pueden afectar a la disponibilidad de la VM desde el servicio Azure Virtual Machines.  

<img src="Images/Azure-virtual-machines.png" width="800"/>

### **Azure Virtual Machine Scale Sets (Conjuntos de escalado de máquinas virtuales)**
- Infraestructura como servicio (IaaS).
- Conjunto de máquinas virtuales idénticas.
- Funciones de escalado automático integradas, manual o una combinación de ambos.
- Diseñado para cargas de trabajo manuales y de escalado automático, como servicios web, procesamiento por lotes,macrodatos, etc.

<img src="Images/Azure-virtual-machine-scale-sets.png" width="800"/>

### **Azure Batch**
**Azure Batch** permite trabajo por lotes paralelos a gran escala y de informática de alto rendimiento (HPC) con la capacidad de escalar a decenas, cientos o miles de máquinas virtuales.  
Cuando esté listo para ejecutar un trabajo, Batch:  
- Iniciará un grupo de máquinas virtuales de proceso de forma automática.
- Instalará aplicaciones y datos de almacenamiento provisional.
- Ejecutará trabajos con tantas tareas como tenga.
- Identificará errores.
- Reordenará la cola de trabajo.
- Reducirá verticalmente el grupo a medida que se complete el trabajo.

Puede haber situaciones en las que se necesite potencia informática sin procesar o potencia de cálculo a nivel de superequipo. Azure proporciona estas capacidades.

### **Azure Virtual Desktop**
**Azure Virtual Desktop** es un servicio de virtualización de escritorios y aplicaciones que se ejecuta en la nube.  
Permite que los usuarios usen una versión hospedada en la nube de Windows desde cualquier ubicación. Azure Virtual Desktop funciona en dispositivos como Windows, Mac, iOS, Android y Linux. Funciona con aplicaciones que se pueden usar para acceder a aplicaciones y escritorios remotos. También puede usar la mayoría de los exploradores modernos para acceder a experiencias hospedadas en Azure Virtual Desktop.

- Administración simplificada
- Administración del rendimiento
- Implementación de sesión múltiple de Windows 10

### **Contenedores**
- Usar el sistema operativo del host
- Emular el sistema operativo (las máquinas virtuales emulan el hardware)
- Ligero (sin O/S)
  - Esfuerzo de desarrollo
  - Mantenimiento
  - Requisitos de computación y almacenamiento
- Responda más rápido a los cambios de demanda
- Diseñado para casi cualquier escenario

<img src="Images/Containers.png" width="800"/>

### **Azure Containers Instance (Instancias de contenedores)**
- La forma más sencilla y rápida de ejecutar un contenedor en Azure
- Plataforma como servicio (PaaS)
- Contenedores sin servidor
- Diseñado para
  - Servicios/aplicaciones web pequeñas y sencillas
  - Trabajos en segundo plano
  - Guiones programados

<img src="Images/Azure-container-instances.png" width="800"/>

### **Azure Kubernetes Services (AKS)**
- Plataforma de orquestación de contenedores de código abierto
- Plataforma como servicio (PaaS)
- Altamente escalable y personalizable
- Diseñado para implementaciones de contenedores a gran escala (¡cualquier cosa realmente!)

<img src="Images/Azure-kubernetes-service.png" width="800"/>

### **Azure App Service**
- Diseñado como servicio de aplicación web de nivel empresarial.
- Compilar, implementar y escalar de forma rápida aplicaciones de API, móviles y web.
- Plataforma como servicio (PaaS).
- Admite múltiples lenguajes de programación y contenedores.
- Satisface exigentes requisitos de rendimiento, escalabilidad, seguridad y cumplimiento.
- Controla la mayoría de decisiones sobre la infraestructura permitiendo
  - puntos de conexión se pueden proteger
  - sitios pueden escalar rápidamente para controlar cargas de tráfico elevado  
Los costos de **Azure App Service** se pagan por los recursos que usa mientras procesa las solicitudes según el plan de **App Service** que elija. El plan de **App Service** determina la cantidad de hardware y si es dedicado o compartido.

<img src="Images/App-service.png" width="800"/>

#### **Tipos de servicios de aplicaciones**
Con **App Service** se pueden hospedar los siguientes  estilos de servicio de aplicación más comunes:
- **Aplicaciones web** - Compatibilidad para hospedar mediante ASP.NET, ASP.NET Core, Java, Ruby, Node.js, PHP o Python. Puede elegir Windows o Linux como S.O.
- **Aplicaciones de API** - Compilar API Web´ basadas en REST. Compatibilidad con Swagger y posibilidad de empaquetar y publicar la API en **Azure Marketplace**. Se pueden consumir desde cualquier cliente basado en HTTP o HTTPS.
- **Trabajos web** - Usa característica **WebJobs** para ejecutar un programa(.exe, Java, PHP, Python o Node.js) o un script(.cmd, .bat, PowerShell o Bash) y suelen usarse para ejecutar tareas en segundo plano como parte de la lógica de aplicación
- **Aplicaciones móviles** - Característica **Mobile Apps** de **App Service** para compilar un back-end para apps iOS y Android. Se pueden agregar conexiones y compatibilidad con SDK (No se explicarán aquí, ya que escapan de fundamentals) 

### **Azure Functions**
- Plataforma como servicio (PaaS)
- Serverless
- Dos modelos de alojamiento/precio
  - Consumo-plan basado
  - plan dedicado
- Diseñado para micro/nanoservicios
- Las funciones pueden tener ser **sin estado**: se comportan como si se reiniciaran cada que se ejecutan; Y  **con estado**(Durable Functions) a los cuales se les pasa un contexto para realizar seguimiento.

<img src="Images/Functions-apps.png" width="800"/>

### **Azure Logic Apps**
Son similares a **Azure Functions**. Permiten desencadenar lógica basada en un evento ejecutando *flujos de trabajo* diseñados para automatizar escenarios empresariales. 
- Los *flujos de trabajo* comienzan con un desencadenador
- Cada desencadenador puede ser especificado con la frecuencia que ejecutará sus cargas de trabajo. 
- Los *flujos de trabajo* se crean mediante un diseño visual en **Azure Portal** o en **Visual Studio**.
- Los *flujos de trabajo* se conservan como un archivo JSON

### **Resumen**
- Máquinas virtuales (IaaS) - software personalizado, requisitos personalizados, muy especializado, alto grado de control
- Conjuntos de escalado de máquinas virtuales (IaaS) - cargas de trabajo de escalado automático para máquinas virtuales
- Instancias de contenedor (PaaS) - alojamiento de contenedor simple, fácil de comenzar
- Servicio Kubernetes (PaaS) - Plataforma de alojamiento de contenedores * altamente escalable y personalizable
- Servicios de aplicaciones (PaaS) - aplicaciones web, muchas funciones de alojamiento web empresarial *, fácil de comenzar
- Funciones (PaaS) (Función como servicio) (Serverless) - micro/nanoservicios, excelente precio basado en el consumo, fácil de comenzar

<img src="Images/Summary.png" width="800"/>

## **Servicios de red**


### **Azure Networking (Redes Azure)**
Categoria de servicio que permite a los clientes conectar sus recursos locales y en la nube, pero también ayuda con la protección y monitoreo de la red para esos servicios, así como ayudar a los cliente en la entrega de aplicaciones.
- Conecte la nube y on-premises
- Funcionalidad de red on-premise

Otra forma de ver es: Permiten a los recursos de Azure, como las **máquinas virtuales, las aplicaciones web y las bases de datos, comunicarse entre sí**, con los usuarios de Internet y con los equipos cliente en el entorno local. Se puede pensar en una red de Azure como en un conjunto de recursos que se vincula a otros recursos de Azure.

Proporcionan las importantes funcionalidades:
- **Aislamiento y segmentación** - Crear varias redes virtuales aisladas y dividir el espacio de direcciones IP en subredes y asignar parte del espacio a cada subred con nombre. En la resolución de nombres, puede usar el **servicio de reoslución de nombres** integrado en Azure o configurar para que la red virtual use un servidor DNS interno o externo. 
- **Comunicación con Internet** - Una VM en Azure se puede conectar de forma predeterminada. Puede habilitar comunicaciones entrantes desde Internet si define una dirección IP pública o un equilibro de carga público.
- **Comunicación entre recursos de Azure** - De dos maneras: 
  - **Redes virtuales**
  - **Puntos de conexión de servicio** - Puede usar estos puntos para conectarse a otros tipos de recursos de Azure, como cuentas de almacenamiento y BD´s. Permite vincular varios recursos de Azure con las redes virtuales.
- **Comunicación con recursos locales (on-premises)** - Las redes virtuales de Azure permiten vincular entre sí a los recursos locales con los que esten dentro de la subscripción de Azure, de 3 formas posibles: 
  - **Redes privadas virtuales de punto a sitio** - Enfoque habitual, consiste en establecer la conexión con la red corporativa(en este caso la red virtual Azure) desde un equipo ajeno a la organización.
  - **Redes virtuales privadas de sitio a sitio** - Vincula un dispositivo o puerta de enlace de VPN local con la puerta de enlace de VPN de Azure en una red virtual, la conexión se cifra y viaja a través de Internet hacia el otro extremo.
  - **Azure ExpressRoute** - Para entornos con necesidad de mayor ancho de banda y seguridad. Proporciona una conectividad privada decicada a Azure que no viaja a través de Internet.
- **Enrutamiento del tráfico de red** - Azure enruta predeterminadamente el tráfico entre subredes de todas las redes virtuales conectadas,pero puede controlar el enrutamiento de dos formas:
  - **Tablas de rutas** - Permite definir reglas para dirigir el tráfico que controlan cómo se enrutan los paquetes entre las subredes.
  - **Protocolo de puerta de enlace de borde** - (BGP) funciona con puertas enlace de VPN de Azure o con ExpressRoute para propagar las rutas BGP locales a las redes virtuales de Azure.
- **Filtrado del tráfico de red**
  - **Grupos de seguridad de red** -  Es un recurso que puede contener varias reglas de seguridad de entrada y salida. Una regla se usa para definir si permitir o bloquear el tráfico en función de factores como protocolo,puerto,direcciónes IP de destino y origen.
  - **Aplicaciones virtuales de red** - Es una máquina virtual especializada que se puede comparar con un dispositivo de red protegido y ejerce una fución de red determinada, como ejecutar un firewall o realizar la optimización de la red de área extensa (WAN).
- **Conexión de redes virtuales** - Puede vincular redes virtuales entre sí mediante *emparejamiento de red virtual*. Estas redes virtuales pueden estar en regiones distintas.
- **Enrutamiento definido por el usuario** - (UDR). Se trata de enrutamiento definido por el usuario, permite que los administradores de red controlen las tablas de enrutamiento entre las subredes de una red virtual,así como entre redes virtuales.

### **Azure Virtual Network (Red virtual)**
Las redes virtuales permiten a sus clientes crear, administrar, monitorear y proteger la conectividad entre los recursos de Azure, pero también entre los recursos de Azure y los suyos on-premises 
- Emulación de infraestructura de red física
- Componentes de red aislados lógicamente
- Segmentado en una o más subredes
- Las subredes son secciones discretas y no se pueden anidar
- Habilita la comunicación de los recursos entre sí, Internet y en las instalaciones
- Alcance a una sola región
- **El emparejamiento de VNet permite la comunicación entre regiones**
- Aislamiento, Segmentación, Comunicación, Filtrado y Enrutamiento entre recursos

<img src="Images/Virtual-network.png" width="600"/>

### **Azure VPN Gateway**
- Tipo específico de puerta de enlace de red virtual para el tráfico on-premise a Azure a través de la Internet pública de forma cifrada. También se puede usar para unir dos redes virtuales de Azure (no es muy común).
- Las instancias de **Azure VPN Gateway** se implementan en **Azure Virtual Network** y habilitan: 
  - Conectar los centros de datos locales a redes virtuales a través de una conexión de **sitio a sitio**.
  - Conectar los dispositivos individuales a redes virtuales a través de una conexión de **punto a sitio**.
  - Conectar las redes virtuales a otras redes virtuales a través de una conexión **entre redes**.
- Solo se puede tener una instancia de **Azure VPN Gateway** en cada red virtual, pero se puede usar una puerta de enlace para conectarse a varias ubicaciones.
- **Azure VPN Gateway** debe conocer el tipo de red privada virtual : *basada en directivas* o *basada en rutas*. 
- En **Azure**, ambos tipos de puertas de enlace VPN resultantes del tipo de red privada virtual, usan una clave previamente compartida como único método de autenticación.
- Usan el intercambio de claves por red (**IKE**) en versiones 1 o 2 y protocolo de seguridad de internet (**IPsec**)
  - IKE se usa para establecer asociación de seguridad entre dos puntos de conexión.
  - Después se pasa al conjunto de IPsec que cifra y descrifa los paquetes de datos encapsulados en el túnel VPN.

#### **Redes privadas virtuales basadas en directivas**
Las instancias de **VPN Gateway basadas en directivas** especifican estáticamente la dirección IP de los paquetes que se deben cifrar a través de cada túnel evaluando los paquetes de datos en función de los conjuntos de direcciones IP para elegir el túnel a tavés del cual se va a enviar el paquete.
  - Compatibilidad solo con IKEv1
  - Escenarios específicos como compatibilidad con dispositivos de red privada virtual locales heredados
#### **Redes privadas virtuales basadas en rutas**
Las instancias de **VPN Gateway basadas en rutas** permiten que los túneles IPSec se modelen como una interfaz de red o de túnel virtual. El enrutamiento IP decide cuál de estas interfaces de túnel se va a usar al enviar cada paquete y son el método preferido para conectar dispositivos locales pues son resistentes a los cambios de la topología como la creación de subredes.
  - Compatibilidad con IKEv2
  - Uso de selectores de tráfico universales
  - Se puede usar *protocolos de enrutamiento dinámico*
Estas instancias permiten: 
  - Conexiones entre redes virtuales
  - Conexiones de punto a sitio
  - Conexiones de varios sitios
  - Coexistencia con una puerta de enlace de Azure ExpressRoute

#### **Tamaños de las instancias de VPN Gateway**

SKU	| Túneles de sitio a sitio o de red a red	| Pruebas comparativas de rendimiento agregado	| Compatibilidad con el Protocolo de puerta de enlace de borde
---|---|---|---
Básico* | Máximo: 10	| 100 Mbps | No compatible
VpnGw1/Az |	Máximo: 30 | 650 Mbps | Compatible
VpnGw2/Az |	Máximo: 30 | 1 Gbps | Compatible
VpnGw3/Az |	Máximo: 30 | 1,25 Gbps | Compatible.

**Básico*** : Solo debe usarse en cargas de trabajo de desarrollo/pruebas.Además, no se puede migrar a SKU superiores sin quitar el gateway y volver a implementarla.

<img src="Images/VPN-gateway.png" width="800"/>

Si se requiere más detalles sobre la implementación de instancias de VPN Gateway, visite https://docs.microsoft.com/es-es/learn/modules/azure-networking-fundamentals/azure-vpn-gateway-fundamentals

### **Azure ExpressRoute**
Permite ampliar las redes locales a la nube de Microsoft mediante una conexión privada con la ayuda de un proveedor de conectividad.
- No pasan por la red pública de Internet
- Conectividad de nivel 3 entre su red local y Microsfot Cloud a través de un proveedor de conectividad
- Enrutamiento dinámico entre la red y Microsoft a través de BGP
- Redudancia integrada en todas las ubicaciones de configuración entre pares
- Admite 3 modelos de conectividad
  - Ubicación de CloudExchange
  - Conexión Ethernet de punto a punto
  - Conexión universal
- Rendimiento de red coherente
- Incluso si tiene conexión ExpressRoute, las consultas DNS, comprobación de lista de revocación de certificados se hacen por la internet.

Si se requiere más detalles,visite https://docs.microsoft.com/es-es/learn/modules/azure-networking-fundamentals/express-route-fundamentals

### **Azure Load Balancer (Equilibrador de carga)**
**Balanceo**: Distribución del tráfico entre múltiples recursos
- Iguala la distribución del tráfico
- Admite escenarios tanto entrantes como salientes
- Escenarios de alta disponibilidad
- Aplicaciones TCP (protocolo de control de transmisión) y UDP (protocolo de datagramas de usuario)
- Tráfico Interno y Externo
- Reenvío de puertos
- Alta escala con hasta millones de flujos
<div>
<img src="Images/Load-balancer.png" width="800"/>
<img src="Images/Load-balancer-2.png" width="800"/>
</div>

### **Azure Application Gateway**
- Equilibrador de carga de tráfico web (HTTP)
- Firewall de aplicaciones web
- Redirección del tráfico entrante
- Afinidad de sesión - Asegurarse que los usuarios siempre se dirijan a los mismos servidores
- Enrutamiento de URL
- Terminación SSL - Permite a los clientes descifrar el tráfico en **Application Gateway** y enviar una versión sin cifrar a los servicios de back-end para reducir la potencia de procesamiento requerida para descifrar cada solicitud individual.

<div>
<img src="Images/Application-gateway.png" width="500"/>
<img src="Images/Application-gateway-2.png" width="500"/>
<img src="Images/Application-gateway-3.png" width="500"/>
</div>

### **Azure Content Delivery Network (Red de entrega de contenidos)**
Distribuye y almacena en caché el contenido en múltiples bucaciones emergentes en todo el mundo para descargar nuestros servicios front-end pero también reduce la latencia de entrega de recursos a nuestros usuarios.
- Definir contenido
- Minimizar la latencia
- POP (puntos de presencia) con muchas ubicaciones

<div>
<img src="Images/Content-delivery-network.png" width="800"/>
<img src="Images/Content-delivery-network-2.png" width="800"/>
</div>

## **Servicios de almacenamiento**
### **Tipos de datos**
- **Estructurado**: datos que se pueden representar mediante tablas con un esquema muy estricto. Cada fila debe seguir un esquema definido. Algunas tablas tienen relaciones definidas entre ellas. Normalmente se utiliza en bases de datos relacionales.  
- **Semiestructurado**: datos que se pueden representar mediante tablas pero sin un esquema estricto definido.  
Las filas solo deben tener un identificador de clave único.  
- **Sin estructura**: cualquier archivo en cualquier formato. Como archivos binarios, archivos de aplicaciones, imágenes, películas, etc.  

<img src="Images/Types-of-data.png" width="800"/>

### **Storage Account (Cuenta de almacenamiento)**
- Grupo de servicios que incluyen
  - Almacenamiento de blobs,
  - Almacenamiento en cola,
  - Almacenamiento de tablas y
  - aAlmacenamiento de archivos
- Se utiliza para almacenar
  - Archivos,
  - Mensajes, y
  - Datos semiestructurados
- Altamente escalable (hasta petabytes de datos)
- Muy duradero (99,999999999 % - 11 nueves, hasta 16 nueves)
- Más barato por GB de almacenamiento

<img src="Images/Storage-account.png" width="400"/>

### **Blob Storage**
- BLOB – objeto grande binario – archivo
- Diseñado para el almacenamiento de archivos de cualquier tipo
- Tres niveles de almacenamiento
  - Hot: datos de acceso frecuente
  - Cool: datos a los que se accede con poca frecuencia (menor disponibilidad, alta durabilidad)
  - Archive: rara vez (si es que alguna vez) se accede a los datos

<img src="Images/Blob-storage.png" width="600"/>

### **Queue Storage**
- Almacenamiento de pequeños datos (mensajes)
- Diseñado para procesamiento asíncrono escalable

<div>
<img src="Images/Queue-storage.png" width="230"/>
<img src="Images/Queue-storage-2.png" width="200"/>
<img src="Images/Queue-storage-3.png" width="300"/>
</div>

### **Table Storage**
- Almacenamiento para datos semiestructurados (NoSQL)
  - Sin necesidad de uniones foráneas, claves foráneas, relaciones o esquemas estrictos
  - Diseñado para un acceso rápido
- Muchas interfaces de programación y SDK

<img src="Images/Table-storage.png" width="700"/>

### **File Storage**
- Almacenamiento para archivos a los que se accede a través de protocolos de unidades compartidas
- Diseñado para ampliar los recursos compartidos de archivos en las instalaciones o implementar escenarios de elevación y cambio

<img src="Images/File-storage.png" width="700"/>

### **Disk Storage**
- Emulación de disco en la nube
- Almacenamiento persistente para máquinas virtuales
- Diferente
  - tamaños,
  - tipos (SSD, HDD)
  - niveles de rendimiento
- El disco puede ser administrado o no administrado  
**NOTA**: **Disk Storage** también es un subservicio de la cuenta de **Azure Storage**. esto significa que tanto los discos administrados como los no administrados son parte de él. incluso si el disco administrado se muestra como un recurso separado,
debajo sigue siendo el mismo servicio.

<img src="Images/Disk-storage.png" width="200"/>

## **Servicios de bases de datos**
### **Tipos de datos en las BD**
Se explicó anteriormente. Revisar [Tipos de datos](#tipos-de-datos)
### **Azure Cosmos DB**
- Servicio de base de datos NoSQL (datos semiestructurados) distribuido globalmente
- Sin esquema (Se abstrae y se consulta a través de las API´s)
- Múltiples API (SQL, MongoDB, Cassandra, Gremlin, Table Storage)
- Diseñado para
  - Aplicaciones de alta capacidad de respuesta (en tiempo real) con respuestas de latencia muy baja <10 ms
  - Aplicaciones multirregionales

<div>
<img src="Images/Cosmos-db.png" width="600"/>
<img src="Images/Cosmos-db-2.png" width="600"/>
</div>

### **Azure SQL Database**
- Servicio de **base de datos relacional** en la nube (PaaS) (DBaaS - Database as a Service)
- **Servicio de datos estructurados** definido mediante esquema y relaciones
- **Capacidades de consulta enriquecidas** (SQL)
- Base de datos de **alto rendimiento**, fiable, totalmente gestionada y segura para la creación de aplicaciones

<div>
<img src="Images/SQL-database.png" width="600"/>
<img src="Images/SQL-server.png" width="600"/>
</div>

### **Azure SQL product family**
- Azure **SQL Database**: base de datos relacional confiable basada en SQL Server
- Azure **Database for MySQL**: versión de Azure SQL para el motor de base de datos MySQL
- Azure **Database for PostgreSQL**: versión de Azure SQL para el motor de base de datos de PostgreSQL
- **Instancia administrada de Azure SQL**: SQL Server completo administrado por un proveedor de la nube
- Azure **SQL en VM**: SQL Server completo en IaaS
- Azure **SQL Data Warehouse (Ahora Azure Synapse Analytics)**: versión de procesamiento paralelo masivo (MPP) de SQL Server que permite consultar datos mediante recursos sin servidor o aprovisionados a escala. Experiencia unificada para ingerir, preparar, administrar y servir los datos.

<img src="Images/Azure-sql.png" width="600"/>

## **Azure Marketplace**
- Facilita la conexión entre usuarios y partners de Microsoft, proveedores de software independientes y neuvas empresas que ofrecen sus soluciones y servicios optimizados para ejecutarse en Azure.
- Piense en ello como una "Tienda Azure" donde compra servicios y soluciones para la plataforma Azure
- Cada producto es una plantilla que contiene **uno o varios servicios(cuya instancia es un recurso)**
- Los productos son entregados por **proveedores propios y externos**.
- Las soluciones pueden aprovechar todas las categorías de servicios como IaaS, PaaS y SaaS

<img src="Images/Marketplace.png" width="600"/>

## **Servicios IoT**
Internet de las cosas (**IoT**) es una red de dispositivos conectados a Internet (**dispositivos IoT**) integrados en objetos cotidianos que permiten enviar y recibir datos, como **configuraciones** y **telemetría**.  
<img src="Images/Iot.png" width="600"/>

### **Azure IoT Hub**
Azure clasifica a su servicio como uno que permite *ordernar y controlar*.

- Servicio gestionado para comunicación bidireccional
- Plataforma como servicio (PaaS)
- Altamente seguro, escalable y confiable
- Se integra con una gran cantidad de servicios de Azure
- SDK programables para lenguajes populares (C, C#, Java, Python, Node.js)
- Múltiples protocolos (HTTPS, AMQP, MQTT)  
- Admite varios patrones de mensajería : telemetría de dispositivo a la nube, carga de archivos desde dispositivos y métodos de solicitud-respuesta.

**Nota**: Una vez que **Azure IoT Hub** recibe un mensaje de un dispositivo, puede enrutarlo a otro servicio de Azure.

<img src="Images/Iot-hub.png" width="600"/>

### **Azure IoT Central**
Se basa en **Azure IoT Hub** y proporciona un panel que permite a las empresas administrar dispositivos de IoT de forma individual y en conjunto, ver informes y configurar notificaciones de error mediante una GUI.

- Plataforma de aplicaciones IoT: software como servicio (SaaS)
- Plantillas de aplicaciones específicas de la industria personalizables
- No se requieren conocimientos técnicos profundos
- Servicio de conexión, gestión y **monitorización** de dispositivos IoT
- Altamente seguro, escalable y confiable
- Construido sobre el servicio IoT Hub y más de 30 servicios más  
- Puede enviar actualizaciones de firmware o software a los dispositivos.
- Uso de plantillas de dispositivo que permite conectar un dispositivo sin programación(Desarrolladores aún deben crear código que se ejecute, pero este solo debería coincidir con la especificación de la plantilla de dispositivo).

<img src="Images/Iot-central.png" width="600"/>

### **Azure Sphere**
- Soluciones seguras de IoT de extremo a extremo
  - Chips certificados por Azure Sphere (unidades de microcontrolador - MCU) - Procesan el S.O. y las señales de los sensores conectados
  - Sistema operativo Azure Sphere basado en Linux - Controla la comunicación con el servicio de seguridad y ejecuta el software del proveedor.
  - Comunicación de dispositivo a nube de confianza de Azure Security Service - Es el servicio de seguridad (AS3). Funciona autenticandose mediante certificados y se asegura que el dispositivo no está en peligro, además una vez se identifica inserta las actualizaciones de software del S.O. o del cliente(y aprobadas) a la vez que pueden recibir mensajes o enviar de forma remota.
 
<img src="Images/Sphere.png" width="600"/>

## **Servicios Big Data & Analytics**
Big Data es un campo de la tecnología que ayuda con la extracción, el procesamiento y el análisis de información que es demasiado grande o compleja para ser tratada por el software tradicional.  
**La regla de las tres V**
Los grandes datos suelen tener una de las siguientes características  
- **Velocidad**: qué tan rápido ingresan los datos o qué tan rápido los estamos procesando
  - Batch
  - Periódico
  - Casi en tiempo real
  - Tiempo real
- **Volumen**: cuántos datos estamos procesando
  - Megabytes
  - Gigabyte
  - Terabytes
  - Petabytes
- **Variedad**: cuán estructurados/complejos son los datos
  - Tables
  - bases de datos
  - Foto, Audio
  - Vídeo, Redes Sociales

### **Azure Synapse Analytics**
Plataforma de análisis de big data con una experiencia de espacio de trabajo unificado que admite la transformación de datos de extremo a extremo con el poder de SQL y Spark.

Azure Synapse Analytics es una evolución de un servicio SQL Datawarehouse que es una versión de procesamiento paralelo masivo de SQL Server. En una iteración reciente, Azure Synapse también brindó la capacidad de ejecutar consultas y scripts mediante Apache Spark y al incluir **Data Factory** como un componente integrado llamado **Synapse Pipelines**, ahora se considera una solución de extremo a extremo para grandes cargas de trabajo de datos.

- Plataforma de análisis de big data (PaaS)
- Múltiples componentes
  - Spark
  - Synapse SQL
    - Grupos de SQL (dedicados: pago por rendimiento aprovisionado)
    - SQL bajo demanda (ad-hoc: pago por TB procesados)
  - Synapse Pipelines (Data Factory - ETL)
  - Studio (Engloba todos los componentes como una experiencia unificada)

<img src="Images/Synapse-analytics.png" width="600"/>

### **Azure HDInsight**
- Plataforma flexible multipropósito de big data (PaaS)
- Múltiples tecnologías compatibles de código abierto(Hadoop, Spark, Kafka, HBase, Hive, Storm, Machine Learning)
- Permite una amplia gama de escenarios como ETL, almacenamiento de datos, aprendizaje automático e IoT

<img src="Images/HDInsight.png" width="600"/>

### **Azure Databricks**
- Plataforma de colaboración de big data (PaaS)
- Espacio de trabajo unificado para portátiles, clústeres, datos, administración de acceso y colaboración
- Basado en Apache Spark
- Se integra muy bien con los servicios de datos comunes de Azure
- Dirigido generalmente a soluciones de inteligencia artificial
- Admite Python, Scala, R, Java y SQL
- Admite marcos y biliotecas de ciencias de datos : TensorFlow, PyTorch, Scikit-learn

<img src="Images/Databricks.png" width="600"/>

### **Azure Data Lake Analytics**
Servicio de trabajos de análisis a petición que simplifica los macrodatos. No requiere administración de servidor, solo escribir consultas para transformar los datos y extraer ideas valiosas.

## **Servicios de IA**
**¿Qué es Artificial Intelligence?**  
La inteligencia artificial (IA) es la simulación de la inteligencia y las capacidades humanas mediante un software informático.  
**¿Qué es Machine Learning?**  
El aprendizaje automático es una subcategoría de la IA en la que se "enseña" un software de computadora a sacar conclusiones y hacer predicciones a partir de los datos. 
**¿Qué es Deep Learning?** 
Se modela en la red neuronal similar al de la mente humana, lo que le permite descubrir, aprender y crecer a través de la experiencia.
### **Azure Machine Learning**
Plataforma para realizar predicciones. Consta de herramientas que permiten conectarse a los datos, probar modelos, implementarlos y usarlo en tiempo real a través de un punto de conexión de API web.

- Plataforma basada en la nube para crear, administrar y publicar modelos de aprendizaje automático
- Plataforma como servicio (PaaS)
- Machine Learning Workspace: recurso de nivel superior (Top-Level)
- Machine Learning Studio: portal web para desarrollo extremo a extremo
- Características
  - Cuadernos: usando Python y R
  - ML automatizado: ejecute múltiples combinaciones de algoritmos/parámetros, elija el mejor modelo
  - Diseñador: interfaz gráfica para el desarrollo sin código
  - Datos y computación: administración de recursos de almacenamiento y computación
  - Pipelines: orqueste tareas de capacitación, implementación y administración de modelos

Cuando los científicos de datos necesiten un control completo sobre el diseño y entrenamiento de un algoritmo con sus propios datos.

<img src="Images/Machine-learning.png" width="600"/>

### **Azure Cognitive Service**
Proporciona modelos de aprendizaje automático creados y entrenados previamente. 
- Soluciona problemas generales : análisis de texto, de imágenes
- Poco conocimiento técnico para usar los servicios
- Se accede a estos servicios mediante API 
- Categorías: 
  - Servicios de lenguaje - Evaluar opiniones,reconocer que quieren usuarios.
  - Servicios de voz - Voz a texto y texto a voz, traducciones y reconocimiento y verificación del hablante.
  - Servicios de visión - Reconocimiento e identificación en imágenes,vídeos y otro contenido visual. 
  - Servicios de decisión - Recomendaciones personalizadas mejorables automáticamente con el uso.

### **Azure Bot Service**
Junto a **Bot Framework** son plataformas para crear agentes virtuales que comprenden y responden a preguntas como un ser humano. Este bot creado usa otros servicios de Azure como **Azure Cognitive Services** para comprender lo que le solicitan los humanos.

## **Servicios serverless computing**
La computación sin servidor es un entorno de ejecución alojado en la nube que permite a los clientes ejecutar sus aplicaciones en la nube mientras abstraen por completo la infraestructura subyacente.  
### **Azure Functions**
- Plataforma de codificación sin servidor (Funciones como servicio, FaaS)
- Diseñado para arquitecturas de nanoservicios y aplicaciones basadas en eventos
- Escala hacia arriba y hacia abajo muy rápidamente
- Altamente escalable
- Admite lenguajes y marcos populares (.NET y .NET Core, Java, Node.js, Python, PowerShell, etc.)

<img src="Images/Azure-functions-apps.png" width="600"/>

### **Azure Logic Apps**
- Servicio de integración empresarial sin servidor (PaaS)
- Más de 200 conectores para servicios populares
- Diseñado para la orquestación de
  - Procesos de negocios,
  - flujos de trabajo de integración para aplicaciones, datos, sistemas y servicios
  - orientado al diseñador (declarativo)
- Solución sin código
- Mantiene un estado
- Supervisado desde Azure Protal, Log Analytics
- Administrado desde Azure Portal, API REST, PowerShell, Visual Studio

<img src="Images/Azure-logics-apps.png" width="600"/>

### **Azure Event Grid**
- Servicio de enrutamiento de eventos sin servidor completamente administrado
- Utiliza el modelo de publicación-suscripción
- Diseñado para aplicaciones basadas en eventos y casi en tiempo real
- Admite docenas de eventos integrados de los servicios de Azure más comunes

<img src="Images/Azure-event-grid.png" width="600"/>

## **Soluciones DevOps**
**DevOps** es un conjunto de prácticas que combinan tanto el desarrollo (Dev) como las operaciones (Ops).  
DevOps tiene como objetivo **acortar el ciclo de vida del desarrollo** al proporcionar capacidades de **integración y entrega continuas** (CI/CD) al tiempo que garantiza una **alta calidad** de los entregables.

### **Azure DevOps Services**
- Software como servicio (SaaS)
- Colección de servicios para construir soluciones usando prácticas DevOps
- Servicios incluidos
  - Azure Boards - Tableros: trabajo de seguimiento,Paneles Kanban, Informes, Ideas de seguimiento y trabajo.
  - Azure Pipelines: creación de flujos de trabajo de CI/CD (creación, prueba e implementación de aplicaciones)
  - Azure Repos: colaboración de código y control de versiones con Git
  - Azure Test Plans: pruebas manuales y exploratorias
  - Azure Artifacts: gestione los entregables del proyecto
- Ampliable con Marketplace: más de 1000 aplicaciones disponibles
- Evolucionado de TFS (Team Foundation Server), a través de VSTS (Visual Studio Team Services)

<img src="Images/Azure-devops.png" width="800"/>

### **Azure DevTest Labs**
- Servicio de creación de entornos sandbox para desarrolladores/testers (PaaS)
- Configuración rápida de máquinas virtuales autogestionadas
- Plantillas preconfiguradas para máquinas virtuales
- Muchos artefactos adicionales (herramientas, aplicaciones, acciones personalizadas)
- Políticas de laboratorio (cuotas, tamaños, apagado automático)
- Comparta y automatice laboratorios a través de imágenes personalizadas
- Complementos/API/herramientas prefabricados para la automatización de canalización de CI/CD

<img src="Images/Azure-devtest-labs.png" width="800"/>

## **Azure Tools**
### **Azure Portal**
- Interfaz pública basada en web para la gestión de la plataforma Azure.
- Diseñado para el autoservicio.
- Personalizable.
- Tareas simples.
- Diseñado para proporcionar resiliencia y disponibilidad continua al estar presente en todos los centros de datos de Azure.

<img src="Images/Azure-portal.png" width="800"/>

### **Azure PowerShell**
- PowerShell y módulo
- Diseñado para la automatización
- Multiplataforma con PowerShell Core
- Fácil de usar
  - Connect-AzAccount: inicie sesión en Azure
  - Get-AzResourceGroup: lista de grupos de recursos
  - New-AzResourceGroup: crear un nuevo grupo de recursos
  - New-AzVm: crear una máquina virtual

<img src="Images/Azure-powershell.png" width="800"/>

### **Azure CLI**
- Interfaz de línea de comandos para Azure
- Diseñado para la automatización
- Multiplataforma (Python)
- Fácil de usar
  - inicio de sesión az: inicie sesión en Azure
  - lista de grupos az: lista de grupos de recursos
  - az group create: crear un nuevo grupo de recursos
  - az vm create: crear una máquina virtual
- Native OS terminal scripting

<img src="Images/Azure-cli.png" width="900"/>

### **Azure Cloud Shell**
- Entorno de secuencias de comandos basado en la nube
- Completamente libre
- Admite Azure PowerShell y la CLI de Azure
- Docenas de herramientas adicionales
- Múltiples interfaces de cliente
  - Integración con Azure Portal (portal.azure.com)
  - Portal de Shell (shell.azure.com)
  - Extensión de código de Visual Studio
  - Terminal de Windows
  - Aplicación móvil de Azure
  - Integración con Microsoft Docs

<img src="Images/Azure-cloud-shell.png" width="900"/>

## **Soluciones de supervisión**
### **Azure Advisor**
- Servicio de **consultoria personalizada**
- Diseñado para proporcionar **recomendaciones** y **mejores prácticas** para
  - **Costo** (tamaños de SKU, servicios inactivos, instancias reservadas, etc.)
  - **Seguridad** (configuración de MFA, configuración de vulnerabilidades, instalaciones de agentes, etc.)
  - **Fiabilidad** (configuración de redundancia, eliminación suave en blobs, etc.)
  - **Rendimiento** (tamaños de SKU, versiones de SDK, limitación de E/S, etc.)
  - **Excelencia operativa** (salud del servicio, límites de suscripción, etc.)
- Recomendaciones **procesables**
- **¡Gratis!**

<img src="Images/Azure-advisor.png" width="900"/>

### **Azure Monitor**
- Servicio de **recopilación, análisis y visualizador de estos datos**
- Función de métricas en el entorno local y de Azure
- **Application Insights se basa en Azure Monitor**
- Puede enviar alertas a los grupos de seguridad de **Azure AD**

### **Azure Service Health**
- Vista personalizada del estado de los servicios, regiones y recursos de Azure en los que se basa su infraestructura.
- Proporciona, después de incidentes oficiales, un análisis de la causa principla(RCA)
- Ayuda a supervisar varios tipos de eventos: 
  - **Problemas de servicios** - Son de Azure, como las interrupciones
  - **Mantenimiento planeado** - Afectan la disponibilidad
  - **Avisos de estado** - Problemas que exigen actuar para evitar interrupción del servicio

## **Servicios de seguridad de red**
La estrategia de *defensa en profundidad* usa una serie de mecanismos para ralentizar el avance de un ataque dirigido a adquirir acceso no autorizado a los datos.  
Se puede visualizar como un conjunto de capas(De arriba hacia abajo) :
  - **Capa de seguridad física** es la primera línea de defensa para proteger el hardware informático del centro de datos.
  - **Capa de identidad y acceso** controla el acceso a la infraestructura y al control de cambios.
  - **Capa perimetral** usa protección frente a ataques de denegación de servicio distribuido (DDoS) para filtrar los ataques a gran escala antes de que puedan causar una denegación de servicio para los usuarios.
  - **Capa de red** limita la comunicación entre los recursos a través de controles de acceso y segmentación.
  - **Capa de proceso** protege el acceso a las máquinas virtuales.
  - **Capa de aplicación** ayuda a garantizar que las aplicaciones sean seguras y estén libres de vulnerabilidades de seguridad.
  - **Capa de datos** controla el acceso a los datos empresariales y de clientes que es necesario proteger.
Cada capa proporciona protección. Este enfoque elimina protección única y proporciona telemtría de alertas sobre la que se puede actuar de forma automática o manual.

Los *niveles de seguridad* es la capacidad de su organización de protegerse frente a amenazas de seguridad y responder a ellas. Los principios comunes usados para definir un nivel son:
  - **Confidencialidad** - Acceso a usuarios especifícos
  - **Integridad** - Evitar cambios no autorizados en la información
    - En reposo - Cuando se almacenan
    - En tránsito - Cuando se transfieren de un lugar a otro
  - **Disponibilidad** - Siempre estén disponibles los servicios y datos

### **Azure Firewall**
Firewall es un servicio de seguridad de red que monitorea y controla el tráfico entrante y saliente en función de un conjunto definido de reglas de seguridad.  
Es un firewall con estado, lo que implica que analiza el contexto completo de una conexión de red

- Servicio de firewall administrado basado en la nube y con *estado* (PaaS, Firewall como servicio)
- Alta disponibilidad integrada
- Usa una dirección IP pública estática 
- Altamente escalable
- Reglas de filtrado de tráfico entrante y saliente
- Compatibilidad con FQDN (Nombre de dominio completo), ej. microsoft.com
- Totalmente integrado con Azure monitor para registro y análisis

<img src="Images/Azure-firewall.png" width="900"/>

### **Azure DDoS Protección**
**DoS - Denegación de servicio**  
Ciberataque con la intención de causar una interrupción temporal o indefinida del servicio

<img src="Images/Dos.png" width="900"/>

**DDoS - Denegación de servicio distribuida**  
Ataque DoS que se origina en múltiples servidores

<img src="Images/Ddos.png" width="900"/>

**Azure DDoS Protection**
- Servicio de protección DDoS en Azure
- Diseñado para
  - Detecte el tráfico malicioso y bloquéelo mientras permite que los usuarios legítimos se conecten
  - Evite costos adicionales para entornos de escalado automático
- dos niveles
  - **Básico**: habilitado automáticamente para la plataforma Azure
  - **Estándar**: capacidades adicionales de mitigación y supervisión para los recursos de **Azure Virtual Network**
- El nivel estándar utiliza el aprendizaje automático para analizar los patrones de tráfico para una mayor precisión
- El nivel estándar ayuda a evitar:
  - Ataques volumétricos - este ataque busca desbordar la capa de red con una gran cantidad de tráfico
  - Ataques de protocolo - vuelven un destino inaccesible al aprovechar vulnerabilidad en la pila del protocolo de capa 3 y 4
  - Ataques de nivel de recursos(nivel de aplicación)(solo con el firewall de aplicaciones web) - dirigidos a paquetes de aplicaciones web para interrumpir la transmisión de datos entre hosts

<img src="Images/Ddos-protection.png" width="900"/>

## **Grupos de seguridad Azure**
Azure Firewall y Azure DDoS Protection ayudan a controlar el tráfico que proviene externamente, pero también se debe saber como proteger las redes internas de Azure.
### **Grupos de seguridad de red**
- Diseñado para filtrar el tráfico hacia (entrante) y desde (saliente) los recursos de Azure ubicados en Azure Virtual Network
- Filtrado controlado por reglas
- Posibilidad de tener múltiples reglas de entrada y salida
- Las reglas se crean especificando
  - Origen/Destino (direcciones IP, etiquetas de servicio, grupos de seguridad de aplicaciones)
  - Protocolo (TCP, UDP, cualquiera)
  - Puerto (o intervalos de puertos, por ejemplo, 3389 – RDP, 22 – SSH, 80 HTTP, 443 HTTPS)
  - Dirección (entrante o saliente)
  - Prioridad (orden de evaluación)

<img src="Images/security-groups.png" width="900"/>

### **Grupos de seguridad de aplicaciones**
- Característica que permite la agrupación de máquinas virtuales ubicadas en la red virtual de Azure
- Diseñado para reducir el esfuerzo de mantenimiento (asigne ASG en lugar de la dirección IP explícita)

<img src="Images/application-security-groups.png" width="900"/>

### **Combinación de servicios de Azure para una solución de seguridad de red completa**
[Leer aquí](https://docs.microsoft.com/es-es/learn/modules/secure-network-connectivity-azure/7-combine-services-complete-solution)

## **Rutas definidas por el usuario (UDR) con tablas de rutas**
### **Enrutamiento(Routing)**
Proceso de encontrar/seleccionar una ruta para el tráfico en una o varias redes.

<img src="Images/Routing.png" width="900"/>

### **User-defined Routes(UDR)**
- Rutas personalizadas (definidas por el usuario, estáticas) (UDR)
- Diseñado para anular el enrutamiento predeterminado de Azure o agregar nuevas rutas
- Administrado a través del recurso Azure Route Table
- Asociado con cero o más subredes de red virtual

<img src="Images/User-defined-routes.png" width="900"/>

## **Azure Identity Services**
### **Identidad**
La identidad en general significa el hecho de ser alguien o algo. Por ejemplo, nuestras cuentas de usuario se consideran identidad.
- Un usuario con username y password.
- También aplicaciones u otros servidores con claves secretas o certificados.
- El hecho de ser algo o alguien.

<img src="Images/Identity.png" width="900"/>

### **Autenticación(AuthN)**
El proceso de verificación/afirmación de identidad

<img src="Images/Authentication.png" width="900"/>

### **Autorización(AuthZ)**
Después de la autenticación empieza el proceso de autorización.  
El proceso de garantizar que solo las identidades autenticadas obtengan acceso a los recursos para los que se les ha otorgado acceso.

<img src="Images/Authorization.png" width="900"/>

### **Gestión de Acceso**
El proceso de controlar, verificar, rastrear y administrar el acceso a usuarios y aplicaciones autorizados.

### **Azure AD**
- Servicio de Gestión de Identidad y Acceso en Azure
- Gestión de identidades: usuarios, grupos, aplicaciones
- Gestión de acceso: suscripciones, grupos de recursos, funciones, asignaciones de funciones, - configuración de autenticación y autorización, etc.
- Utilizado por múltiples plataformas en la nube de Microsoft
  - Azure
  - Microsoft 365
  - Office 365
  - Servicios de Live.com (Skype, OneDrive, etc.)

<img src="Images/Azure-ad.png" width="900"/>

**Azure Active Directory (AD)** está relacionado con **Active Directory** de Windows Server.  
Azure AD es para:
  - **Administradores de TI** - Controlar acceso a las aplicaciones y los recursos en función de sus requisitos empresariales
  - **Desarrolladores de aplicaciones** - Agregar funcionalidad a las aplicaciones como SSO o habilitar una aplicación para que funcione con las credenciales existentes de un usuario.
  - **Usuarios** - Administrar sus identidades como restablecimiento de contraseña sin intervención de otros.
  - **Suscriptores de servicios en línea** - Suscriptores de Microsoft 365, Office 365, Azure, etc ya usan Azure AD. 

**Servicios proporcionados por Azure AD**: 
- **Autenticación** - Comprobación de identidad para acceder a aplicaciones y recursos, funciones de autoservicio del usuario y autenticación multifactor, lista de contraseña prohibidas y servicios de bloqueo inteligente.
- **Inicio de sesión único** - Permite iniciar sesión una vez y usar esa credencial para acceder a recursos y aplicaciones de distintos proveedores.
- **Administrador de aplicaciones** - Características como Application Proxy, aplicaciones SaaS, portal Aplicaciones y SSO
- **Administrador de dispositivos** - Registro de dispositivos a través de herramientas como Microsoft Intune. 

### **Autenticación multifactor (MFA)**
- Proceso de autenticación usando más de un factor (evidencia) para probar la identidad
- Tipos de factores
  - Factor de conocimiento: "Algo que sabes", ej. contraseña, pin
  - Factor de posesión – “Algo que tienes”, ej. teléfono, ficha, tarjeta, llave
  - Factor de característica física – “Algo que eres”, ej. huella dactilar, voz, rostro, iris del ojo
  - Factor de ubicación – “En algún lugar donde estés”, ej. ubicación gps
- Compatible con Azure AD de forma predeterminada (simple interruptor de encendido y apagado)

<img src="Images/Multi-factor-authentication.png" width="900"/>

### **Acceso condicional**
Herramienta que usa Azure AD para permitir o no el acceso a los recursos en función de señales de identidad. Estas señales incluyen **quién es,dónde se encuentra y desde qué dispositivo solicta el acceso el usuario**.  
Para usar el acceso condicional se necesita una licencia Azure AD Premium P1 o P2

## **Herramientas de seguridad**
### **Azure Security Center**
- Servicio de administración de seguridad de plataforma e infraestructura centralizada/unificada
- Integrado de forma nativa en los servicios de Azure
- Integrado con Azure Advisor
- dos niveles
  - Gratis (Azure Defender APAGADO): incluido en todos los servicios de Azure, proporciona evaluaciones continuas, puntuación de seguridad y recomendaciones de seguridad procesables
  - Pagado (Azure Defender ON): seguridad híbrida,
alertas de protección contra amenazas, análisis de vulnerabilidades, acceso a máquinas virtuales justo a tiempo (JIT), etc.
- Incluye funciones avanzadas de defensa en la nube para máquinas virtuales, seguridad de red e integridad de archivos
  - **Acceso Just-in-Time** - bloquea el tráfico de forma predeterminada en puertos de red especifícos, pero lo permite durante un tiempo especifico cuando un administrador lo solicita y aprueba.
  - **Controles de aplicaciones adaptables** - Puede controlar que aplicaciones se pueden ejecutar en VM´s. Por medio de ML se examinan procesos que se ejecutan en una VM y envia alertas si hay aplicaciones no autorizadas en ejecución.
  - **Protección de red adaptable** - Supervisa los patrones de tráfico de internet de las VM y los compara con la configuración actual de los grupos de seguridad(NSG) de la empresa. A partir de ahi, puede hacer recomendaciones sobre si los NSG deben bloquearse más.
  - **Supervisión de la integridad de los archivos** - Configuración del registro, aplicaciones y otros aspectos que puedan indicar un ataque de seguridad.
- Ofrece una vista centralizada de todas sus alertas de seguridad.
<div>
<img src="Images/Security-center.png" width="900"/>
<img src="Images/Security-center-2.png" width="900"/>
<img src="Images/Security-center-3.png" width="900"/>
</div>

[Video explicativo](https://youtu.be/tyztKP9rszU?list=PLGjZwEtPN7j-Q59JYso3L4_yoCjj2syrM)

### **Azure Sentinel**
Administración de seguridad a gran escala puede beneficiarse de sistema de administración de eventos e información de seguridad (SIEM) dedicado que agrega datos de seguridad de muchos orígenes diferentes.Además proporciona funciones para detección de amenazas y respuesta a ellas. **Azure Sentinel** es el sistema SIEM basado en la nube de Microsfot. Permite:
- **Recopilación de datos en la nube a gran escala** - Recopila datos de todos los usuarios, dispositivos, aplicaciones e infraestructura, tanto locales como de varias nubes. Las conexiones se administran por conectores integrados o API y formatos de registro estándar del sector.
  - **Conexión de soluciones de Microsoft** - Entre estas: orígenes de Microsoft 365,Azure AD y Firewall de Windows Defender
  - **Conexión de otros servicios y soluciones** - AWS CloudTrail, Citrix Analytics(Security), Sophos XG Firewall, VMware Carbon Black Cloud y Okta SSO
  - **Conexión de orígenes de datos estándar del sector** - Datos de otros orígenes que usan estándar de mensajería Formato de evento común (CEF), Syslog o la API REST.
- **Detección de amenazas no detectadas anteriormente** - Minimiza los falsos positivos mediante el análisis y la inteligencia sobre amenazas completas.
- **Investigación de amenazas con inteligencia artificial** Examine actividades sospechosas a gran escala usando la experiencia de Microsoft.
- **Respuesta rápida a los incidentes** Use la orquestación y la automatización de tareas comunes integradas.

Más información [aquí](https://docs.microsoft.com/es-es/learn/modules/protect-against-security-threats-azure/3-detect-respond-threats-sentinel)

### **Azure Key Vault**
- Servicio administrado para asegurar información sensible (aplicación/plataforma) (PaaS)
- Servicio de almacenamiento seguro
  - Administración de keys - facilita creación y control de claves de cifrado que se emplean para cifrar los datos.
  - Administración de secrets - Controla el acceso a tokens, contraseñas, certificados, claves de API y más.
  - Administración de certificados SSL/TLS - aprovisionar, administrar e implementar los certificados públicos y privadas de capa de socket seguros y seguridad de la capa de transporte de los recursos de Azure y recursos locales
  - Administración de secretos basado en módulos de seguridad de hardware(HSMs) - Se protegen mediante software o con dispositivos HSM validados por FIPS 140-2 de nivel 2.
- Altamente integrado con otros servicios de Azure (VM, Logic Apps, Data Factory, Web Apps, etc.)
- Centralización para controlar su distribución y reduce posibilidades de que se filtren
- Supervisión y registro de acceso
- Requiere autenticación y autorización adecuadas que garantiza almacenamiento seguro

<img src="Images/Key-vault.png" width="900"/>

### **Azure Dedicated Host**
En Azure, las VM se ejecutan en hardware compartido administrado por Microsoft, pero las cargas de trabajo de las VM están aisladas, pero debido a un cumplimiento normativo que obliga a ser el único cliente que usa el equipo físico, aparece **Azure Dedicated Host**.  
- Administrar servidores físicos dedicados para hospedar máquinas virtuales de Azure para Windows y Linux mediante Azure Dedicated Host.
- Ofrece visibilidad y control sobre infraestructura de servidor que ejecuta las VM
- Permite elegir número de procesadores, capacidades de servidor, series de VM y tamaños de estas.
- Para lograr alta disponibilidad puede aprovisionar varios hosts en un *grupo host* e implementar las VM´s en este grupo.
- Se puede aprovechar las ventajas del *control de mantenimiento* que permite controlar cuando se producen las actualizaciones de mantenimiento en VM.
- Se cobra por host dedicado y este precio se basa en familia de máquinas virtuales, el tipo de hardware y la región

<img src="Images/azure-dedicated-host.png" width="900"/>

## **Gobernanza en Azure**
*Gibernanza* describe el proceso general por el que se establecen reglas y directivas y se garantiza que esas reglas y directivas se aplican. En la nube tener una buena gobernanza ayuda a tener control de las aplicaciones y los recursos que se administran en la nube, así se garantiza que seamos compatibles con:
  - Estándares del sector, como **PCI DSS**
  - Estándares corporativos o de la organización
Las ventajas de gobernanza son mayores cuando:
  - Hay varios equipos de ingeniería que trabajan en Azure.
  - Hay varias suscripciones que administrar.
  - Hay requisitos normativos que deben aplicarse.
  - Hay estándares que deben seguirse en todos los recursos en la nube.

Cuando tenemos varios equipos de TI e ingeniería, ¿cómo podemos controlar el acceso que tienen a los recursos del entorno de nube? Una buena práctica de seguridad consiste en conceder a los usuarios únicamente los derechos que necesitan para realizar su trabajo, y solo a los recursos pertinentes.  
En vez de definir los requisitos de acceso detallados de cada individuo y, posteriormente, ir actualizándolos a medida que se vayan creando más recursos, Azure permite controlar el acceso a través del control de acceso basado en roles de Azure (RBAC de Azure).

### **Azure Role-based Access Control (RBAC)**
**¿Qué es un rol?**  
El rol (definición de rol) es una colección de acciones que la identidad asignada podrá realizar.  
La definición de roles es una respuesta a la pregunta "¿Qué se puede hacer?".  
Cuando se asignan usuarios o grupos a uno o varios roles, reciben todos los permisos de acceso asociados correspondientes.    

<img src="Images/Roles.png" width="900"/>

**¿Qué es un alcance?**
El ámbito es uno o más recursos de Azure a los que se aplica el acceso.  
La asignación de alcance es una respuesta a la pregunta "¿Dónde se puede hacer?"  

<img src="Images/Scopes.png" width="900"/>

**¿Qué es Security Principal?**
Security Principal es un objeto de Azure (identidad) que se puede asignar a un rol (por ejemplo, usuarios, grupos o aplicaciones).  
La asignación de **Security Principal** es una respuesta a la pregunta "¿Quién puede hacerlo?"  

<div>
<img src="Images/Security-principals.png" width="900"/>
<img src="Images/Security-principals-2.png" width="900"/>
</div>

**¿Qué es una asignación de roles?**  
La asignación de funciones es una combinación de la definición de funciones, la entidad de seguridad y el ámbito.  

<img src="Images/Rol-assignament.png" width="900"/>

**Características**  
- Sistema de autorización integrado en Azure Resource Manager (ARM) - ARM es un servicio de administración que proporciona una forma de organizar y proteger nuestros recursos en la nube.
- Diseñado para la gestión de acceso detallada de los recursos de Azure
- La asignación de roles es una combinación de
  - Definición de roles: lista de permisos como crear VM, eliminar SQL, asignar permisos, etc.
  - Principal de seguridad: usuario, grupo, entidad de servicio e identidad administrada y
  - Ámbito: recurso, grupos de recursos, suscripción, grupo de administración
- Jerárquico
  - Grupos de administración > Suscripciones > Grupos de recursos > Recursos
- Se admiten funciones integradas y personalizadas

**¿Cómo se aplica RBAC?**
Se aplica a cualquier acción que se inicie en un recurso de Azure que pasa por ARM.  
RBAC de Azure no aplica permisos de acceso en el nivel de aplicación ni de datos. La seguridad de la aplicación debe controlarla la propia aplicación.

**¿Cómo se administran los permisos de RBAC?**
En el panel **Control de acceso(IAM)** de Azure Portal

### **Azure Resource Locks**
Aun cuando haya directivas de control de acceso basado en roles de Azure (RBAC de Azure) en vigor, sigue existiendo el riesgo de que alguien con el nivel de acceso adecuado elimine recursos de nube críticos. Podríamos pensar en un bloqueo de recursos como un sistema de aviso que nos recuerda que un recurso no se debe eliminar o cambiar.

- Diseñado para evitar la eliminación y/o modificación accidental de recursos.
- Usado junto con RBAC
- Dos tipos de cerraduras
  - Solo lectura (ReadOnly): solo se permiten acciones de lectura
  - Eliminar (CanNotDelete): todas las acciones excepto eliminar están permitidas
- Los ámbitos son jerárquicos (heredados)
  - Suscripciones > Grupos de recursos > Recursos
- Los grupos de administración no se pueden bloquear
- Solo las funciones de propietario y administrador de acceso de usuario pueden administrar bloqueos (funciones integradas)
- Los bloqueos se aplican con independencia de los permisos RBAC

<div>
<img src="Images/resource-locks.png" width="900"/>
<img src="Images/resource-locks-2.png" width="900"/>
</div>

**¿Cómo se administran los bloqueos de recursos?**
Desde Azure Portal, PowerShell, CLI o con una plantilla en ARM. Desde Azure Portal, en Configuración/Bloqueos de cualquier recurso en Azure Portal.  
Se pueden aplicar bloqueos a una suscripción o aun grupo de recursos o a un recurso individual.

### **Azure Resource Tags**
- Las etiquetas son simples pares Nombre (clave) - Valor
- Diseñado para ayudar con la organización de los recursos de Azure
- Se pueden agregar, modificar o eliminar etiquetas a través de PowerShell, CLI, Plantillas de ARM, API REST o Azure Portal. También se pueden administrar mediante Azure Policy para que las etiquetas se hereden.
- Se utiliza para la gestión de recursos, la seguridad, la gestión de operaciones, la gestión de costes, la automatización, etc.
- Estrategias típicas de etiquetado
  - Funcional – marcar por función (ej: entorno = producción)
  - Clasificación: marca por políticas utilizadas (por ejemplo: clasificación = restringido)
  - Finanzas/Contabilidad: marca para fines de facturación (por ejemplo, departamento = finanzas)
  - Asociación: marca por asociación de usuarios/grupos (p. ej., propietario = adam)
- Aplicable para recursos, grupos de recursos y suscripciones
- NO se hereda por defecto

<img src="Images/tags.png" width="900"/>

### **Azure Policy**
Surge de la necesidad de asegurarse que sus recursos mantenga su cumplimiento de gobernaza y si pudiera recibir un aviso cuando la configuración de un recurso cambie. Crea, asigna y administra directivas que controlan o auditan recursos.

- Definir directivas individuales y grupos de directivas relacionadas (*iniciativas*)
- Impedir que se creen recursos no conformes.
- Se integra con **Azure DevOps** aplicando directivas de integración continua y canalización de entrega.
- Diseñado para ayudar con la gestión de recursos, la seguridad, el cumplimiento, la gestión de costes, etc.
- Las políticas se centran en las propiedades de los recursos (RBAC se centra en las acciones del usuario)
- Definición de política: define lo que debería suceder
  - Defina la condición (if/else) y el efecto (denegar, auditar, agregar, modificar, etc.)
  - Los ejemplos incluyen tipos de recursos permitidos, ubicaciones permitidas, SKU permitidos, heredar etiquetas de recursos
- Se admiten políticas integradas y personalizadas
- Iniciativa de política: un grupo de definiciones de política
- Asignación de política: asignación de una definición/iniciativa de política a un ámbito
- Los alcances se pueden asignar a
  - grupos de gestión,
  - suscripciones,
  - grupos de recursos y
  - recursos
- Las políticas permiten exclusiones de alcances
- Comprobado durante la creación o actualización de recursos y los existentes con tareas de remediación

<div>
<img src="Images/Policy.png" width="900"/>
<img src="Images/Policy-2.png" width="900"/>
</div>

### **Azure Blueprints**
Un blueprint es una guía,patrón o diseño para realizar algo

<img src="Images/blueprint.png" width="900"/>

- Paquete de varios componentes de Azure (artefactos)
  - Grupos de recursos
  - Plantillas ARM
  - Asignaciones de políticas
  - Asignaciones de roles
- Almacenamiento centralizado para patrones de diseño aprobados por la organización
- Definición de plano: describe lo que debería suceder (paquete reutilizable)
- Asignación de blueprint: describe dónde debería suceder (implementación del paquete)

<div>
<img src="Images/blueprint-2.png" width="900"/>
<img src="Images/blueprint-3.png" width="900"/>
</div>

**Uso de Azure Blueprints**
La relación entre la definición del plano técnico y su asignación permanece, es decir, Azure crea un registro que asocia un recurso con el plano técnico que lo define y con esta conexión se realiza el seguimiento y la auditoría de nuestras implementaciones.  
Los planos técnicos también tienen versiones y el control de versiones nos permite llevar un control de los cambios que se producen en el plano técnico y comentarlos.

**Artefactos de plano técnico**
Cada componente de la definición de un planot técnico se denomina *artefacto*.
Los *artefactos* pueden contener uno o más parámetros que se pueden configurar

### **Cloud Adoption Framework for Azure** 
Sirve como guía consolidada para ayudar en el recorrido para la adopción de la nube.
#### **Adopción de la nube**
La adopción de la nube es un movimiento estratégico de una organización para aprovechar la nube en su negocio

#### **Marco de adopción de la nube**
Cloud Adoption Framework for Azure es un conjunto de
  - herramientas,
  - mejores prácticas,
  - directrices y
  - documentación
preparado por Microsoft para ayudar a las empresas en su proceso de adopción de la nube.

#### **Estrategía**
1. Comprende tu motivación
- Responde a la pregunta ¿POR QUÉ MOVERSE?
- Los desencadenantes comunes de la motivación incluyen
  - Migración
    - Ahorro de costos en infraestructura
    - Reducción de la complejidad
    - Optimización de operaciones
    - Mayor agilidad empresarial
  - Innovación
    - Alcanzando una escala global
    - Mejoras en la experiencia del cliente
    - Transformación de productos o servicios
    - Interrupción del mercado
2. Resultado comercial
- Responde a la pregunta ¿QUÉ MEDIR?
- Resultado definido, conciso y observable capturado por una medida específica, por ejemplo
  - Aumento de los ingresos
  - Aumento de la ganancia
  - Reducción de costo
  - Acceso global a los clientes
  - Llegar a nuevos mercados
3. Justificación comercial
- Responda a la pregunta ¿CUÁL ES MI RENTABILIDAD DE LA INVERSIÓN?
- Desarrolle un caso de negocios para validar el modelo financiero que respalda sus - motivaciones y resultados
- Las herramientas que apoyan este proceso son
  - Calculadora de TCO (costo total de propiedad) de Azure: calcule los costos locales actuales
  - Calculadora de precios de Azure: calcule los costos futuros de Azure
  - Administración de costos de Azure: vea los costos actuales de Azure
4. Primer Proyecto
- Elija el primer proyecto para validar su estrategia (Prueba de concepto - POC) basado en
  - Criterios de negocio
    - Operando actualmente
    - Propietario dedicado
    - Fuerte motivación para moverse.
  - Criterios Técnicos
    - Dependencias y activos mínimos

#### **Plan**
1. Digital Estate (INVENTARIO DE ACTIVOS)
  - Revise el panorama actual y enumere todos los proyectos/soluciones (activos digitales)
  - Elija una de las cinco (5) R de racionalización
    - Rehost: muévase como está; típicamente en contenedores o IaaS (máquinas virtuales)
    - Refactorización: realice pequeños cambios en el código y pase a PaaS (por ejemplo, Azure SQL, Azure App Service, etc.)
    - Rearquitectura - realice cambios de código complejos para introducir nuevas funciones o reparar aplicaciones incompatibles
    - Reconstruir: cree una nueva aplicación usando el primer diseño de la nube
    - Reemplazar: revise las soluciones SaaS disponibles y reemplace las aplicaciones heredadas o innecesarias
2. Alineación inicial de la organización
  - Alinee a las personas para que apoyen su plan de adopción
  - Asignar personas a capacidades
3. Plan de preparación de habilidades
  - Revisar las habilidades actuales y abordar las brechas
4. Plan de adopción de la nube: combine todo, desde los pasos 1 a 3 en un solo plan de adopción de la nube

<img src="Images/Plan.png" width="900"/>

#### **Comienzo**
1. Guía de configuración de Azure: revise la guía de configuración de Azure para familiarizarse con las herramientas y los enfoques que debe usar para crear una zona de aterrizaje.
2. Azure Landing Zone: elija un tipo de suscripción de Azure adecuado que mejor se adapte a sus necesidades y establezca un entorno de Azure inicial.
3. Ampliar zona de aterrizaje -
Amplíe la zona de aterrizaje inicial para que se ajuste a las necesidades de su empresa.
4. Mejores prácticas: revise todo y asegúrese de que se sigan las mejores prácticas.

<img src="Images/Ready.png" width="900"/>

#### **Adopción**
**Emigrar**  
1. Primera migración: migre su primera aplicación para familiarizarse con la nube, las pautas y las herramientas
2. Escenarios de migración: revise y prepare escenarios/directrices de migración para su empresa
  - Máquinas virtuales: Linux, Windows, etc.
  - Aplicaciones: aplicaciones web Java, .NET, NodeJS, etc.
  - Datos: SQL Server, PostreSQL, servidores de archivos, etc.
  - Otro - VMware, Azure Stack, etc.
3. Mejores prácticas: aborde las necesidades comunes de migración mediante la aplicación de mejores prácticas coherentes.
4. Mejoras de procesos: una parte importante de esta actividad intensa de proceso es identificar cuellos de botella y mejorar con cada migración
  
<img src="Images/Adopt.png" width="900"/>

**Innovar**
1. Consenso de valor comercial (VALOR A LA ESTRATEGIA)
  - Crear una necesidad hipotética del cliente
  - Decide la solución que lo solucione
  - Asigne esto a su estrategia
2. Guía de innovación (HERRAMIENTAS): elija las herramientas de Azure disponibles que lo ayudarán a crear esta aplicación
3. Mejores prácticas: verifique que se sigan las mejores prácticas para todas las herramientas en la cadena de herramientas
4. Mejoras de Procesos - recopilar comentarios de los usuarios y clientes para mejorar las decisiones arquitectónicas y los productos futuros

#### **Gobierno y Administración**
1. Defina soluciones de gobierno: elija soluciones para mantener el cumplimiento, la seguridad y garantizar el control total del entorno.
  - Esas soluciones deben centrarse en
    - Abordar las necesidades comerciales
    - Proporcionar agilidad
    - Riesgos de control
2. Administrar el entorno de la nube (OPERACIONES EN LA NUBE): entregue las soluciones y el entorno al equipo de operaciones de la nube para su mantenimiento.
El equipo debe garantizar que la estabilidad y los costos estén siempre en perfecto equilibrio para cumplir con los compromisos comerciales. El equipo debe permitir que el entorno crezca, evolucione y se adapte a las necesidades comerciales cambiantes

<div>
<img src="Images/Govern.png" width="900"/>
<img src="Images/Govern-2.png" width="350"/>
</div>

#### **Organizar**
Asegúrese de que todos sepan qué hacer y cuándo hacerlo en cada etapa de este proceso. Una de las formas de lograr esto es a través de la matriz RACI (Responsable, Responsable, Consultado e Informado).

<img src="Images/Organize.png" width="900"/>

## **Core tenets of Security,Privacy,Compliance(Trust Center,DPA,OST y más)**

Document/Website | Diagrama | Info | Ofertas | Audiencia

**Microsoft Privacy Statement**  
<img src="Images/Microsoft-privacy-statement.png" width="900"/> 

- Recopilación, Propósito y Uso de Datos Personales|Todas las ofertas de Microsoft, incluidos servicios, aplicaciones, sitios web, software, servidores, dispositivos
- Todos 
- Clientes finales o empresas 

**Online Services Terms (OST)**  
<img src="Images/Online-services-terms.png" width="900"/> 

- Términos de licencia (acuerdo legal): derechos de uso sobre los servicios de Azure. Lo que se puede hacer y lo que está prohibido.
- Servicios en línea de Microsoft como Azure, servicios de Microsoft 365, Bing Maps, etc.
- Organizaciones - Equipos legales

**Data Protection Addendum**  
<img src="Images/Data-protection-addendum.png" width="900"/>

- Anexo al OST que describe las obligaciones de ambas partes (Microsoft y usted) con respecto al procesamiento de datos personales y del cliente
- Servicios en línea de Microsoft como Azure, servicios de Microsoft 365, Bing Maps, etc.
- Organizaciones - Equipos legales, equipos de seguridad

**Trust Center**  
<img src="Images/Trust-center.png" width="900"/>

- Portal web de ventanilla única para todo lo relacionado con seguridad, cumplimiento, privacidad, políticas, mejores prácticas, etc.
- Servicios en línea de Microsoft como Azure, servicios de Microsoft 365, Bing Maps, etc.
- Organizaciones: equipos legales, equipos de seguridad, gerentes comerciales, administradores

**Azure Compliance Documentation**  
<img src="Images/Azure-compliance-docs.png" width="900"/>

- Portal web que se centra en las ofertas de cumplimiento en Azure, similar al centro de confianza pero reducido
- Azure
- Organizaciones: equipos legales, equipos de seguridad, gerentes comerciales, administradores de Azure

### **Azure Government**
Es una instancia independiente del servicio de Microsoft Azure. Aborda las necesidades de seguridad y cumplimiento de las agencias federales de EE. UU., los gobiernos locales y estatales, así como sus proveedores de soluciones. Azure Government ofrece aislamiento físico de las implementaciones que no son del gobierno de los Estados Unidos y proporciona personal estadounidense que ha pasado por un filtro.

### **Azure China 21Vianet**
Es operado por 21Vianet. Se trata de una instancia físicamente separada de servicios en la nube que se encuentra en China.  
Según el Reglamento de telecomunicaciones de China, los proveedores de servicios en la nube, infraestructuras como servicio (IaaS) y plataformas como servicio (PaaS) deben tener permisos de telecomunicaciones de valor añadido. Solo las compañías registradas localmente con una inversión extranjera inferior al 50 % pueden optar a estos permisos.  
Los contratos y acuerdos de Azure en China, cuando corresponde, se firman entre los clientes y 21Vianet.

### **Regiones soberanas de Azure**
Azure Sovereign Regions proporciona servicios de Azure en mercados con requisitos normativos muy estrictos.  
- Azure Government diseñado para el gobierno de EE. UU.
  - Instancia separada de Azure (ciclo de vida, servicios, portal, etc.)
  - Aislado físicamente de otras regiones de Azure
  - Solo el personal escaneado autorizado puede tener acceso
- Azure China diseñado para el mercado chino
  - Instancia separada de Azure (ciclo de vida, servicios, portal, etc.)
  - Aislado físicamente de otras regiones de Azure
  - Operado por una empresa de telecomunicaciones china llamada 21Vianet

## **Planeación y administración de costos de Azure**
- Costo base
  - Tipos de recursos: todos los servicios de Azure (recursos) tienen modelos de precios específicos de recursos. Por lo general, consta de una o más métricas.

  <img src="Images/Resource-types.png" width="900"/>

  - Servicios: las ofertas específicas de Azure (Enterprise, Web Direct, CSP, etc.) tienen diferentes costos y componentes de facturación, como prepagos, ciclos de facturación, descuentos, etc.

  <img src="Images/Services.png" width="900"/>

  - Ubicación: la ejecución de los servicios de Azure varía entre las regiones de Azure

  <img src="Images/Location.png" width="900"/>

  - Ancho de banda: tráfico de red al cargar (entrante/ingreso) datos a Azure o al descargar (saliente/egreso) desde Azure

  <img src="Images/Bandwidth.png" width="900"/>

- Savings
  - Instancias reservadas
  - Beneficios Híbridos

### **Cost Reduction Methods, Reservations, Hybrid benefit, Spot VM, Pricing y TCO**
#### **Reservaciones en Azure**
Adquiera los servicios de Azure con 1 o 3 años de anticipación con importantes descuentos
  - Instancias reservadas: Azure Virtual Machines
  - Capacidad reservada: Azure Storage, núcleos virtuales de SQL Database, DBU de Databricks, RU de Cosmos DB
  - Planes de software: Red Hat, Red Hat OpenShift, SUSE Linux, etc.
  - Las reservas se hacen para 1 o 3 años

<img src="Images/Reservations.png" width="900"/>

#### **Máquinas virtuales al contado de Azure**
Compre capacidad de máquina virtual no utilizada para obtener un descuento significativo  
- Cómo funciona
  - Descuento significativo para máquinas virtuales de Azure
  - La capacidad se puede retirar en cualquier momento.
  - El cliente puede establecer el precio máximo después del descuento para mantener o desalojar la máquina
- Lo mejor para cargas de trabajo interrumpibles (procesamiento por lotes, entornos de desarrollo/prueba, grandes cargas de trabajo informáticas, tareas no críticas,
etc)

<img src="Images/Spot-VM.png" width="900"/>

#### **Beneficio de uso híbrido**
Usar licencias existentes en la nube
  - Usar licencias existentes en Azure
    - Windows Server
      - Azure VM
    - Red Hat
      - Azure VM 
    - SUSE Linux
      - Azure VM 
    - SQL Server
      - Azure SQL Database
      - Azure SQL Managed Instance
      - Azure SQL Server on VM
      - Azure Data Factory SQL Server Integration Services

<img src="Images/Hybrid-use-benefit.png" width="900"/>

#### **Herramientas**
- Calculadora de precios: calcule el costo de los servicios de Azure
  - Seleccionar servicio
  - Ajustar parámetros (uso)
  - ver el precio
- Calculadora de costo total de propiedad (TCO): calcule y compare el costo de ejecutar cargas de trabajo en el centro de datos versus Azure
  - Defina sus cargas de trabajo
  - Ajustar suposiciones
  - Ver el informe


### **Azure Cost Managment**
#### **Administración de costos de Azure**
- Un servicio centralizado para generar informes sobre el uso y la facturación del entorno de Azure
- Capacidades de exploración de costos de autoservicio
- Presupuestos y alertas
- Recomendaciones de costos
- Exportaciones automatizadas

<img src="Images/Cost-managment.png" width="900"/>

#### **Minimización de costos en Azure**
- Calculadora de precios de Azure para elegir la región de bajo costo
  - Buena latencia
  - Todos los servicios requeridos están disponibles.
  - Soberanía de datos/requisitos de cumplimiento
- Beneficio de uso híbrido y reservas de Azure
- Supervisión, presupuestos, alertas y recomendaciones de Azure Cost Management
- Comprenda el ciclo de vida del servicio y automatice los entornos
- Utilice las funciones de escalado automático a su favor
- Azure Monitor para encontrar y reducir recursos infrautilizados
- Use etiquetas y políticas para una gobernanza eficaz

## **SLA y SLA Compuesto en Azure**
**SLA**  
El Acuerdo de nivel de servicio (SLA) es un acuerdo formal entre un proveedor de servicios y un cliente.  
No es necesaria una suscripción de Azure para revisar los SLA. [Ver aquí.](https://azure.microsoft.com/es-es/support/legal/sla/)   
SLA es una promesa de disponibilidad de un servicio (tiempo de actividad y conectividad). La disponibilidad es una medida del tiempo que un servicio permanece operativo.  
  - Cada Servicio tiene su propio SLA
  - Rangos de 99% a 99.999%
  - Los servicios gratuitos normalmente no tienen un SLA
  - SLA roto significa devolución de crédito de servicio (descuento)

SLA | Tiempo de inactividad mensual
---|---
99%|7h 18m 17s
99.5%|3h 39m 8s
99.9%|43m 49s
99.95%|21m 54s
99.99%|4m 22s
99.999%|26s

**Créditos de servicio**
Es el porcentaje de precio que ha pagado y que se le abonará conforme al proceso de aprobación de reclamaciones. Si un servicio no funciona de acuerdo a su SLA, puede obtener un descuento compensatorio en su factura.

### **Acuerdo de nivel de servicio de aplicación**
Define los requisitos del acuerdo para una aplicación específica.

### **Formulas**
**AND lógico - agregando dependencia**
Disponibilidad de **S1 AND S2** = Disponibilidad (S1) * Disponibilidad (S2)  
Escenario: sitio web de Azure con base de datos back-end de SQL
  - Disponibilidad = Disponibilidad (web) aplicación * Disponibilidad (sql)
  - Disponibilidad = 99,95 % * 99,95 %
  - Disponibilidad = 0,9995 * 0,9995
  - Disponibilidad = 0.99900025
  - Disponibilidad ~ 99,9%

<img src="Images/AND.png" width="900"/>

**OR lógico: agregando redundancia**
Disponibilidad de **S1 OR S2** = 100 % - ( Indisponibilidad (S1) * Indisponibilidad (S2) )  
Escenario: dos aplicaciones web redundantes detrás de un balanceador de carga
  - Disponibilidad (ambos-web) = 100% - ( Indisponibilidad (web1) * Indisponibilidad (web2))
  - Disponibilidad (ambos-web) = 100% - ( 0.05% * 0.05% )
  - Disponibilidad (ambos-web) = 1 – ( 0.0005 * 0.0005 )
  - Disponibilidad (ambos-web) = 1 – 0.00000025
  - Disponibilidad (ambos-web) = 0.99999975
  - Disponibilidad (ambos-web) ~ 99.9999%

<img src="Images/AND-2.png" width="900"/>

### **Elementos clave**
- Acuerdo formal entre Microsoft y el cliente
- Calculado como un porcentaje de la disponibilidad del servicio (tiempo de actividad y conectividad) (una promesa)
- Romper el SLA proporciona un descuento de la factura mensual final (Crédito de servicio)
- Los servicios de nivel superior ofrecen mejores SLA
- Los servicios gratuitos normalmente no tienen SLA (0% SLA)
- Los servicios de vista previa no tienen SLA
- SLA compuesto es un SLA combinado de todos los componentes de la aplicación

## **Ciclo de vida de un servicio en Azure | Public preview and General availability**
### **Ciclo de vida del servicio**
- Cada servicio en Azure sigue su propio ciclo de vida de servicio
- La vista previa pública es una etapa 'beta' del servicio disponible para el uso del público en general
- Las características también pueden estar en etapas de vista previa
- Diseñado para pruebas, no para soluciones de producción.
- La disponibilidad general es una versión de "producción" del servicio

<div>
<img src="Images/lifecycle-public.png" width="600"/>
<img src="Images/lifecycle-private.png" width="600"/>
</div>

### **Información clave de vista previa pública**
- Sin SLA
- Algunos servicios no tienen cobertura de soporte
- Disponibilidad de región limitada
- funcionalidad limitada
- Cambios de precios
- Cambios de dirección
- Vistas previas de Azure Portal (https://preview.portal.azure.com)