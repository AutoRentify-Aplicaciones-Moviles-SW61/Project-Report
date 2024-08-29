<p align="center">
    <strong>Universidad Peruana de Ciencias Aplicadas</strong><br>
<br><img src="images/upcLogo.png"></img><br>  
    <strong>Ingeniería de Software - 202402</strong><br>
    <br>
    <strong>SI729 - Desarrollo de Aplicaciones Móviles - SW61</strong><br>  
    <br>
    <strong>Profesor: Mayta Guillermo, Jorge Luis
</strong><br>
    <br> <strong>INFORME DE TRABAJO FINAL - TB1 </strong> 
</p>
<p align="center">
    <strong>Startup: AutoRentify </strong><br>
    <strong>Producto:  GottaGoFast </strong>
</p>

<h3 align="center" >Team Members:</h3>
<div>
    <table align="center">
        <tr>
            <th style="text-align:center;">Member</th>
            <th style="text-align:center;">Code</th>
        </tr>
        <tr>
            <td>Christian Renato Espinoza Saenz</td>
            <td>U202213208</td>
        </tr>
        <tr>
            <td>Julio Esteban Elsner De La Torre Ugarte</td>
            <td>U202111654</td>
        </tr>
        <tr>
            <td>Joaquin David Rivadeneyra Ramos</td>
            <td>U202211846</td>
        </tr>
        <tr>
            <td>Alvaro Felipe Pinto Fuentes Rivera</td>
            <td>U202213384</td>
        </tr>
        <tr>
            <td>Serrano Ircañaupa, Nelson Elías</td>
            <td>U202214733</td>
        </tr>
    </table>
</div>
<br>

## Registro de Versiones del Informe

| Versión |   Fecha    | Autor | Descripción de modificación | 
|:-------:|:----------:|:-----:|:-----------------------| 
|TB1| 24/08/2024 |Todos los integrantes del equipo| Capítulo I, Capítulo II|
## Contenido
### Tabla de Contenidos
### [Student Outcome](#student-outcome-1)
### [Capítulo I: Introducción](#capítulo-i-introducción)
- [1.1. Startup Profile](#11-startup-profile)
  - [1.1.1. Descripción de la Startup](#111-description-de-la-startup)
  - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
- [1.2. Solution Profile](#12-solution-profile)
  - [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)
  - [1.2.2 Lean UX Process](#122-lean-ux-process)
    - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
    - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
    - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
    - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
- [1.3. Segmentos objetivo](#13-segmentos-objetivo)

### [Capítulo II: Needfinding](#capitulo-ii-needfinding-1)
- [2.1. Competidores](#21-competidores)
  - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
  - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
- [2.2. Entrevistas](#22-entrevistas)
  - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
  - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
  - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
- [2.3. Needfinding](#23-needfinding)
  - [2.3.1. User Personas](#231-user-personas)
  - [2.3.2. User Task Matrix](#232-user-task-matrix)
  - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
  - [2.3.4. Empathy Mapping](#234-empathy-mapping)
  - [2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)
- [2.4. Requirements Specification](#23-ubiquitous-language)
  - [2.4.1 To-Be Scenario Mapping](#31-to-be-scenario-mapping)
  - [2.4.2 User Stories](#32-user-stories)
  - [2.4.3 Impact Mapping](#33-impact-mapping)
  - [2.4.4 Product Backlog](#34-product-backlog)
### [Conclusiones](#conclusiones-1)
### [Bibliografía](#bibliografia-1)
### [Anexos](#anexos-1)



## **Student Outcome**
El curso contribuye al cumplimiento del Student Outcome ABET:

ABET – EAC − Student Outcome 7 Aprendizaje Continuo y Autónomo

Criterio: La capacidad de adquirir y aplicar nuevos conocimientos según sea necesario, utilizando estrategias de aprendizaje apropiadas.

En el siguiente cuadro se describen las acciones realizadas y enunciados de conclusiones por parte del equipo, que permiten sustentar el haber alcanzado el logro del ABET – EAC − Student Outcome.

|**Criterio específico**|**Acciones realizadas**|**Conclusiones**|
| - | - | - |
|Actualiza conceptos y conocimientos necesarios para su desarrollo profesional y en especial para su proyecto en soluciones de software.|<p>**TB1:**</p><p>**Joaquin David Rivadeneyra Ramos:** Se llevó a cabo un estudio con el propósito de comprender en detalle el desafío que enfrentamos. Este proceso nos permitió identificar a los grupos de personas a los que nos enfocamos, entender sus necesidades particulares y desarrollar un producto que las satisfaga.</p><p></p><p>**TB1:**</p><p>**Julio Elsner:** Se analizó a profundidad el negocio en la vida real y se evaluaron los casos para la creación de los dos segmentos objetivos mediante esto nos permitió a poder crear la lógica de negocio de la aplicación móvil y como el impacto al consumidor final.</p><p>**Nelson Elías Serrano**</p><p></p><p>**TB1:**</p><p>Para esta primera versión, se investigaron recursos para formular el desarrollo del proyecto. Desde la problemática, aplicando técnicas de las 5w’s y 2h’s y de Lean UX</p><p></p><p></p><p>**Christian Renato Espinoza Saenz**</p><p></p><p>**TB1:**</p><p>En esta versión, me encargué de desarrollar las historias de usuario y de crear los impact maps para cada segmento. Analizando a fondo ambos segmentos para asegurarme de que las historias de usuario y los maps se alinean con las necesidades y objetivos específicos de cada uno. </p><p></p><p>**Alvaro Felipe Pinto Fuentes Rivera**</p><p></p><p>**TB1:**</p><p>En esta entrega, mi trabajo fue desarrollar los empathy maps por cada segmento, además de supervisar el desarrollo de los Objetivos Smart y ayudar con la investigación para nuestra bibliografía asegurándonos de la veracidad de nuestras fuentes tomando en cuenta su cuartil.</p>|<p>**TB1:**</p><p>Realizamos una investigación y un análisis detallado para impulsar nuestro proyecto de soluciones de software. Definimos los segmentos de mercado a los que nos dirigimos y comprendimos sus necesidades, lo que nos permitió crear soluciones innovadoras. Además, evaluamos el contexto del proyecto, identificamos obstáculos y examinamos las soluciones actuales para resaltar oportunidades de innovación. Este enfoque meticuloso nos asegura responder de manera eficaz a las demandas del mercado. También reconocemos la importancia de actualizar continuamente nuestros conocimientos para mantenernos al día en nuestro desarrollo profesional.</p>|
|Reconoce la necesidad del aprendizaje permanente para el desempeño profesional y el desarrollo de proyectos en soluciones de software.| <p>**TB1:**</p><p>**Joaquin David Rivadeneyra Ramos:** Se preparó un informe detallado que cubrió desde la identificación del problema hasta la propuesta de estrategias de solución. Esto resalta la importancia de seguir aprendiendo para crecer profesionalmente en proyectos de software.</p><p></p><p>**TB1:**</p><p>**Julio Elsner:** En base al análisis de negocio se implementó un esquema con herramientas de diseño para lograr nuestro objetivo final. Añadido a esto, se plantearon preguntas a los dos segmentos objetivos para lograr una visión más detallada de los requerimientos de los usuarios. </p><p></p><p>**Nelson Elías Serrano**</p><p></p><p>**TB1:** Para seguir progresando con el proyecto es fundamental probar las hipótesis planteadas según Lean UX. Además, a través del Canvas, respondemos las preguntas planteadas para formular el propósito de nuestro proyecto y abarcarlo de la mejor manera.</p><p></p><p>**Christian Renato Espinoza Saenz**</p><p></p><p>**TB1:** Me encargué de realizar una entrevista dirigida al segmento de administradores de talleres, donde profundicé en el ámbito de la automotriz. A través de esta entrevista, aprendí e investigué en detalle sobre las necesidades, desafíos y oportunidades que enfrentan los administradores en su día a día. </p><p></p><p>**Alvaro Felipe Pinto Fuentes Rivera**</p><p>**TB1:** Se indagó en la perspectiva de cada usuario para descubrir que sienten, piensan, ven o hacen.</p><p></p> |<p>**TB1:**</p><p>Alcanzamos logros significativos en el avance de nuestro proyecto. Hemos transformado nuestras ideas y propuestas en un plan detallado, abordando de manera integral los desafíos que se nos presentan. Además, hemos creado informes exhaustivos que incluyen investigaciones sobre el problema, análisis de la competencia, así como propuestas y estrategias de solución. Estos informes están organizados de manera clara y objetiva, proporcionando una base sólida para el progreso de nuestro proyecto. En resumen, hemos demostrado un compromiso sólido con la calidad y la exhaustividad.</p>|

## **Objetivos Smart**

<table align="center">
        <tr>
            <th style="text-align:center;">Member</th>
            <th style="text-align:center;">Plan</th>
        </tr>
        <tr>
            <td>Christian Renato Espinoza Saenz</td>
            <td>Uno de mis objetivos es mejorar la usabilidad de la aplicación móvil haciendo que la interfaz de usuario sea más cómoda para el usuario basandome en principios fundamentales de UX que he aprendido. Planeo realizar estas mejoras dedicando al menos 6 horas semanales a nuestro proyecto.</td>
        </tr>
        <tr>
            <td>Julio Esteban Elsner De La Torre Ugarte</td>
            <td>Para el desarrollo del backend me propongo implementar correctamente las funcionalidades básicas de la arquitectura RESTful para la aplicación "Gotta Go Fast". Para ello aplicaré lo aprendido en los cursos anterior para nuestro proyecto dedicandole 8 horas semanales.</td>
        </tr>
        <tr>
            <td>Joaquin David Rivadeneyra Ramos</td>
            <td>Me considero bueno con en analisis de datos, por lo que mi objetivo es revisar detenidamente las entrevistas, utilizaré las respuestas para identificar patrones comunes en los usuarios y así llevar cuenta de las necesidades y percepción de nuestros segmentos objetivos. Para ello planeo necesitar al menos unas 7 horas semanales.</td>
        </tr>
        <tr>
            <td>Alvaro Felipe Pinto Fuentes Rivera</td>
            <td>Como mi punto fuerte es la busqueda de información planeo hacer dedicarme al menos 6 horas semanales a realizar una investigación profunda para hallar funciones necesarias o altamente solicitadas, además de explorar a la competencia para apoyar en el desarrollo de herramientas y aspectos que nos hagan diferenciar de los demás. </td>
        </tr>
        <tr>
            <td>Serrano Ircañaupa, Nelson Elías</td>
            <td>Yo me enfocaré en optimizar el código de la aplicación para mejorar su rendimiento. Mi objetivo es revisar las secciones clave del código para eliminar posibles redundancias. También, implementaré técnicas que aprendí en complejidad algoritmica. Dedicaré 6 horas semanales a esta tarea.</td>
        </tr>
    </table>


## **Capítulo I: Presentación**

### **1.1. Startup Profile**


#### **1.1.1. Descripción de la Startup**

 ---

AutoRentify es una startup dedicada a revolucionar la manera en que las personas alquilan vehículos. A través de nuestra aplicación móvil, ofrecemos una experiencia de alquiler ágil, segura y accesible, adaptada a las necesidades modernas. Nuestra plataforma conecta a usuarios con una amplia red de proveedores de autos, garantizando una amplia variedad de opciones y precios competitivos. AutoRentify se enfoca en la simplicidad y la eficiencia, eliminando las complicaciones tradicionales del proceso de alquiler y brindando a los usuarios control total desde la palma de su mano.

**Misión:**  
Facilitar el acceso a una experiencia de alquiler de autos rápida, confiable y personalizada mediante el uso de tecnología innovadora. Nuestro objetivo es empoderar a los usuarios con una plataforma intuitiva que les permita encontrar y alquilar el vehículo perfecto para sus necesidades de manera eficiente, desde cualquier lugar y en cualquier momento.

**Visión:**  
Convertirnos en la plataforma líder en alquiler de autos, redefiniendo la industria con un enfoque en la conveniencia y la transparencia. Aspiramos a construir una comunidad global de usuarios satisfechos que confían en AutoRentify para todas sus necesidades de movilidad, promoviendo al mismo tiempo un modelo de negocio sostenible y tecnológicamente avanzado.

#### **1.1.2. Perfiles de integrantes del equipo**
| Integrante                | Perfil                                | Foto                                                |
|---------------------------|--------------------------------------------------|-------------------------------------|
| Elsner De La Torre Ugarte (u202111654) | Mi nombre es Julio Elsner De La Torre Ugarte, tengo 19 años y soy estudiante de la carrera de ingeniería de software. Con anterioridad ya he tenido experiencia con el tipo de trabajos que conllevan trabajo grupal y que busca una solución a alguna problemática. En mi opinión, soy bastante hábil extrayendo información de algún problema lo cual mejora el trabajo conjunto en grupo y la organización en general. | ![Foto1](images/JulioElsner.png)                |
| Rivadeneyra Ramos, Joaquin David (U202211846) | Soy Joaquin Rivadeneyra, tengo 19 años y actualmente estoy cursando el 5to ciclo de la carrera de Ingeniería de Software. Me considero una persona comunicativa y abierta a nuevas ideas, lo que me permite tener una buena relación con los demás miembros del equipo y fomentar un ambiente de trabajo colaborativo. | ![Foto3](https://github.com/ReadWell-SW54-SI729/Informe/assets/149616870/9299c70a-dcd0-4be9-85b4-54f2ccb67eb7)               |
| Espinoza Saenz, Christian Renato (U202213208) | Mi nombre es Christian Espinoza, soy un estudiante de 19 años que cursa el 6to ciclo de la carrera Ingeniería de Software. Poseo ideas únicas e innovadoras para que el trabajo logre sobresalir. Tengo experiencia en la creación de distintos tipos de diagramas, editar diferentes tipos de multimedia como videos, y un conocimiento general en programación de C++, HTML, CSS y SQL, que será beneficioso para el proyecto.| ![Foto4](https://i.postimg.cc/1RCVXhbj/foto.jpg/8ad1bb6d-e043-494f-b687-a3d5f02d2ab9)               |
| Pinto Fuentes Rivera Alvaro (U202213384)   | Hola, mi nombre es Alvaro, soy un estudiante del quinto ciclo de la carrera Ingeniería de Software. Me gusta mucho leer, sobretodo el género de fantasía y ciencia ficción, mi frase favorita de un libro es el credo "Vida antes que muerte, fuerza antes que debilidad y viaje antes que destino", también soy un gran fan del cine y pasó la mayor parte de mi tiempo libre escribiendo por diversión. Poseo un nivel bueno de programación en los lenguajes de C# y C++, creo que podré resultar de gran ayuda durante el desarrollo del proyecto, así como podré brindar ideas creativas para el equipo. | ![Foto5](images/fotoAlvaro.jpg)                 |
| Nelson Elías Serrano (U202214733) | Me llamo Nelson Serrano, estudiante de Ingeniería de Software con el código estudiantil U202214733. Mi carrera se basa en crear soluciones digitales e innovadoras para distintas problemáticas del mundo real . Las habilidades en las que puedo aportar en el grupo son dominio y práctica de lenguajes de programación como C++ y python, documentación de proyectos y metodologías ágiles y conocimientos básicos de base de datos. | ![img.png](images/img.png)![](Aspose.Words.067514d0-720e-40d5-b69e-4e8975ffcf0c.006.png)   |

**1.2. Solution Profile**

**1.2.1 Antecedentes y problemática**

**Antecedentes**

El alquiler de autos ha sido una solución popular para satisfacer necesidades de movilidad a corto plazo, especialmente en situaciones donde el transporte público no es viable o conveniente. Sin embargo, el proceso tradicional de alquiler de autos puede ser engorroso y confuso, con múltiples pasos, falta de transparencia en precios y disponibilidad, y un servicio al cliente inconsistente. La digitalización y el auge de las aplicaciones móviles han comenzado a transformar la industria, pero aún existen áreas significativas de mejora, especialmente en la personalización de servicios y la accesibilidad para una base de usuarios más amplia.

**Problemática**

El alquiler de autos tradicional enfrenta varios desafíos que afectan tanto a los usuarios como a los proveedores de servicios. Los procesos suelen ser complejos y opacos, con numerosos pasos que pueden resultar confusos para los usuarios. Esto incluye la dificultad para comparar precios y opciones, la falta de transparencia en la disponibilidad de vehículos, y un servicio al cliente que puede variar en calidad. Además, la experiencia de reserva y gestión de vehículos a menudo no se alinea con las expectativas de comodidad y eficiencia de los consumidores modernos. Todo esto contribuye a una experiencia de usuario insatisfactoria y a una falta de fidelización en el sector.



- Who? (¿Quién?)
  
  ¿Quiénes enfrentan desafíos en el alquiler de autos?

  Los consumidores que buscan alquilar vehículos para diversos propósitos (viajes, eventos, uso personal) y las empresas de alquiler de autos que desean mejorar su alcance y eficiencia operativa.


- What? (¿Qué?)

  ¿Qué aspectos del proceso de alquiler de autos necesitan mejorar?

  La transparencia en los precios, la disponibilidad en tiempo real, la simplicidad del proceso de reserva, la personalización de las opciones de vehículos, y la calidad del servicio al cliente.




- Where? (¿Dónde?)

  ¿Dónde se deben implementar las mejoras en el alquiler de autos?

  Principalmente en áreas urbanas y destinos turísticos con alta demanda de alquiler de vehículos, y también en regiones menos cubiertas que podrían beneficiarse de un acceso más fácil a servicios de alquiler.


- When? (¿Cuándo?)

  ¿Cuándo es el momento ideal para introducir una nueva solución en el mercado de alquiler de autos?

  Durante períodos de alta demanda como vacaciones, eventos especiales, o durante el crecimiento del mercado de movilidad compartida, cuando los consumidores están más abiertos a probar nuevas soluciones tecnológicas.


- Why? (¿Por qué?)

  ¿Por qué es necesaria una nueva solución en el alquiler de autos?

  Porque el proceso actual es a menudo complicado y poco transparente, lo que genera frustración en los usuarios y pérdida de oportunidades para los proveedores. La demanda de soluciones más eficientes y tecnológicas está en aumento, y no se está satisfaciendo adecuadamente.




- How? (¿Cómo?)

  ¿Cómo solucionará nuestra aplicación los problemas existentes en el alquiler de autos?

  AutoRentify simplifica el proceso mediante una interfaz intuitiva que permite la búsqueda, comparación y reserva de vehículos en tiempo real. La aplicación ofrece precios claros, opciones personalizadas, y un servicio al cliente eficiente para mejorar la experiencia general del usuario.


- How Much?

  ¿Cuánto costará implementar y mantener esta solución?

  El costo incluye el desarrollo tecnológico, marketing, y la formación de alianzas con proveedores de autos. A través de un modelo de negocio basado en comisiones, suscripciones, y servicios adicionales, se busca asegurar que la solución sea rentable tanto para la startup como para sus socios comerciales.


#### **1.2.2 Lean UX Process**


#### **1.2.2.1. Lean UX Problem Statements**

 ---

El proceso de alquiler de autos tradicionalmente implica múltiples pasos, incluyendo la búsqueda en varios sitios, la comparación de precios y la confirmación de disponibilidad, lo que puede resultar en un proceso engorroso y poco transparente para los usuarios.

Las soluciones actuales a menudo carecen de una interfaz unificada y fácil de usar para comparar opciones, ver precios claros y realizar reservas de manera eficiente. Esto genera frustración en los usuarios y una experiencia inconsistente.

Nuestro producto abordará esta brecha mediante una aplicación móvil, AutoRentify, que ofrece una interfaz intuitiva para buscar, comparar y reservar autos de manera rápida y transparente. La aplicación proporcionará información clara sobre precios, disponibilidad en tiempo real, y opciones personalizadas para mejorar la experiencia del usuario.

Nuestro enfoque inicial será dirigido a usuarios de áreas urbanas y destinos turísticos que buscan una solución eficiente y confiable para alquilar vehículos, así como empresas de alquiler de autos que buscan optimizar su alcance y procesos operativos.

Sabremos que tenemos éxito cuando alcancemos una tasa de adopción del 30% entre los usuarios objetivo después de la implementación inicial y logremos un índice de satisfacción del cliente superior al 80%, medido a través de encuestas y feedback dentro de los primeros seis meses de lanzamiento


#### **1.2.2.2. Lean UX Assumptions**


---

**Business Assumptions:**

- Creo que los usuarios necesitan una forma más eficiente y transparente para alquilar vehículos.
- Estas necesidades se pueden resolver con una aplicación móvil que simplifique la búsqueda, comparación y reserva de autos, ofreciendo una interfaz intuitiva y opciones personalizadas.
- Mis clientes iniciales serán consumidores que buscan alquilar autos en áreas urbanas y destinos turísticos, así como empresas de alquiler de autos que desean mejorar su eficiencia operativa.
- El valor #1 que un cliente quiere obtener de mi servicio es un proceso de alquiler simplificado y transparente, con acceso rápido a información sobre precios y disponibilidad.
- El cliente también puede obtener beneficios adicionales como opciones personalizadas, reservas en tiempo real y un servicio al cliente confiable.
- Voy a adquirir la mayoría de mis clientes a través de estrategias de marketing digital, incluyendo campañas en redes sociales, publicidad en línea y asociaciones con proveedores de autos.
- Voy a ganar dinero mediante un modelo de ingresos basado en comisiones por reserva, suscripciones premium y servicios adicionales ofrecidos a través de la aplicación.
- Mi competencia principal en el mercado serán otras plataformas de alquiler de autos y servicios de movilidad compartida que ofrecen características similares.
- Venceremos a la competencia mediante una mejor experiencia de usuario, una interfaz más intuitiva y una mayor transparencia en los precios y la disponibilidad.
- Mi mayor riesgo es la resistencia al cambio por parte de los usuarios que están acostumbrados a métodos tradicionales de alquiler de autos.
- Resolveremos esto mediante una interfaz fácil de usar, demostraciones y tutoriales claros sobre cómo utilizar la aplicación, y un soporte al cliente accesible.

**User Assumptions:**

- El usuario principal es cualquier persona que necesite alquilar un vehículo, incluyendo viajeros, personas en mudanzas, y aquellos que requieren un auto por razones personales o profesionales.
- Nuestro producto se integra en la vida diaria del usuario proporcionando una plataforma centralizada para buscar, comparar y reservar autos de manera eficiente.
- Nuestro producto resuelve problemas de complejidad y falta de transparencia en el proceso de alquiler de autos, facilitando la toma de decisiones con información clara y opciones personalizadas.
- El usuario utiliza nuestra aplicación móvil regularmente cuando necesita alquilar un vehículo, ya sea para una ocasión específica o como parte de su rutina de movilidad.
- Las características importantes incluyen una interfaz de usuario intuitiva, opciones de búsqueda y filtrado personalizadas, información de precios y disponibilidad en tiempo real, y soporte al cliente eficiente.
- Nuestro producto debe tener una apariencia moderna y atractiva, con una interfaz clara que facilite la navegación y la realización de reservas. Debe comportarse de manera rápida y eficiente, ofreciendo respuestas rápidas a las búsquedas y reservas, y notificando al usuario sobre actualizaciones importantes en su reserva o en la disponibilidad de vehículos.



**Business Outcomes:**

Lograr que el 25% de los usuarios objetivo en áreas urbanas y destinos turísticos adopten la aplicación dentro del primer año de lanzamiento.
Asegurar que al menos el 60% de los usuarios registrados utilicen la aplicación al menos una vez por cada período de viaje o necesidad de alquiler.
Observar que más del 50% de los usuarios utilizan las funciones de comparación de precios y reserva en tiempo real al menos una vez al mes.
Mantener una tasa de retención del 75% entre los usuarios que han realizado al menos una reserva a través de la aplicación.
Lograr un aumento del 15% en el número de usuarios activos mensuales durante el segundo año después del lanzamiento.
Recibir una valoración positiva en el 85% de las encuestas de satisfacción enviadas a los usuarios después de completar una reserva.

---
**User Outcomes:**
- Los usuarios experimentarán un proceso de alquiler más rápido y menos complicado, desde la búsqueda hasta la reserva del vehículo.
- Obtendrán información clara sobre precios y disponibilidad, lo que facilita la toma de decisiones.
- Podrán personalizar su búsqueda y reservas según sus necesidades específicas, mejorando la satisfacción general.
- Los usuarios confiarán en la plataforma para manejar sus reservas de manera segura y eficiente, con un soporte al cliente accesible.



**Features:**

- Interfaz Intuitiva: Un diseño fácil de usar que permite a los usuarios buscar y comparar vehículos rápidamente.
- Disponibilidad en Tiempo Real: Información actualizada sobre la disponibilidad de vehículos y precios.
- Opciones de Personalización: Filtros y opciones para ajustar la búsqueda según preferencias de tipo de vehículo, características y opciones de recogida/entrega.
- Seguridad en las Transacciones: Mecanismos de pago seguros y protección de datos del usuario.
- Soporte al Cliente: Acceso a soporte en vivo y asistencia para resolver problemas o responder preguntas.
- Sistema de Calificaciones y Reseñas: Funcionalidad para que los usuarios califiquen y dejen reseñas sobre los proveedores de autos y la experiencia de alquiler.


#### **1.2.2.3. Lean UX Hypothesis Statements**

 ---

**Hipótesis 1:**

Creemos que lograremos que el 25% de los usuarios objetivo en áreas urbanas y destinos turísticos adopten la aplicación dentro del primer año de lanzamiento.

Si los usuarios de estas áreas.

Logran encontrar y reservar vehículos de alquiler de manera rápida y transparente.

Con una interfaz intuitiva que ofrezca precios claros y disponibilidad en tiempo real.

**Hipótesis 2:**

Creemos que al menos el 60% de los usuarios registrados utilizarán la aplicación al menos una vez por cada período de viaje o necesidad de alquiler.

Si los viajeros frecuentes y personas con necesidades ocasionales de alquiler.

Logran personalizar sus opciones de búsqueda y reservas de manera eficiente.

Con filtros avanzados que les permitan seleccionar vehículos según sus preferencias y necesidades específicas.

**Hipótesis 3:**

Creemos que más del 50% de los usuarios utilizarán las funciones de comparación de precios y reserva en tiempo real al menos una vez al mes.

Si los usuarios.

Logran acceder fácilmente a información actualizada y comparar múltiples opciones de vehículos.

Con una funcionalidad de comparación de precios que muestre opciones claras y transparentes en tiempo real.

**Hipótesis 4:**

Creemos que mantendremos una tasa de retención del 75% entre los usuarios que han realizado al menos una reserva a través de la aplicación.

Si los usuarios.

Logran tener una experiencia de reserva sin fricciones y sentirse respaldados por un soporte al cliente confiable.

Con un proceso de reserva simplificado y un servicio de atención al cliente accesible y eficiente.

**Hipótesis 5:**

Creemos que recibiremos una valoración positiva en el 85% de las encuestas de satisfacción enviadas a los usuarios después de completar una reserva.

Si los usuarios.

Logran completar sus alquileres sin problemas y perciben que el servicio añade valor a su experiencia de viaje.

Con un diseño de experiencia de usuario que priorice la facilidad de uso, la claridad de la información y la rapidez en el proceso de reserva.




#### **1.2.2.4. Lean UX Canvas**

 ---

![LeanUXCanvas.png](images/LeanUXCanvas.png)

LINK LEAN UX CANVAS: https://miro.com/app/board/uXjVKnG08sE=/?share_link_id=250310705435

### **1.3. Segmentos objetivo**

 ---

**Segmento objetivo #1: Personas Interesadas en Alquilar Vehículos**

**Aspectos demográficos:**

- **Sexo:** Masculino y femenino.
- **Edad:** 25-50 años.
- **Estado civil:** Varía entre solteros, casados y personas en relaciones estables.
- **Tamaño de la familia:** Desde individuos solos hasta familias pequeñas.

**Aspectos geográficos:**

- **Ubicación:** Principalmente en áreas urbanas y destinos turísticos donde el alquiler de vehículos es común.

**Aspectos psicográficos:**

- **Valores:** Valoran la conveniencia, la eficiencia en la planificación de sus viajes, y la transparencia en el acceso a servicios.
- **Intereses:** Interesados en viajes, tecnología, movilidad urbana, y soluciones que faciliten la logística diaria.
- **Comportamiento:** Buscan soluciones rápidas y confiables para sus necesidades de transporte. Prefieren aplicaciones móviles que ofrezcan claridad en precios y disponibilidad, y que permitan realizar reservas de forma sencilla. Tienden a comparar opciones antes de tomar una decisión y valoran la personalización del servicio.

 ---

**Segmento objetivo #2: Empresas de Alquiler de Autos**

**Aspectos demográficos:**

- **Sexo:** Masculino y femenino (en roles de gestión y operación).
- **Edad:** 30-55 años.
- **Estado civil:** Variado, abarcando desde solteros hasta personas con familias.
- **Tamaño de la empresa:** Desde pequeñas empresas de alquiler hasta grandes corporaciones con flotas amplias.

**Aspectos geográficos:**

- **Ubicación:** Localizadas en áreas urbanas y zonas turísticas donde existe una alta demanda de alquiler de vehículos.

**Aspectos psicográficos:**

- **Valores:** Enfocados en la eficiencia operativa, maximización de la ocupación de vehículos, y optimización del servicio al cliente.
- **Intereses:** Altamente interesados en plataformas que mejoren la gestión de reservas, la visibilidad del inventario en tiempo real, y que permitan alcanzar a un mayor número de clientes potenciales.
- **Comportamiento:** Buscan herramientas que aumenten la visibilidad de su oferta en el mercado, mejoren la eficiencia operativa y proporcionen una experiencia de usuario sin fricciones. Valoran soluciones tecnológicas que les permitan gestionar su flota de manera óptima y que ofrezcan soporte al cliente para resolver problemas rápidamente. Prefieren plataformas que se integren fácilmente con sus sistemas actuales y que ofrezcan reportes detallados para la toma de decisiones.

 --- 

Estos segmentos objetivo permiten a AutoRentify enfocar sus esfuerzos de desarrollo, marketing y ventas en satisfacer las necesidades específicas de sus principales audiencias.

# **Capítulo II: Needfinding**

## Competitive Analysis Landscape

### ¿Por qué llevar a cabo este análisis?
Este análisis se lleva a cabo para investigar, analizar y comparar el comportamiento de los competidores directos o indirectos en el mercado. Entender la dinámica competitiva es esencial para identificar las fortalezas y debilidades de nuestra empresa en relación con otras marcas. Al realizar este análisis, podemos descubrir oportunidades para mejorar nuestros productos y servicios, así como para diferenciar nuestra oferta en un mercado saturado. Además, permite anticipar movimientos estratégicos de los competidores, lo que es vital para tomar decisiones informadas y mantener una ventaja competitiva. También es útil para identificar tendencias del mercado y adaptarse a las necesidades cambiantes de los consumidores, asegurando que nuestra empresa no solo sobreviva, sino que prospere en un entorno competitivo. Por último, el análisis competitivo nos ayuda a desarrollar estrategias de marketing más efectivas y a optimizar los recursos para maximizar el retorno de la inversión.

### 2.1. Competidores

Algunos de los competidores a los que Gotta Go Fast podría enfrentarse son:

<ul>
    <li>
        <b>Hertz: </b>Una de las compañías de alquiler de vehículos más conocidas a nivel mundial, Hertz ofrece una amplia gama de coches para alquilar, con opciones flexibles de recogida y devolución en múltiples ubicaciones. La empresa es reconocida por su extensa red de sucursales y programas de fidelización para clientes frecuentes.
    </li>
    <li>
        <b>Avis: </b>Empresa líder en alquiler de coches, Avis se especializa en ofrecer una experiencia de alquiler rápida y conveniente, con opciones para alquileres a corto y largo plazo. Avis también tiene un programa de suscripción que permite a los usuarios acceder a vehículos con tarifas reducidas durante periodos más largos.
    </li>
    <li>
        <b>Enterprise: </b>Con una red global y una reputación sólida en el mercado de alquiler de vehículos, Enterprise ofrece una amplia selección de coches, desde económicos hasta de lujo. Además de sus servicios tradicionales, Enterprise también cuenta con opciones de alquiler a domicilio y planes de suscripción para alquileres prolongados.
    </li>
</ul>

### 2.1.1. Análisis competitivo

<table>
<tr><th colspan="16" valign="top"><b>Competitive Analysis Landscape</b></th></tr>
<tr><td colspan="9" valign="top">¿Por qué llevar a cabo este análisis?</td><td colspan="7" valign="top">Este análisis se lleva a cabo para investigar, analizar y comparar el comportamiento de los competidores directos o indirectos en el mercado de alquiler de vehículos.</td></tr>
<tr><td colspan="6" valign="top"><b>Nombre</b></td><td colspan="3" valign="top"><b>Gotta Go Fast</b></td><td colspan="3" valign="top"><b>Hertz</b></td><td colspan="3" valign="top"><b>Avis</b></td><td valign="top"><b>Enterprise</b></td></tr>
<tr><td colspan="6" valign="top"><b>Logo</b></td><td colspan="3" valign="top"><img src="./images/gottalogo.jpg"></td><td colspan="3" valign="top"><img src="./images/hertz.png"></td><td colspan="3" valign="top"><img src="./images/avis.png"></td><td valign="top"><img src="./images/enter.png"></td></tr>
<tr><td colspan="3" rowspan="4" valign="top"><b>Perfil</b></td><td colspan="3" rowspan="2" valign="top"><b>Overview</b></td><td colspan="3" rowspan="2" valign="top">Plataforma diseñada para simplificar el alquiler de vehículos, ofreciendo una amplia gama de coches y una interfaz intuitiva para realizar reservas rápidas. También cuenta con un plan de suscripción para usuarios regulares.</td><td colspan="3" rowspan="2" valign="top">Una de las compañías líderes a nivel mundial en alquiler de vehículos, conocida por su amplia red de sucursales y variedad de coches, con un enfoque en la conveniencia y la flexibilidad del cliente.</td><td colspan="3" rowspan="2" valign="top">Empresa especializada en el alquiler rápido y conveniente de coches, con opciones de alquiler a corto y largo plazo. Ofrece programas de fidelización y servicios adicionales.</td><td rowspan="2" valign="top">Una de las empresas más grandes en el mercado global de alquiler de vehículos, con una extensa selección de coches y servicios adicionales como alquiler a domicilio. Se enfoca en ofrecer opciones flexibles y convenientes para todos los clientes.</td></tr>
<tr></tr>
<tr><td colspan="3" rowspan="2" valign="top"><b>Ventaja competitiva ¿Qué valor ofrece a los clientes?</b></td><td colspan="3" rowspan="2" valign="top">Rapidez en el proceso de alquiler, una amplia selección de vehículos, opciones de entrega a domicilio, y precios competitivos con un plan de suscripción premium.</td><td colspan="3" rowspan="2" valign="top">Amplia red de ubicaciones, variedad de vehículos, y programas de fidelización para clientes frecuentes.</td><td colspan="3" rowspan="2" valign="top">Proceso de alquiler eficiente, acceso a una gama diversa de coches, y un sólido programa de fidelización.</td><td rowspan="2" valign="top">Extensa red global, opciones de alquiler flexibles, y servicios adicionales como el alquiler a domicilio y planes de suscripción.</td></tr>
<tr></tr>
<tr><td colspan="3" rowspan="2" valign="top"><b>Perfil de Marketing</b></td><td colspan="3" valign="top"><b>Mercado objetivo</b></td><td colspan="3" valign="top">Viajeros frecuentes, turistas, conductores ocasionales, y suscriptores de servicios de transporte.</td><td colspan="3" valign="top">Viajeros de negocios, turistas, y clientes corporativos.</td><td colspan="3" valign="top">Turistas, viajeros de negocios, y usuarios regulares de servicios de alquiler de vehículos.</td><td valign="top">Turistas, familias, viajeros de negocios, y clientes corporativos.</td></tr>
<tr><td colspan="3" valign="top"><b>Estrategias de Marketing</b></td><td colspan="3" valign="top"><p>Marketing digital, promociones para suscriptores, alianzas con hoteles y aerolíneas, y presencia en redes sociales.</p></td><td colspan="3" valign="top"><p>Publicidad en aeropuertos, promociones para clientes frecuentes, y colaboraciones con empresas de viajes.</p></td><td colspan="3" valign="top"><p>Promociones en línea, programas de lealtad, y campañas de marketing digital.</p></td><td valign="top"><p>Publicidad global, programas de fidelización, y promociones en línea.</p></td></tr>
<tr><td colspan="3" rowspan="3" valign="top"><b>Perfil de producto</b></td><td colspan="3" valign="top"><b>Productos y Servicios</b></td><td colspan="3" valign="top">Alquiler de vehículos, suscripción premium, entrega a domicilio, y soporte 24/7.</td><td colspan="3" valign="top">Alquiler de vehículos, programas de fidelización, y opciones de alquiler a largo plazo.</td><td colspan="3" valign="top">Alquiler de coches, opciones de seguro, y programas de fidelización.</td><td valign="top">Alquiler de vehículos, alquiler a domicilio, y suscripción premium.</td></tr>
<tr><td colspan="3" valign="top"><b>Precios y Costos</b></td><td colspan="3" valign="top">Ofrece tarifas competitivas con descuentos para suscriptores. El plan premium tiene un costo mensual de $29.99 USD.</td><td colspan="3" valign="top">Tarifas de alquiler varían según el vehículo y la ubicación, con programas de fidelización que ofrecen descuentos.</td><td colspan="3" valign="top">Tarifas competitivas, con descuentos disponibles a través de programas de lealtad y promociones estacionales.</td><td valign="top">Varía según el tipo de vehículo y duración del alquiler, con descuentos para suscriptores y usuarios frecuentes.</td></tr>
<tr><td colspan="3" valign="top"><b>Canales de distribución</b></td><td colspan="3" valign="top"><p>- Página web</p><p>- Aplicaciones móviles en dispositivos iOS y Android.</p></td><td colspan="3" valign="top"><p>- Sucursales físicas</p><p>- Página web</p><p>- Aplicaciones móviles</p></td><td colspan="3" valign="top"><p>- Sucursales físicas</p><p>- Página web</p><p>- Aplicaciones móviles</p></td><td valign="top"><p>- Sucursales físicas</p><p>- Página web</p><p>- Aplicaciones móviles</p></td></tr>
<tr><td colspan="3" rowspan="4" valign="top"><b>Análisis FODA</b></td><td colspan="3" valign="top"><b>Fortalezas</b></td><td colspan="3" valign="top"><p>- Rapidez y conveniencia</p><p>- Amplia selección de vehículos</p><p>- Plan de suscripción premium</p></td><td colspan="3" valign="top"><p>- Red global de ubicaciones</p><p>- Amplia gama de vehículos</p><p>- Reputación consolidada</p></td><td colspan="3" valign="top"><p>- Procesos de alquiler eficientes</p><p>- Amplia red de ubicaciones</p><p>- Programas de fidelización sólidos</p></td><td valign="top"><p>- Red global</p><p>- Flexibilidad de opciones</p><p>- Servicios adicionales</p></td></tr>
<tr><td colspan="3" valign="top"><b>Debilidades</b></td><td colspan="3" valign="top"><p>- Competencia feroz</p><p>- Dependencia de la tecnología</p></td><td colspan="3" valign="top"><p>- Precios relativamente altos</p><p>- Procesos de alquiler a veces lentos</p></td><td colspan="3" valign="top"><p>- Tarifas más altas</p><p>- Competencia intensa</p></td><td valign="top"><p>- Tarifas relativamente altas</p><p>- Competencia</p></td></tr>
<tr><td colspan="3" valign="top"><b>Oportunidades</b></td><td colspan="3" valign="top"><p>- Expansión internacional</p><p>- Alianzas estratégicas</p><p>- Innovación tecnológica</p></td><td colspan="3" valign="top"><p>- Crecimiento en mercados emergentes</p><p>- Innovación en servicios</p><p>- Expansión de la red</p></td><td colspan="3" valign="top"><p>- Expansión en mercados emergentes</p><p>- Innovación en procesos de alquiler</p></td><td valign="top"><p>- Expansión en nuevos mercados</p><p>- Colaboraciones estratégicas</p></td></tr>
<tr><td colspan="3" valign="top"><b>Amenazas</b></td><td colspan="3" valign="top"><p>- Competencia de otras plataformas de alquiler</p><p>- Cambios en la tecnología</p><p>- Regulaciones locales</p></td><td colspan="3" valign="top"><p>- Cambios en las regulaciones</p><p>- Competencia de empresas emergentes</p><p>- Disrupción tecnológica</p></td><td colspan="3" valign="top"><p>- Competencia de nuevas plataformas</p><p>- Cambios en la regulación</p></td><td valign="top"><p>- Competencia de nuevas plataformas de alquiler</p><p>- Cambios en la regulación</p></td></tr>
</table>

### 2.1.2. Estrategias y tácticas frente a competidores

Hemos empleado un análisis FODA para identificar las posibilidades y desafíos en el mercado, así como para evaluar nuestras fortalezas y debilidades internas. Esta metodología nos ha permitido concebir estrategias y tácticas que se ajusten de manera coherente a nuestro entorno y a los recursos disponibles.

**Estrategia de distinción:**

Para destacar en el mercado de alquiler de vehículos, hemos decidido implementar un servicio premium que se centre en la conveniencia y la personalización. Esto incluye la opción de entrega del vehículo directamente en la ubicación del cliente, ya sea en su hogar, oficina, o cualquier lugar de su elección. Además, ofreceremos un sistema de reservas ultrarrápido a través de nuestra aplicación, donde los usuarios pueden realizar reservas en menos de un minuto. Como parte de nuestra oferta diferenciada, Gotta Go Fast permitirá a los usuarios elegir entre una flota de vehículos exclusivos y de alta gama para experiencias de conducción excepcionales. También planeamos implementar un programa de fidelización que recompense a los usuarios frecuentes con descuentos y ventajas exclusivas, como upgrades de vehículos y acceso prioritario en temporadas altas.

**Estrategia de liderazgo en costos:**

Nos enfocaremos en optimizar nuestros costos operativos para poder ofrecer tarifas competitivas que atraigan a una amplia gama de clientes. Esto implicará la adopción de tecnologías de gestión de flotas más eficientes, la negociación de acuerdos favorables con proveedores de vehículos y la reducción de gastos mediante la automatización de procesos administrativos. Al reducir costos, Gotta Go Fast puede ofrecer precios más accesibles sin sacrificar la calidad del servicio, lo que nos permitirá atraer a clientes sensibles al precio, especialmente en segmentos de mercado como los turistas y los conductores ocasionales que buscan un equilibrio entre costo y conveniencia.

**Estrategia de mercadotecnia:**

Implementaremos una campaña de marketing digital enfocada en aumentar la visibilidad de nuestra aplicación entre los usuarios que buscan soluciones rápidas y convenientes para el alquiler de vehículos. Nuestras estrategias incluirán publicidad dirigida en plataformas como Google Ads, Instagram, y Facebook, donde nos enfocaremos en captar la atención de usuarios interesados en el turismo, los deportes automovilísticos, y la movilidad urbana. Además, planeamos colaborar con influencers en el ámbito del viaje y la automoción para promocionar nuestras ofertas especiales y destacar la facilidad de uso de nuestra aplicación. También lanzaremos promociones, como descuentos en la primera reserva y beneficios adicionales para quienes opten por nuestro plan de suscripción premium, para incentivar a nuevos usuarios a probar Gotta Go Fast.

**Tácticas:**

Nuestras tácticas incluyen la implementación de estudios de mercado continuos para identificar las preferencias y necesidades no satisfechas de los usuarios en el sector de alquiler de vehículos. Esta investigación nos permitirá ajustar nuestro servicio para satisfacer de manera más efectiva las demandas del mercado, asegurando que Gotta Go Fast se mantenga competitivo y relevante. Adicionalmente, planeamos realizar pruebas A/B para optimizar nuestras campañas publicitarias y ajustar nuestras ofertas en función de la respuesta del mercado. Esto, junto con un enfoque en la experiencia del cliente y la facilidad de uso de la aplicación, nos permitirá diferenciar a Gotta Go Fast de otros competidores y brindar un servicio que exceda las expectativas de nuestros usuarios.

### 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

### Segmento 1: Personas Locales y turistas Sin Vehículos

1. **¿Podrías contarnos un poco sobre tu estilo de vida en la ciudad?**
2. **¿Cómo sueles desplazarte a tus actividades diarias, como trabajo, estudios o ocio?**
3. **¿Has considerado alguna vez comprar un coche? ¿Por qué no lo has hecho hasta ahora?**
4. **¿Qué servicios de transporte utilizas con mayor frecuencia (transporte público, taxis, aplicaciones de movilidad)?**
5. **¿Con qué frecuencia alquilas vehículos?**
6. **¿Qué tipo de vehículo prefieres alquilar según tus necesidades (pequeño, SUV, deportivo, etc.)?**
7. **¿Qué te motiva a alquilar un vehículo en lugar de utilizar otro medio de transporte?**
8. **¿Prefieres alquilar vehículos por horas, días o semanas? ¿Por qué?**
9. **¿Cómo sueles reservar vehículos actualmente? ¿A través de apps, sitios web o en persona?**
10. **¿Qué aspecto consideras más importante al elegir un servicio de alquiler de coches (precio, variedad de vehículos, conveniencia, etc.)?**
11. **¿Qué tan importante es para ti la posibilidad de recibir el vehículo a domicilio?**
12. **¿Has tenido alguna mala experiencia al alquilar vehículos? Si es así, ¿podrías compartirla?**
13. **¿Qué mejoras o características adicionales te gustaría ver en los servicios de alquiler de vehículos?**
14. **¿Cuánto valoras la posibilidad de gestionar todo el proceso de alquiler desde una sola aplicación móvil?**
15. **¿Te resultaría útil contar con una opción de suscripción para obtener descuentos en alquileres frecuentes?**
16. **¿Qué opinas sobre la opción de ver reseñas y valoraciones de otros usuarios antes de alquilar un coche?**
17. **¿Qué nivel de asistencia al cliente esperas en una plataforma de alquiler de vehículos (chat en vivo, llamadas, asistencia en la app)?**
18. **¿Te gustaría recibir notificaciones sobre promociones o tarifas reducidas en alquileres?**
19. **¿Qué tan probable sería que recomendaras un servicio como Gotta Go Fast a tus conocidos?**
20. **¿Qué función crees que mejoraría más tu experiencia como usuario local sin coche en un servicio de alquiler?**

### Segmento 2:  Empresas que ponen en alquiler sus vehículos

1. **¿Cuáles son los principales desafíos que enfrenta al administrar su flota de vehículos?**
2. **¿Qué criterios utiliza para determinar la rentabilidad de un vehículo en alquiler?**
3. **¿Qué tipo de vehículos son los más solicitados por sus clientes?**
4. **¿Cómo maneja el mantenimiento y las reparaciones de los vehículos en su flota?**
5. **¿Qué tecnologías utiliza actualmente para gestionar sus operaciones de alquiler de vehículos?**
6. **¿Cuáles son sus principales canales de adquisición de clientes?**
7. **¿Cómo se asegura de que sus vehículos estén en las mejores condiciones para los clientes?**
8. **¿Qué tan importante es para usted la seguridad y la eficiencia de los vehículos?**
9. **¿Cómo maneja la rotación de vehículos en su flota?**
10. **¿Cuál es su proceso para fijar precios de alquiler?**
11. **¿Cuáles son las principales quejas que recibe de sus clientes?**
12. **¿Qué medidas toma para mejorar la satisfacción del cliente?**
13. **¿Qué estrategias utiliza para diferenciarse de la competencia en el mercado de alquiler de vehículos?**
14. **¿Cómo se adapta a las fluctuaciones en la demanda de alquileres de vehículos?**
15. **¿Qué aspectos considera al elegir una plataforma para alquilar sus vehículos?**
16. **¿Cuál es su proceso para evaluar el rendimiento de su flota de alquiler?**
17. **¿Cómo maneja los riesgos asociados con el alquiler de vehículos, como accidentes o daños?**
18. **¿Qué tan importante es la gestión de la reputación en su negocio?**
19. **¿Qué programas o incentivos ofrece a los clientes habituales?**
20. **¿Qué desafíos enfrenta al expandir su negocio de alquiler de vehículos a nuevas ubicaciones?**


### 2.2.2. Registro de entrevistas

### Personas Locales y turistas Sin Vehículos:

Entrevistado #1: 
![Entrevista1](./images/vz.jpg)
Andres Valle Zuta

●	Sexo: Masculino

●	Edad: 21 años

●	Distrito en el que vive: Surco

●	Nivel socioeconómico: Clase B
Entrevista:

●	Link: [Click para ver entrevista](https://drive.google.com/file/d/1Z5x02-7qjcuB_dzeJoMgaNv1tYk5D18m/view?usp=sharing)

●	Momento en el que inicia: 0:00

●	Duración: 6:03

●	Entrevistador: Rivadeneyra Ramos, Joaquin David

Resumen:
<p align="justify">
Andrés Valle Zuta lleva un estilo de vida urbano en la ciudad, utilizando principalmente transporte público y aplicaciones de movilidad, sin interés en comprar un coche debido a los costos y la conveniencia del transporte alternativo. Alquila vehículos ocasionalmente, prefiriendo pequeños o SUV por días, y valora la facilidad de reservar a través de apps, destacando la importancia del precio, la variedad de vehículos y la opción de entrega a domicilio. Aunque ha experimentado retrasos en la entrega de vehículos, considera crucial la posibilidad de gestionar todo desde una aplicación, ver reseñas, acceder a soporte al cliente y recibir notificaciones de promociones, lo que aumentaría la probabilidad de que recomiende el servicio.
</p>

Entrevistado #2:

![entrevista-lector4](images/MiguelLopez_Entrevista.png)

Nombre: Miguel Lopez

●	Sexo: Masculino

●	Edad: 21 años

●	Distrito en el que vive: Lima

●	Nivel socioeconómico: Clase B

Entrevista:

●	Link: [Click para ver entrevista](https://youtu.be/89MyCMDCgLI)

●	Momento en el que inicia: 0:00

●	Duración: 5:51

Resumen:
<p align="justify">
Miguel López, un turista mexicano, llega a Lima, Perú, con la intención de conocer su rica cultura, disfrutar de la gastronomía local y visitar lugares emblemáticos como Machu Picchu y el Valle Sagrado. Planea quedarse dos semanas y, como suele hacer en sus viajes, opta por alquilar un SUV para tener la flexibilidad de explorar diferentes destinos sin depender del transporte público. Para Miguel, la comodidad y la facilidad de reserva son esenciales, por lo que prefiere reservar y pagar con antelación a través de una aplicación móvil. También valora la seguridad y las reseñas de otros turistas, así como la opción de recoger el coche en el aeropuerto, lo que facilita su llegada. Además, considera importante contar con un servicio de asistencia al cliente disponible 24/7 y apreciaría promociones especiales para alquileres de varios días.
</p>

Entrevistado N°3: Ian Sanchez

  ![Entrevista](./images/ian-sanchez.png)

●	Nombre: Ian Sanchez

●	Edad: 21

●	Sexo: Masculino

●	Residencia: Venezuela

●	Entrevista:

●	Link: [Click para ver entrevista](https://drive.google.com/file/d/1CTHywJLc25pq3jJwSrn3CqUlsw1fwwDR/view?usp=sharing)

●	Momento en el que inicia: 0:00

●	Duración: 8:53

●	Entrevistador: Elsner De La Torre Ugarte, Julio 

Resumen:
<p align="justify">
Ian Sanchez de 21 años, un turista que llegó desde Venezuela, comparte su experiencia de viaje y sus preferencias al alquilar un coche. Planea quedarse en la ciudad durante una semana y suele alquilar vehículos cuando viaja para mayor comodidad. Ian prefiere alquilar coches económicos y prioriza el precio y la facilidad de reserva. Le gusta tener flexibilidad en su itinerario, pero también valora la opción de reservar y pagar con antelación. Ha utilizado servicios de alquiler en otros países y considera crucial recibir el coche en el aeropuerto. Prefiere gestionar el alquiler desde una aplicación móvil, donde la seguridad y las políticas de la compañía son sus mayores preocupaciones. Además, aprecia poder leer reseñas de otros turistas, tener asistencia 24/7, y acceder a tarifas reducidas, lo cual influiría en su decisión. La personalización del servicio y promociones especiales también son importantes para él, y tras una buena experiencia, recomendaría Gotta Go Fast a otros turistas.
</p>

### Empresas que ponen en alquiler sus vehículos:
Entrevistada #1: Sebastian Palacios

<ul>
    <li>
        Sexo: Masculino
    </li>
    <li>
        Edad: 27 años
    </li>
    <li>
        Distrito en el que vive: San Borja
    </li>
    <li>
        Nivel socioeconómico: Clase B
    </li>
</ul>
Entrevista:
<ul>
    <li>
        Link: <a href="https://youtu.be/6Al_sL4MM2g">Click para ver entrevista</a>
    </li>
    <li>
        Momento en el que inicia: 0:00
    </li>
    <li>
        Duración: 08:47
    </li>
      <li>
        Entrevistador: Espinoza Saenz, Christian Renato
    </li>
</ul>
<img src="https://i.postimg.cc/6qy3nqF1/sebastianpalacion.png" alt="Entrevista Autor 1">

Resumen:
<p align="justify">
    Entrevistamos a Sebastian Palacios, de 27 años,administrador de un taller de autos que enfrenta diversos desafíos en la gestión de su flota. Sebastián se ocupa de mantener los vehículos en óptimas condiciones mientras maneja la demanda fluctuante y la distribución eficiente de la flota. Sebastian menciona que sus principales canales de adquisición de clientes incluyen el marketing digital y asociaciones locales.Además destaca la importancia de la reputación y ofrece programas de fidelidad para clientes habituales.También enfrenta desafíos al expandir su negocio a nuevas ubicaciones, incluyendo la adaptación a nuevos mercados y la gestión de la logística de expansión.
</p>

Entrevistado #2: 

Mateo Loechle
![Entrevista3](./images/mateo-entrevista.png)

●	Sexo: Masculino


●	Edad: 29 años

●	Distrito en el que vive: Lima

●	Nivel socioeconómico: Clase A

Entrevista:

●	Link: [Click para ver entrevista](https://drive.google.com/file/d/18aUbc2nDt8k6JsA4vORVyraxBvSmktZF/view?usp=sharing)

●	Momento en el que inicia: 0:00

●	Duración: 9:04

●	Entrevistador: Elsner De La Torre Ugarte, Julio Esteban

Resumen:
<p align="justify">
Mateo Loechle de 29 años, propietario de una empresa de alquiler de vehículos, nos ofrece una visión detallada de los desafíos y estrategias en la gestión de su flota. Mateo destaca que uno de los mayores retos es mantener la rentabilidad de los vehículos, lo cual evalúa mediante criterios específicos como el costo de mantenimiento y la demanda de los diferentes tipos de vehículos, siendo los modelos económicos y SUV los más solicitados. Para garantizar la eficiencia y seguridad, implementa tecnologías avanzadas en la gestión de su flota, asegura un riguroso mantenimiento, y utiliza múltiples canales para adquirir clientes. La satisfacción del cliente es prioritaria, por lo que se enfoca en mantener sus vehículos en óptimas condiciones y maneja la rotación y fijación de precios con un enfoque estratégico. Mateo también destaca la importancia de la gestión de riesgos, incluyendo la atención a accidentes o daños, y la adaptación a la fluctuación en la demanda. Para diferenciarse en el competitivo mercado, Mateo implementa programas de incentivos para clientes habituales y se enfoca en la expansión a nuevas ubicaciones, considerando cuidadosamente las plataformas que mejor se adaptan a sus necesidades.
</p>

Entrevistado #3:

Leandro Medina

![Entrevista-nelson.png](./images/Entrevista-nelson.png)

●	Sexo: Masculino


●	Edad: 22 años

●	Distrito en el que vive: Lima

●	Nivel socioeconómico: Clase A

Entrevista:

●	Link: [Click para ver entrevista](https://www.youtube.com/watch?v=_RbKISOL-Qo)

●	Momento en el que inicia: 0:12

●	Duración: 4:58 

●	Entrevistador: Serrano Ircañaupa, Nelson Elías

Resumen:
<p align="justify">
Leandro nos dio a conocer su opinion de algunas de las preguntas planteadas por su conocimiento de estar relacionado con este tipo de empresarios de alquiler. Nos contó que los principales desafíos al administrar una flota de vehículos incluyen el mantenimiento regular, la gestión de reparaciones, la optimización de la rotación para maximizar la rentabilidad, y la actualización de los vehículos para cumplir con normativas y preferencias del cliente. Además mencionó que la rentabilidad de un vehículo se determina según su tasa de utilización, costos de mantenimiento, ingresos generados, y depreciación.
</p>


### 2.2.3. Análisis de entrevistas
Según las entrevistas realizadas y los resúmenes, hemos llevado a cabo un análisis de las entrevistas en el que destacamos las similitudes y hallazgos:

### Segmento Objetivo #1: Personas interesadas en alquilar vehículos

<p align="justify">
    Durante las entrevistas, se identificó que las personas interesadas en alquilar vehículos buscan principalmente comodidad y facilidad en el proceso de alquiler. Expresaron un fuerte deseo de contar con una aplicación móvil que les permita gestionar todo el proceso de alquiler de manera rápida y eficiente, desde la búsqueda del vehículo hasta su devolución. Además, valoran la posibilidad de comparar precios y leer reseñas de otros usuarios para tomar decisiones informadas. La personalización de las opciones de alquiler, como la elección del tipo de vehículo según sus necesidades y la flexibilidad en el tiempo de alquiler (horas, días, semanas), es crucial para estos usuarios. En resumen, los clientes buscan una plataforma que facilite el proceso de alquiler, ofrezca opciones personalizadas y permita una gestión integral a través de una aplicación móvil..
</p>

### Segmento Objetivo #2:  Empresas que ponen en alquiler sus vehículos

<p align="justify">
    Las entrevistas con los dueños de empresas que ponen en alquiler sus vehículos revelaron que estos buscan una plataforma que optimice la gestión de su flota y aumente la visibilidad de sus servicios. Valoran especialmente la capacidad de recibir retroalimentación directa de los clientes y de utilizar herramientas de análisis para mejorar sus operaciones. También consideran crucial la seguridad en la transacción y la flexibilidad para ajustar las ofertas y promociones en función de la demanda del mercado. La posibilidad de integrar la plataforma con sus sistemas actuales y de acceder a datos en tiempo real sobre el rendimiento de sus vehículos es vital para ellos. En conclusión, los dueños de empresas buscan una solución que les permita mejorar la eficiencia operativa, incrementar la satisfacción del cliente y obtener insights valiosos para optimizar su negocio..
</p>

### 2.3.1. User Personas

Personas interesadas en alquilar vehículos:

![Personas Locales y turistas Sin Vehículos](./images/turista.jpg)

Empresas que ponen en alquiler sus vehículos:

![Empresas que ponen en alquiler sus vehículos](./images/carlos.jpg)

### 2.3.2. User Task Matrix

### Segmento 1: Personas Locales y turistas Sin Vehículos

| Actividad                            | Descripción                                         | Frecuencia | Importancia |
|--------------------------------------|-----------------------------------------------------|------------|-------------|
| Buscar opciones de transporte        | Investigar diferentes medios de transporte disponibles. | Alta       | Alta        |
| Comparar precios de alquiler de vehículos | Evaluar costos entre distintas opciones de alquiler. | Alta       | Alta        |
| Reservar un vehículo                 | Hacer una reserva para un vehículo según las necesidades. | Alta       | Alta        |
| Recoger el vehículo                  | Ir a recoger el vehículo reservado.                | Baja       | Alta        |
| Devolver el vehículo                 | Entregar el vehículo al finalizar el alquiler.     | Baja       | Alta        |
| Gestionar reservas y pagos            | Administrar reservas y pagos a través de una aplicación o web. | Alta       | Alta        |
| Leer reseñas y valoraciones          | Consultar opiniones de otros usuarios sobre el servicio. | Media      | Alta        |
| Solicitar asistencia al cliente      | Contactar soporte para resolver problemas o dudas. | Baja       | Media       |
| Aprovechar ofertas y promociones     | Buscar y usar descuentos disponibles en el servicio de alquiler. | Media      | Media       |

### Segmento 2: Empresas que ponen en alquiler sus vehículos

| Actividad                              | Descripción                                                                                                  | Frecuencia | Importancia |
|------------------------------------------------|-------------------------------------------------------------------------------------------------------------------|----------------|-----------------|
| Administrar la flota de vehículos         | Supervisar y mantener la flota en óptimas condiciones, incluyendo el mantenimiento y las reparaciones necesarias. | Alta           | Alta            |
| Evaluar la rentabilidad de vehículos      | Analizar los ingresos y costos asociados a cada vehículo para determinar su rentabilidad.                         | Alta           | Alta            |
| Gestionar reservas y disponibilidad        | Supervisar y gestionar la disponibilidad de los vehículos para maximizar la ocupación.                            | Alta           | Alta            |
| Implementar tecnologías de gestión         | Utilizar software y herramientas tecnológicas para optimizar la gestión de la flota y las operaciones de alquiler. | Media          | Alta            |
| Adquirir nuevos clientes                   | Desarrollar estrategias de marketing y ventas para atraer nuevos clientes y expandir la base de clientes.         | Alta           | Alta            |
| Fijar precios de alquiler                 | Establecer tarifas competitivas para los vehículos en alquiler, basadas en la demanda y el mercado.               | Alta           | Alta            |
| Manejar la rotación de la flota            | Decidir cuándo vender o renovar los vehículos en la flota para mantener la eficiencia y satisfacción del cliente.  | Media          | Alta            |
| Asegurar la calidad del servicio           | Garantizar que los vehículos estén en perfectas condiciones para los clientes y que el servicio sea excelente.     | Alta           | Alta            |
| Atender quejas y resolver problemas        | Gestionar las quejas de los clientes y resolver cualquier problema relacionado con el alquiler de vehículos.       | Media          | Alta            |
| Evaluar la competencia y diferenciarse    | Analizar la competencia y desarrollar estrategias para diferenciarse en el mercado.                               | Media          | Alta            |
| Adaptarse a fluctuaciones de demanda       | Ajustar la oferta de vehículos y las estrategias de marketing según la demanda estacional y las tendencias del mercado. | Media          | Media           |
|Expansión a nuevas ubicaciones             | Planificar y ejecutar la expansión del negocio de alquiler de vehículos a nuevas ciudades o regiones.             | Baja           | Media           |
| Gestionar la seguridad y eficiencia        | Asegurar que todos los vehículos cumplan con los estándares de seguridad y eficiencia para reducir riesgos.       | Alta           | Alta            |
| Optimizar la gestión de pagos y reservas   | Facilitar la administración de pagos y reservas a través de plataformas tecnológicas.                             | Alta           | Alta            |

#### **2.3.3. User Journey Mapping**

En este documento, presentamos dos User Journey Maps que ilustran las experiencias actuales de dos segmentos clave dentro del contexto del alquiler de vehículos: los interesados en alquilar y las empresas de alquiler de vehículos.

**Hanna Schneider**:

![UserP1Hanna.png](images%2FUserP1Hanna.png)


**Carlos Herrera:**

![UserP2Carlos.png](images%2FUserP2Carlos.png)


### **2.3.4 Empathy Mapping**

**Segmento objetivo personas interesadas en alquilar:**

![Empathy map_ARRENDATARIO.png](images/Empathy%20map_ARRENDATARIO.png)

**Segmento objetivo de empresarios de alquiler de vehículos:**

![Empathy map_ARRENDADOR.png](images/Empathy%20map_ARRENDADOR.png)

### **2.3.5 As-is Scenario Mapping**

**Segmento objetivo personas interesadas en alquilar:**

![As-is NORMAL.png](images/As-Is_Arrendatarios.png)

**Segmento objetivo de empresarios de alquiler de vehículos:**

![As-is ARRENDADOR.png](images/As-Is_Empresario.png)


## **2.4. Requirements Specification**

### **2.4.1 To-Be Scenario Mapping**

**Segmento objetivo personas interesadas en alquilar:**

![As-is NORMAL.png](images/To-Be_Arrendatarios.png)

**Segmento objetivo de empresarios de alquiler de vehículos:**

![As-is ARRENDADOR.png](images/To-Be_Empresario.png)

### 2.4.2 User Stories
|         | Nombre                                                 |                                                                                                                                                                |
| ------- | ------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| EPIC01 | Gestión de la Información del Usuario                  
| EPIC02 | Inicio de Sesión y Registro Seguro                     |                                            |
| EPIC03 | Gestión de Recogida y Devolución de Vehículos                                                                            |
| EPIC04 | Acceso a Valoraciones y Comentarios de Usuarios        |                                              |
| EPIC05 | Búsqueda y Selección Rápida de Vehículos      
| EPIC06 | Planificación de la Duración del Alquiler del Vehículo 
| EPIC07 | Gestión Eficiente de Vehículos y Alquileres




|User Story ID|Título|Descripción|Criterios de Aceptación|Relacionado con (Epic ID)|
| :- | :- | :- | :- | :- |
|US01|Actualización de Información Personal|Como usuario, quiero actualizar mi información personal, para asegurarme de que mi perfil esté actualizado.|<p>Escenario 1: Actualización de Dirección</p><p>-Dado que el usuario ha cambiado de domicilio y necesita actualizar su dirección en la aplicación.</p><p>-Cuando el usuario ingresa al sistema, accede a su perfil y actualiza la dirección con la nueva información.</p><p>-Entonces el sistema guarda la nueva dirección y muestra un mensaje de confirmación indicando que la actualización ha sido exitosa.</p><p></p><p>Escenario 2: Ingreso de Información Incompleta</p><p>-Dado que el usuario intenta actualizar su información personal, pero deja algunos campos requeridos en blanco.</p><p>-Cuando el usuario intenta guardar la actualización.</p><p>-Entonces el sistema muestra un mensaje de error indicando qué campos faltan por completar.</p>|EPIC01|
|US02|Actualización de Método de Pago|Como usuario, quiero actualizar mis métodos de pago para asegurarme de que mis transacciones se procesen correctamente.|<p>Escenario1: Actualización Exitosa de Método de Pago</p><p>-Dado que el usuario desea actualizar su método de pago actual a una nueva tarjeta de crédito.</p><p>-Cuando el usuario ingresa a la sección de "Métodos de Pago" en la configuración de su cuenta, introduce los detalles de la nueva tarjeta de crédito y guarda los cambios.</p><p>-Entonces el sistema valida los detalles de la tarjeta de crédito, actualiza la información y muestra un mensaje de confirmación indicando que el método de pago ha sido actualizado con éxito.</p><p></p><p>Escenario 2: Error en la Actualización de Método de Pago por Información Inválida</p><p>-Dado que el usuario intenta actualizar su método de pago con una tarjeta de crédito que contiene información inválida. </p><p>-Cuando el usuario ingresa los detalles de la tarjeta de crédito en la sección de "Métodos de Pago" y guarda los cambios.</p><p>-Entonces el sistema detecta la información inválida, muestra un mensaje de error y especifica el campo invalido.</p>|EPIC01|
|US03|Configuración de Preferencias de Notificación|Como usuario, quiero ajustar mis preferencias de notificación para recibir solo los tipos de alertas que prefiero.|<p>Escenario 1: Desactivación de Alertas por Correo Electrónico</p><p>-Dado que el usuario ha decidido dejar de recibir ciertas alertas por correo electrónico.</p><p>-Cuando el usuario accede a "Preferencias de Notificación", desmarca la opción para recibir alertas específicas por correo electrónico.</p><p>-Entonces el sistema deja de enviar las alertas seleccionadas al correo electrónico del usuario y confirma la desactivación con un mensaje en la aplicación.</p><p>Escenario 2: Selección Exclusiva de Recordatorios de Reserva</p><p>-Dado que el usuario desea recibir únicamente notificaciones de recordatorios de reserva.</p><p>-Cuando el usuario accede a "Preferencias de Notificación", selecciona solo la opción de recibir "Recordatorios de Reserva" y desmarca todas las demás opciones.</p><p>-Entonces el sistema guarda la configuración y envía solo recordatorios de reserva l usuario. </p>|EPIC01|
|US04|Visualización del Historial de Actividades|Como usuario, quiero ver un historial de mis actividades y transacciones recientes para llevar un registro de mis reservas y gastos.|<p>Escenario 1: Acceso al Historial de Actividades</p><p>-Dado que el usuario desea consultar su historial de actividades.</p><p>-Cuando el usuario accede a la sección "Historial de Actividades" en la aplicación.</p><p>-Entonces el sistema muestra una lista detallada de todas las reservas y transacciones recientes, incluyendo fechas, tipos de vehículos alquilados, y montos pagados.</p><p></p><p>Escenario 2: Filtrar por Tipo de Actividad</p><p>-Dado que el usuario quiere ver sus reservas confirmadas.</p><p>-Cuando el usuario aplica un filtro en la sección "Historial de Actividades".</p><p>-Entonces el sistema muestra solo las transacciones que cumplen con el filtro seleccionado.</p>|EPIC01|
|US05|Preferencias de Idioma|Como usuario, quiero seleccionar mi idioma preferido para que la aplicación se muestre en el idioma que entiendo mejor.|<p>Escenario1:<br>Selección de Idioma Preferido</p><p>-Dado que el usuario desea cambiar el idioma en el que se muestra la aplicación.</p><p>-Cuando el usuario accede a "Configuración de Idioma" en la aplicación, selecciona el idioma deseado de la lista disponible y confirma la selección.</p><p>-Entonces el sistema cambia el idioma de la aplicación al idioma seleccionado y muestra una confirmación de que el cambio ha sido realizado con éxito.</p><p>Escenario 2:</p><p>Restablecimiento a Idioma Predeterminado</p><p>-Dado que el usuario ha cambiado el idioma de la aplicación y desea volver al idioma predeterminado.</p><p>-Cuando el usuario accede a "Configuración de Idioma" y selecciona la opción para restablecer al idioma predeterminado.</p><p>-Entonces el sistema cambia el idioma de la aplicación al idioma predeterminado del dispositivo y muestra una confirmación de que el idioma ha sido restablecido.</p>|EPIC01|
|US06|Gestión de Planes|Como usuario, quiero ver y gestionar mis planes y suscripciones para adaptar el nivel de servicio a mis necesidades y explorar beneficios adicionales.|<p>Escenario 1: Actualización de Plan de Suscripción</p><p>-Dado que el usuario quiere cambiar su plan de suscripción a uno con más beneficios.</p><p>-Cuando el usuario selecciona la opción para actualizar su plan en la sección "Mis Planes", elige el nuevo plan deseado y confirma el cambio.</p><p>-Entonces el sistema actualiza el plan de suscripción del usuario al nuevo plan seleccionado, y muestra una confirmación de que el cambio ha sido realizado con éxito.</p><p>Escenario 2:</p><p>Cancelación de Plan de Suscripción</p><p>-Dado que el usuario desea cancelar un plan de suscripción activo.</p><p>-Cuando el usuario accede a la sección "Mis Planes", selecciona el plan que desea cancelar y confirma la cancelación.</p><p>-Entonces el sistema procesa la cancelación del plan de suscripción, notifica al usuario sobre la fecha de finalización y asegura que no se realizarán más cargos para ese plan.</p>|EPIC01|
|US07|Registro de Nuevo Usuario|Como nuevo usuario, quiero registrarme en la aplicación proporcionando mis datos.|<p>Escenario 1: Registro Exitoso de Usuario</p><p>-Dado que el nuevo usuario ha ingresado un correo electrónico único, una contraseña válida y otros detalles requeridos.</p><p>-Cuando el usuario haga clic en "Registrar".</p><p>-Entonces el sistema valida la información, crea una cuenta nueva y redirige al usuario a la página principal.</p><p></p><p>Escenario 2: Registro Fallido por Correo Electrónico Duplicado</p><p>-Dado que el usuario intenta registrarse con un correo electrónico que ya está en uso.</p><p>-Cuando el usuario hace clic en "Registrar".</p><p>Entonces el sistema muestra un mensaje de error indicando que el correo electrónico ya está en uso y solicita al usuario que ingrese uno diferente.</p>|EPIC02|
|US08|Desactivar o Eliminar Cuenta|<p>Como usuario,</p><p>quiero tener la opción de desactivar temporalmente o eliminar permanentemente mi cuenta,</p><p>para asegurar mis datos.</p>|<p>Escenario 1: Desactivar Cuenta Temporalmente</p><p>-Dado que el usuario está en la configuración de su cuenta.</p><p>-Cuando el usuario selecciona la opción para desactivar la cuenta temporalmente.</p><p>-Entonces el sistema desactiva la cuenta, permitiendo al usuario reactivarla más tarde al iniciar sesión, y notificar al usuario que la cuenta ha sido desactivada temporalmente.</p><p></p><p>Escenario 2: Eliminación Permanente de la Cuenta</p><p>-Dado que el usuario está en la configuración de su cuenta.</p><p>-Cuando el usuario selecciona la opción para eliminar permanentemente la cuenta.</p><p>-Entonces el sistema elimina de forma irreversible todos los datos asociados a la cuenta y notificar al usuario que la eliminación ha sido completada.</p>|EPIC02|
|US09|Inicio de Sesión con Correo Electrónico y Contraseña|Como usuario, quiero iniciar sesión en la aplicación usando mi correo electrónico y contraseña para acceder a mi cuenta de manera segura.|<p>Escenario 1: Ingreso Correcto de Credenciales</p><p>-Dado que el usuario ha ingresado un correo electrónico y una contraseña válidos.</p><p>-Cuando el usuario hace clic en "Iniciar Sesión".</p><p>-Entonces el sistema valida las credenciales, inicia sesión exitosamente y redirige al usuario a la página principal.</p><p></p><p>Escenario 2: Ingreso Incorrecto de Credenciales</p><p>-Dado que el usuario ha ingresado un correo electrónico o una contraseña incorrectos.</p><p>-Cuando el usuario hace clic en "Iniciar Sesión".</p><p>-Entonces el sistema muestra un mensaje de error indicando que las credenciales son incorrectas y solicita al usuario que vuelva a intentarlo.</p>|EPIC02|
|US10|Recuperación de Contraseña|Como usuario, quiero recuperar mi contraseña si la he olvidado para poder volver a acceder a mi cuenta.|<p>Escenario 1: Envío de Enlace de Recuperación</p><p>-Dado que el usuario ha ingresado un correo electrónico válido asociado con una cuenta.</p><p>-Cuando el usuario presione “he olvidado mi contraseña”.</p><p>-Entonces el sistema envía un correo electrónico con un enlace para restablecer la contraseña y muestra un mensaje de confirmación.</p><p></p><p>Escenario 2: Intento de recuperación repetido</p><p>-Dado que el usuario ha solicitado el enlace de recuperación y el correo ha sido enviado.</p><p>-Cuando el usuario intenta solicitar un nuevo enlace de recuperación utilizando el mismo correo electrónico antes de que el primer enlace haya expirado.</p><p>-Entonces el sistema muestra un mensaje indicando que ya se ha enviado un enlace de recuperación a ese correo electrónico.</p><p></p>|EPIC02|
|US11|Cierre de Sesión Seguro|<p>Como usuario,</p><p>quiero tener la opción de cerrar sesión de manera segura cuando termine de usar la aplicación,</p><p>para proteger mi cuenta.</p>|<p>Escenario 1: Cierre de Sesión desde el Menú de Configuración</p><p>-Dado que el usuario está en la aplicación y ha terminado de usarla.</p><p>-Cuando el usuario selecciona la opción "Cerrar sesión" desde el menú de configuración.</p><p>-Entonces el sistema cierra la sesión del usuario de manera segura y redirigir al usuario a la pantalla de inicio de sesión.</p><p></p><p>Escenario 2: Cierre de Sesión Automático por Inactividad</p><p>-Dado que el usuario presenta un gran periodo de inactividad.</p><p>-Cuando el tiempo de inactividad se cumple,</p><p>-Entonces el sistema cierra la sesión del usuario automáticamente, notificándole que su sesión ha expirado por inactividad.</p>|EPIC02|
|US12|Selección de Punto de Recogida|Como usuario, quiero seleccionar el punto de recogida más conveniente para mí, para poder retirar el vehículo sin problemas.|<p>Escenario 1: Selección de Punto de Recogida Cercano</p><p>-Dado que el usuario necesita un punto de recogida cercano a su ubicación actual.</p><p>-Cuando el usuario accede a la opción de selección de punto de recogida y elige "Usar mi ubicación actual".</p><p>-Entonces el sistema muestra los puntos de recogida más cercanos en un mapa o lista, permitiendo al usuario seleccionar el que prefiera.</p><p></p><p>Escenario 2: Selección de Punto de Recogida por Dirección</p><p>-Dado que el usuario prefiere recoger el vehículo en una ubicación específica, no relacionada con su ubicación actual.</p><p>-Cuando el usuario ingresa manualmente una dirección en la opción de selección de punto de recogida.</p><p>-Entonces el sistema muestra los puntos de recogida más cercanos a la dirección ingresada, permitiendo al usuario elegir el que mejor le convenga.</p><p></p><p>Escenario 3: Punto de Recogida No Disponible</p><p>-Dado que el usuario ha seleccionado un punto de recogida específico que, en este momento, no tiene vehículos disponibles.</p><p>-Cuando el usuario intenta confirmar la selección de ese punto.</p><p>-Entonces el sistema muestra un mensaje informando que no hay vehículos disponibles en ese punto y sugiere puntos de recogida alternativos cercanos.</p>|EPIC03|
|US13|Cambio de Punto de Recogida|Como usuario, quiero cambiar el punto de recogida antes de la hora programada, Por si ocurre un inconveniente.|<p>Escenario 1: Cambio de Punto de Recogida con Tiempo Suficiente</p><p>-Dado que el usuario ha seleccionado un punto de recogida inicial y desea cambiarlo con suficiente antelación antes de la hora programada.</p><p>-Cuando el usuario accede a la opción de modificar la reserva y elige un nuevo punto de recogida.</p><p>-Entonces el sistema realiza el cambio sin cargos adicionales, actualiza la reserva con el nuevo punto de recogida, y envía una confirmación al usuario.</p><p></p><p>Escenario 2: Cancelación del Cambio de Punto de Recogida</p><p>-Dado que el usuario ha iniciado el proceso de cambio de punto de recogida, pero cambia de opinión antes de confirmar.</p><p>-Cuando el usuario decide cancelar el cambio y mantener el punto de recogida original.</p><p>-Entonces el sistema restablece la reserva al estado original sin aplicar ningún cambio y muestra una confirmación de que el punto de recogida original ha sido mantenido.</p>|EPIC03|
|US14|Selección de Punto de Devolución|Como usuario, quiero seleccionar el punto de devolución más cercano, para poder devolver el vehículo de manera eficiente.|<p>Escenario 1: Selección de Punto de Devolución Cercano a la Ubicación Actual</p><p>-Dado que el usuario desea devolver el vehículo en un punto cercano a su ubicación actual.</p><p>-Cuando el usuario accede a la opción de seleccionar un punto de devolución y elige "Usar mi ubicación actual".</p><p>-Entonces el sistema muestra los puntos de devolución más cercanos, permitiendo al usuario seleccionar el más conveniente. </p><p></p><p>Escenario 2: Punto de Devolución Fuera del Horario de Operación</p><p>-Dado que el usuario ha seleccionado un punto de devolución que no estará operativo en el horario previsto.</p><p>-Cuando el usuario intenta confirmar la devolución en ese punto fuera del horario de operación.</p><p>-Entonces el sistema informa sobre el horario y sugiere puntos alternativos o la opción de cambiar la hora de la devolución.</p>|EPIC03|
|US15|Recogida a Domicilio|Como usuario, quiero solicitar que el vehículo sea entregado en mi domicilio para mayor comodidad.|<p>Escenario 1: Confirmación de Recogida a Domicilio</p><p>-Dado que el usuario desea que el vehículo sea entregado en su domicilio.</p><p>-Cuando el usuario ingresa su dirección y selecciona la opción de entrega a domicilio.</p><p>-Entonces el sistema verifica la disponibilidad del servicio en esa ubicación y confirma la hora y fecha de entrega, mostrando un mensaje de confirmación con todos los detalles.</p><p></p><p>Escenario 2: Modificación de la Hora de Entrega a Domicilio</p><p>-Dado que el usuario necesita ajustar la hora de entrega del vehículo en su domicilio.</p><p>-Cuando el usuario modifica la hora o fecha de entrega a través de la aplicación.</p><p>-Entonces el sistema verifica la disponibilidad de la nueva hora solicitada y confirma el cambio, actualizando los detalles de la reserva y enviando una notificación al usuario con la nueva hora de entrega.</p><p></p>|EPIC03|
|US16|Chequeo del Vehículo Antes de Recogida|<p>Como usuario,</p><p>quiero recibir un informe de chequeo del vehículo antes de recogerlo,</p><p>para asegurarme de que está en condiciones óptimas y conocer cualquier detalle relevante antes de utilizarlo.</p>|<p>Escenario 1: Informe Vía Aplicación</p><p>-Dado que el usuario ha reservado un vehículo.</p><p>-Cuando se acerca a la recogida, el sistema envía un informe de chequeo del vehículo por la aplicación.</p><p>-Entonces el usuario revisa el estado actual del vehículo, incluyendo cualquier daño previo.</p><p></p><p>Escenario 2: Informe por Correo Electrónico</p><p>-Dado que el usuario prefiere recibir notificaciones por correo.</p><p>-Cuando el informe está listo.</p><p>-Entonces el sistema envía el informe al correo electrónico del usuario.</p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p>|EPIC03|
|US17|Escribir Comentarios sobre el Vehículo Alquilado|<p>Como usuario,</p><p>quiero poder escribir y publicar comentarios sobre el vehículo que he alquilado,</p><p>para compartir mi experiencia con otros usuarios.</p>|<p>Escenario 1: Publicación de Comentario Después del Alquiler</p><p>-Dado que el usuario ha completado su alquiler.</p><p>-Cuando el usuario accede a la sección de comentarios en la aplicación y escribe una reseña sobre el vehículo.</p><p>-Entonces el sistema permite al usuario publicar el comentario y lo asocia automáticamente con el vehículo alquilado.</p><p></p><p>Escenario 2: Edición de un Comentario Publicado</p><p>-Dado que el usuario ha publicado un comentario, pero desea modificarlo.</p><p>-Cuando el usuario accede a la sección de comentarios y selecciona la opción de editar.</p><p>-Entonces el sistema permite al usuario realizar cambios en su comentario y actualizarlo, manteniendo la visibilidad para otros usuarios.</p><p>Escenario 3:<br>Borrado de Comentario por Incumplimiento de Reglas</p><p>-Dado que el usuario ha publicado un comentario que no cumple con las normas de la comunidad </p><p>-Cuando el sistema detecta que el comentario infringe las reglas de la comunidad.</p><p>-Entonces el sistema elimina automáticamente el comentario y notifica al usuario sobre la eliminación, explicando las razones.</p>|EPIC04|
|US18|Filtrado de Comentarios por Categoría|<p>Como usuario,</p><p>quiero poder filtrar los comentarios por categorías,</p><p>para enfocarme en los aspectos que más me importan al seleccionar un vehículo.</p>|<p>Escenario 1:</p><p>Filtrado por Categoría Específica</p><p>-Dado que el usuario está en la sección de comentarios de un vehículo,</p><p>-Cuando el usuario selecciona la categoría "Comodidad" en el filtro de categorías.</p><p>-Entonces el sistema muestra únicamente los comentarios que mencionan aspectos relacionados con la comodidad del vehículo.</p><p></p><p>Escenario 2:</p><p>Filtrado por Múltiples Categorías</p><p>-Dado que el usuario está en la sección de comentarios de un vehículo,</p><p>-Cuando el usuario selecciona las categorías "Consumo de Combustible" y "Estado del Vehículo" en el filtro de categorías.</p><p>-Entonces el sistema muestra todos los comentarios que mencionan al menos una de las categorías seleccionadas.</p><p></p><p>Escenario 3: Eliminación de Filtros</p><p>-Dado que el usuario está en la sección de comentarios de un vehículo y ha aplicado un filtro por categoría,</p><p>-Cuando el usuario decide eliminar el filtro.</p><p>-Entonces el sistema muestra todos los comentarios del vehículo sin aplicar ningún filtro.</p><p></p>|EPIC04|
|US19|Valorar los comentarios de Otros Usuarios|<p>Como usuario,</p><p>Quiero poder valorar los comentarios de otros usuarios como útiles o no útiles,</p><p>Para ayudar a destacar los comentarios más relevantes para otros usuarios.</p>|<p>Escenario 1: Valorar un Comentario positivamente</p><p>-Dado que el usuario está navegando en la sección de comentarios de un vehículo.</p><p>-Cuando el usuario encuentra un comentario que considera útil y hace clic en el botón de “Like”.</p><p>-Entonces el sistema registra la valoración e incrementar el contador de "Likes" para ese comentario.</p><p></p><p>Escenario 2: Denunciar un Comentario como Inapropiado</p><p>-Dado que el usuario está en la sección de comentarios de un vehículo,</p><p>-Cuando el usuario encuentra un comentario ofensivo o que contiene información falsa y decide denunciarlo,</p><p>-Entonces el sistema registra la denuncia, y enviar una alerta al equipo de moderación para que revise el comentario.</p>|EPIC04|
|US20|Búsqueda por Ubicación Actual|<p>Como usuario,</p><p>quiero buscar vehículos disponibles cerca de mi ubicación actual, para encontrar rápidamente opciones convenientes.</p>|<p>Escenario 1: Activar Ubicación y Buscar Vehículos</p><p>-Dado que el usuario ha activado la opción de compartir su ubicación en la aplicación.</p><p>-Cuando el usuario realiza una búsqueda de vehículos cerca de su ubicación actual.</p><p>-Entonces el sistema usa la ubicación actual del usuario para mostrar una lista de vehículos disponibles cercanos.</p><p></p><p>Escenario 2: Ubicación Actual No Disponible</p><p>-Dado que el usuario ha desactivado la opción de compartir su ubicación y no ha proporcionado manualmente su ubicación.</p><p>-Cuando el usuario intenta buscar vehículos cerca de su ubicación actual.</p><p>-Entonces el sistema muestra un mensaje informando que la búsqueda de vehículos requiere la activación de la ubicación y proporcionar opciones para activar la ubicación o ingresar una ubicación manualmente.</p>|EPIC05|
|US21|Filtrar Vehículos por Tipo|<p>Como usuario,</p><p>quiero filtrar los vehículos por tipo,</p><p>para encontrar el tipo de vehículo que mejor se adapte a mis necesidades.</p>|<p>Escenario 1: Filtrar por Tipo de Vehículo Específico</p><p>-Dado que el usuario está en la página de búsqueda de vehículos,</p><p>-Cuando el usuario selecciona un tipo específico de vehículo en el filtro de tipos de vehículos,</p><p>-Entonces el sistema muestra solo los vehículos que coinciden con el tipo seleccionado, actualizando la lista de resultados en consecuencia.</p><p></p><p>Escenario 2: Selección Múltiple de Tipos de Vehículo</p><p>-Dado que el usuario desea ver varios tipos de vehículos,</p><p>-Cuando el usuario selecciona múltiples tipos de vehículos el filtro de tipos.</p><p>-Entonces el sistema muestra vehículos que coincidan con cualquiera de los tipos seleccionados, combinando los resultados en la lista.</p><p></p><p>Escenario 3: Restablecer Filtros de Tipo de Vehículo</p><p>-Dado que el usuario ha aplicado un filtro de tipo de vehículo,</p><p>-Cuando el usuario elige restablecer los filtros,</p><p>-Entonces el sistema elimina todos los filtros aplicados, incluyendo el tipo de vehículo, y mostrar la lista completa de vehículos disponibles.</p>|EPIC05|
|US22|Seleccionar Vehículo por Rango de Precio|<p>Como usuario,</p><p>Quiero seleccionar un rango de precio para los vehículos,</p><p>para limitar la búsqueda a opciones que se ajusten a mi presupuesto.</p>|<p>Escenario 1: Selección de un Rango de Precio Específico</p><p>-Dado que el usuario está en la página de búsqueda de vehículos,</p><p>-Cuando el usuario selecciona un rango de precio específico (en el filtro de precios.</p><p>-Entonces el sistema muestra solo los vehículos cuyo precio se encuentra dentro del rango seleccionado.</p><p></p><p>Escenario 2: Sin Resultados en Rango de Precio</p><p>-Dado que el usuario ha seleccionado un rango de precio que no incluye ningún vehículo disponible.</p><p>-Cuando el sistema no puede encontrar vehículos dentro del rango de precio especificado.</p><p>-Entonces el sistema muestra un mensaje informando que no hay vehículos disponibles dentro del rango de precio seleccionado y ofrece opciones para ajustar el rango o buscar otros criterios.</p><p></p>|EPIC05|
|US23|Buscar Vehículos por Marca y Modelo|<p>Como usuario,</p><p>quiero buscar vehículos por marca y modelo específicos,</p><p>para encontrar opciones que cumplan con mis preferencias.</p>|<p>Escenario 1: Búsqueda por Marca y Modelo Específicos</p><p>-Dado que el usuario está en la página de búsqueda de vehículos,</p><p>-Cuando el usuario ingresa una marca y un modelo específicos en los campos de búsqueda.</p><p>-Entonces el sistema muestra solo los vehículos que coinciden con la marca y el modelo ingresados.</p><p></p><p>Escenario 2: Selección de Marca y Modelo en Menú Desplegable</p><p>-Dado que el usuario está en la página de búsqueda de vehículos.</p><p>-Cuando el usuario selecciona una marca y un modelo específicos a partir de menús desplegables.</p><p>-Entonces el sistema muestra solo los vehículos que coinciden con la marca y el modelo seleccionados en los menús desplegables.</p>|EPIC05|
|US24|Filtrar Vehículos con Ofertas Especiales|<p>Como usuario,</p><p>quiero filtrar vehículos que tengan ofertas,</p><p>para aprovechar promociones y ahorrar en mi alquiler.</p>|<p>Escenario 1: Filtrar Vehículos por Fecha de Validez de la Oferta</p><p>-Dado que el usuario está en la página de búsqueda de vehículos.</p><p>-Cuando el usuario selecciona el filtro para mostrar vehículos con ofertas especiales y especifica un rango de fechas.</p><p>-Entonces el sistema muestra solo los vehículos con ofertas especiales que son válidas dentro del rango de fechas especificado.</p><p></p><p>Escenario 2: Filtrar Vehículos por Porcentaje de Descuento</p><p>-Dado que el usuario está en la página de búsqueda de vehículos.</p><p>-Cuando el usuario selecciona el filtro para mostrar vehículos con ofertas especiales y especifica un porcentaje de descuento mínimo.</p><p>-Entonces el sistema muestra solo los vehículos con ofertas especiales que incluyen un descuento igual o mayor al porcentaje especificado.</p><p></p>|EPIC05|
|US25|Seleccionar Fecha y Hora de Inicio del Alquiler|<p>Como usuario,</p><p>quiero seleccionar la fecha y hora de inicio del alquiler del vehículo,</p><p>para asegurarme de que el vehículo esté disponible a partir del momento que lo necesite.</p>|<p>Escenario 1: Selección de Fecha y Hora de Inicio del Alquiler</p><p>Dado que el usuario ha seleccionado un vehículo para alquilar,</p><p>cuando el usuario accede a la página de selección de fecha y hora de inicio del alquiler,</p><p>entonces el sistema debe mostrar un calendario para ingresar la hora de inicio, permitiendo al usuario seleccionar la fecha y la hora deseada.</p><p></p><p>Escenario 2: Error en la Selección de Fecha y Hora</p><p>-Dado que el usuario ha ingresado una fecha y hora de inicio que no es válida.</p><p>-Cuando el usuario intenta proceder con la selección.</p><p>-Entonces el sistema debe mostrar un mensaje de error y solicitar al usuario que ingrese una fecha y hora válidas.</p>|EPIC06|
|US26|Extender la Duración del Alquiler|<p>Como usuario,</p><p>quiero extender la duración del alquiler del vehículo si necesito más tiempo,</p><p>para evitar problemas si mi planificación cambia y mantener el vehículo por más tiempo.</p>|<p>Escenario 1: Solicitar Extensión de Alquiler</p><p>-Dado que el usuario tiene un alquiler en curso y desea extenderlo.</p><p>-Cuando el usuario accede a la opción de "Extender Duración" en la aplicación,</p><p>-Entonces el sistema debe permitir al usuario ingresar una nueva fecha y hora de devolución y mostrar la disponibilidad del vehículo para el período extendido.</p><p></p><p>Escenario 2: Rechazo de Solicitud de Extensión</p><p>-Dado que el usuario ha solicitado una extensión y el vehículo no está disponible para el período adicional.</p><p>-Cuando el usuario recibe la notificación de rechazo.</p><p>-Entonces el sistema ofrece opciones alternativas, como la posibilidad de devolver el vehículo y alquilar uno nuevo.</p><p></p>|EPIC06|
|US27|Reducir la Duración del Alquiler|<p>Como usuario,</p><p>quiero reducir la duración del alquiler del vehículo si termino antes de lo previsto,</p><p>Para evitar cargos innecesarios.</p>|<p>Escenario 1: Solicitar Reducción de Duración</p><p>-Dado que el usuario tiene un alquiler en curso y desea reducir la duración.</p><p>-Cuando el usuario accede a la opción de "Reducir Duración" en la aplicación.</p><p>-Entonces el sistema permite al usuario ingresar una nueva fecha y hora de devolución y mostrar la disponibilidad del vehículo para el período ajustado.</p><p></p><p>Escenario 2: Cancelación de Reducción de Duración</p><p>-Dado que el usuario ha solicitado reducir la duración y luego decide cancelar la reducción,</p><p>-Cuando el usuario solicita cancelar la reducción de duración a través de la aplicación,</p><p>-Entonces el sistema revierte la reducción y restablecer la fecha y hora original de devolución, actualizando el costo de la reserva si corresponde.</p>|EPIC06|
|US28|Gestión de Disponibilidad de Vehículos|<p>Como administrador de una empresa de vehículos,</p><p>quiero gestionar la disponibilidad de mis vehículos en la aplicación,</p><p>para asegurar que solo los vehículos que están listos para alquilar se muestren a los usuarios.</p>|<p>Escenario 1: Marcar un Vehículo como Disponible</p><p>-Dado que soy una empresa de vehículos con acceso a la aplicación.</p><p>-Cuando un vehículo en mi flota ha pasado todas las inspecciones y está listo para alquilarse.</p><p>-Entonces puedo marcar el vehículo como disponible en la aplicación para que los usuarios puedan verlo y alquilarlo.</p><p></p><p>Escenario 2: Marcar un Vehículo como No Disponible</p><p>-Dado que un vehículo de mi flota necesita mantenimiento o está reservado para otro uso.</p><p>-Cuando quiero asegurarme de que no se muestre en la lista de vehículos disponibles,</p><p>Entonces puedo marcar el vehículo como no disponible en la aplicación para que los usuarios no puedan alquilarlo.</p>|EPIC07|
|US29|Registro y Monitoreo de Daños en Vehículos|<p>Como administrador de una empresa de vehículos,</p><p>quiero poder registrar daños y verificar el estado del vehículo después de cada alquiler,</p><p>para comunicarme con el cliente si es necesario y tomar acciones correctivas.</p>|<p>Escenario 1: Registro de Daños al Devolver el Vehículo</p><p>-Dado que un cliente ha devuelto un vehículo después de un alquiler.</p><p>-Cuando se realiza una inspección del vehículo y se presenta daños.</p><p>-Entonces puedo registrar cualquier daño encontrado en la aplicación, adjuntando fotos y detalles sobre la ubicación y naturaleza del daño.</p><p></p><p>Escenario 2: Notificación Automática al Cliente sobre Daños</p><p>-Dado que he registrado un daño en un vehículo devuelto,</p><p>-Cuando completo el proceso de registro del daño en la aplicación,</p><p>-Entonces se envía automáticamente una notificación al cliente, informándole del daño encontrado y solicitándole que se ponga en contacto si tiene alguna consulta.</p>|EPIC07|
|US30|Registro de Vehículos |<p>Como administrador de la empresa de vehículos,</p><p>quiero poder registrar vehículos en el sistema,</p><p>para facilitar su gestión.</p>|<p>Escenario 1: Registro de un Nuevo Vehículo con Precios</p><p>-Dado que el administrador está en la sección de registro de vehículos en la aplicación.</p><p>-Cuando selecciona la opción para registrar un nuevo vehículo.</p><p>-Entonces el sistema permite ingresar detalles como el número de matrícula, marca, modelo, año de fabricación, color y los precios asociados.</p><p></p><p>Escenario 2: Actualización de Precios y Datos Generales del Vehículo</p><p>-Dado que el administrador necesita actualizar la información de un vehículo en la aplicación.</p><p>-Cuando accede a la sección de gestión de vehículos.</p><p>-Entonces el sistema muestra una lista de vehículos registrados,</p><p>y cuando el administrador selecciona un vehículo específico para editar,</p><p>entonces el sistema debe permitirle actualizar los datos.</p>|EPIC07|
|US31|Monitoreo en Tiempo Real de Vehículos|<p>Como administrador de la empresa de vehículos,</p><p>quiero monitorear en tiempo real la ubicación y el estado de cada vehículo que tengo en alquiler,</p><p>para asegurarme de que estén disponibles y en buenas condiciones para los clientes.</p>|<p>Escenario 1: Visualización en Tiempo Real de Ubicación</p><p>-Dado que el administrador de la empresa desea monitorear los vehículos.</p><p>-Cuando accede a la sección de monitoreo en la aplicación,</p><p>-Entonces el sistema muestra un mapa con la ubicación en tiempo real de cada vehículo disponible o en uso.</p><p></p><p>Escenario 2: Registro Histórico de Movimientos</p><p>-Dado que el administrador desea revisar el uso de un vehículo.</p><p>-Cuando accede al historial de un vehículo específico.</p><p>-Entonces el sistema muestra un registro de los movimientos y cambios de estado del vehículo durante un período definido.</p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p><p></p>|EPIC07|



### 2.4.3 Impact Mapping

#### Segmento Interesados en alquilar un vehiculo


[![Impact Map](https://i.postimg.cc/wx2HnSGw/impatcampprimer.png)](https://i.postimg.cc/wx2HnSGw/impatcampprimer.png)


#### Segmento Empresas de vehículos que ponen en alquiler sus vehículos

[![Impact Map](https://i.postimg.cc/BnBfMs5S/impactmap2.png)](https://i.postimg.cc/BnBfMs5S/impactmap2.png)


### **2.4.4 Product Backlog**

En este apartado del informe, nos adentramos en el concepto y la relevancia del Product Backlog en la metodología ágil. Descubrimos que el Product Backlog es una lista en constante cambio y priorizada de elementos que representan el trabajo futuro necesario para desarrollar un producto. Analizamos cómo se organiza y prioriza esta lista según el valor y las necesidades del negocio, así como su función esencial en la planificación de sprints y la toma de decisiones estratégicas para el desarrollo ágil de productos.

A continuación, se muestra nuestro Product Backlog elaborado:

**Trello: <https://trello.com/b/RNJMMqSo/product-backlog>** 

![](images/productbacklog.png)


|#Orden|` `User Story Id|Título|Story Points (1/2/3/5/8)|
| :- | :- | :- | :- |
|1|US30|Registro de Vehículos|` `3|
|2|US28|Gestión de Disponibilidad de Vehículos|5|
|3|US20|Búsqueda por Ubicación Actual|8|
|4|US25|Seleccionar Fecha y Hora de Inicio del Alquiler|3|
|5|US23|Buscar Vehículos por Marca y Modelo|5|
|6|US22|Seleccionar Vehículo por Rango de Precio|3|
|7|US24|Filtrar Vehículos con Ofertas Especiales|3|
|8|US21|Filtrar Vehículos por Tipo|3|
|9|US15|Recogida a Domicilio |5|
|10|US31|Monitoreo en Tiempo Real de Vehículos|8|
|11|US02|Actualización de Método de Pago|3|
|12|US07|Registro de Nuevo Usuario|3|
|13|US10|Recuperación de Contraseña|1|
|14|US26|Extender la Duración del Alquiler|3|
|15|US27|Reducir la Duración del Alquiler|3|
|16|US12|Selección de Punto de Recogida|3|
|17|US13|Cambio de Punto de Recogida|3|
|18|US14|Selección de Punto de Devolución|3|
|19|US06|Gestión de Planes|1|
|20|US29|Registro y Monitoreo de Daños en Vehículos|5|
|21|US09|Inicio de Sesión con Correo Electrónico y Contraseña|1|
|22|US17|Escribir Comentarios sobre el Vehículo Alquilado|1|
|23|US08|Desactivar o Eliminar Cuenta|3|
|24|US16|Chequeo del Vehículo Antes de Recogida|5|
|25|US01|Actualización de Información Personal|3|
|26|US18|Filtrado de Comentarios por Categoría|3|
|27|US19|Valorar los comentarios de Otros Usuarios|1|
|28|US11|Cierre de Sesión Seguro|1|
|29|US04|Visualización del Historial de Actividades|5|
|30|US03|Configuración de Preferencias de Notificación|3|
|31|US05|Preferencias de Idioma|1|



## **Conclusiones**
### Conclusiones y Recomendaciones

La administración de flotas de vehículos en la industria de alquiler presenta desafíos importantes como el mantenimiento, la gestión de reparaciones y la optimización de la rotación para maximizar la rentabilidad. Estos factores son esenciales, ya que la rentabilidad depende de la tasa de utilización, los costos de mantenimiento y la depreciación de los vehículos. Una gestión eficiente en estos aspectos es clave para el éxito del negocio.

La aplicación móvil "Gotta Go Fast" se perfila como una solución innovadora para superar las deficiencias del proceso tradicional de alquiler de autos, que suele ser complejo y poco transparente. Esta herramienta promete mejorar la experiencia del usuario al simplificar el proceso de reserva, garantizar la transparencia en los precios y asegurar la disponibilidad en tiempo real, transformando la manera en que se gestiona la renta de vehículos.

Se recomienda implementar funciones adicionales en "Gotta Go Fast" como un sistema de mantenimiento predictivo para anticipar reparaciones, personalización del servicio al cliente para aumentar la lealtad y algoritmos de optimización de rotación para maximizar la rentabilidad. Además, expandir la cobertura geográfica podría captar mercados desatendidos, ampliando el alcance y el impacto de la aplicación.

### Video App Validation
### Video About the product
### Video About the team

## **Glosario**

- User (usuario): Persona que utiliza la aplicación, ya sea para alquilar un vehículo o gestionar un alquiler. Los usuarios pueden ser clientes individuales o empresas que requieren servicios de alquiler.
- Rental Agreement (contrato de alquiler): Documento digital que detalla los términos y condiciones del alquiler de un vehículo, incluyendo la duración del alquiler, el precio, las políticas de seguro y las restricciones de uso.
- Vehicle (vehículo): Cualquier automóvil disponible para alquilar a través de la aplicación. Cada vehículo tiene información detallada sobre su tipo, modelo, año de fabricación, estado y disponibilidad.
- Booking (reserva): Proceso de selección y confirmación de un vehículo para alquilar durante un período específico. La reserva incluye la selección del vehículo, la duración del alquiler y las opciones de seguro.
- Customer Support (soporte al cliente): Servicio de asistencia para usuarios que enfrentan problemas o tienen consultas sobre el uso de la aplicación, procesos de reserva, o detalles de alquiler. Disponible a través de chat en vivo, correo electrónico o teléfono.
- Fleet Management (gestión de flota): Funcionalidad que permite a las empresas gestionar múltiples vehículos disponibles para alquiler, realizar mantenimiento, y monitorear el estado y la ubicación de cada vehículo en tiempo real.
- Corporate Client (cliente corporativo): Empresas o negocios que utilizan la aplicación para alquilar vehículos para sus empleados o para operaciones comerciales. Los clientes corporativos tienen acceso a herramientas de gestión específicas y descuentos por volumen.
- Insurance Options (opciones de seguro): Diferentes planes de seguro que los usuarios pueden seleccionar al alquilar un vehículo, que cubren desde daños menores hasta cobertura total en caso de accidentes.
- Pick-Up and Drop-Off Points (puntos de recogida y entrega): Ubicaciones designadas donde los usuarios pueden recoger y devolver los vehículos alquilados. Estas ubicaciones pueden ser tiendas de alquiler, oficinas, o estacionamientos específicos.
- Vehicle Availability (disponibilidad de vehículos): Información en tiempo real sobre qué vehículos están disponibles para alquilar en un momento dado, considerando la ubicación del usuario y el tiempo de solicitud.
- Customer Feedback (retroalimentación del cliente): Opiniones y comentarios proporcionados por los usuarios después de completar una reserva, utilizados para mejorar continuamente la experiencia del usuario y los servicios ofrecidos.
- Cancellation Policy (política de cancelación): Reglas y condiciones bajo las cuales un usuario puede cancelar una reserva. Incluye detalles sobre reembolsos, cargos por cancelación y plazos para modificaciones.

## **Bibliografía**

- Caguana-Tonato, Y., Luna-Carrillo, N., Atiaja-Freire, M., & Carrill-Rosero, D. (2022). Servicio de transporte turístico y las expectativas del viajero. CIENCIAMATRIA, 8(4), 1116-1127. https://doi.org/10.35381/cm.v8i4.915

- Mantilla Falcón, L. M., Mantilla Falcón, M. S., Polit Chuez, G. M., & Castillo Martínez, D. C. (2022). Estrategias comerciales, personal selling y fidelización de clientes en una pyme de renta de autos. Uniandes Episteme, 9(3), 366–381.
https://revista.uniandes.edu.ec/ojs/index.php/EPISTEME/article/view/2525

- Polanco Graciano, C. A., & Dino Aracena, L. A. (2022). Asistencia digital para rentas de vehículos en República Dominicana: apoyo mediante aplicación móvil (RentaMarketRD) (Doctoral dissertation, Santo Domingo: Universidad Iberoamericana (UNIBE)).
https://repositorio.unibe.edu.do/jspui/handle/123456789/1352

- Polanco Graciano, C. A., & Dino Aracena, L. A. (2022). Asistencia digital para rentas de vehículos en República Dominicana: apoyo mediante aplicación móvil (RentaMarketRD) (Doctoral dissertation, Santo Domingo: Universidad Iberoamericana (UNIBE)).
https://repositorio.pascualbravo.edu.co/handle/pascualbravo/2371

## **Anexos**

