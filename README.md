﻿![upcLogo.png](images/upcLogo.png)

**Universidad Peruana de Ciencias Aplicadas**

Ingeniería de software

Desarrollo de Aplicaciones Móviles - 6° Ciclo

SW61

**Informe del Trabajo Final**

Mayta Guillermo, Jorge Luis

#NOmbreStartup

*“GottaGoFast”*




|            **Integrantes**            |**Código**|
|:-------------------------------------:| :-: |
|    Christian Renato Espinoza Saenz    |U202213208|
|Julio Esteban Elsner De La Torre Ugarte|u202111654|
|    Joaquin David Rivadeneyra Ramos    |U202211846|
|  Alvaro Felipe Pinto Fuentes Rivera   |U202213384|
|    Serrano Ircañaupa, Nelson Elías    |<p>U202214733</p><p></p>|



Agosto de 2024-02

**Registro de Versiones del Informe**
**


| **Versión** |**Fecha**|**Autor**|                        **Descripción de modificación**                         |
|:-----------:| :-: | :-: |:------------------------------------------------------------------------------:|
|     TB1     |||                                           |
|     TB1     |||                                      |


**Student Outcome**

## **Capítulo I: Presentación**

### **1.1. Startup Profile**


#### **1.1.1. Descripción de la Startup**

AutoRentify es una startup dedicada a revolucionar la manera en que las personas alquilan vehículos. A través de nuestra aplicación móvil, ofrecemos una experiencia de alquiler ágil, segura y accesible, adaptada a las necesidades modernas. Nuestra plataforma conecta a usuarios con una amplia red de proveedores de autos, garantizando una amplia variedad de opciones y precios competitivos. AutoRentify se enfoca en la simplicidad y la eficiencia, eliminando las complicaciones tradicionales del proceso de alquiler y brindando a los usuarios control total desde la palma de su mano.

**Misión:**  
Facilitar el acceso a una experiencia de alquiler de autos rápida, confiable y personalizada mediante el uso de tecnología innovadora. Nuestro objetivo es empoderar a los usuarios con una plataforma intuitiva que les permita encontrar y alquilar el vehículo perfecto para sus necesidades de manera eficiente, desde cualquier lugar y en cualquier momento.

**Visión:**  
Convertirnos en la plataforma líder en alquiler de autos, redefiniendo la industria con un enfoque en la conveniencia y la transparencia. Aspiramos a construir una comunidad global de usuarios satisfechos que confían en AutoRentify para todas sus necesidades de movilidad, promoviendo al mismo tiempo un modelo de negocio sostenible y tecnológicamente avanzado.

#### **1.1.2. Perfiles de integrantes del equipo**


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

## **Capítulo II: Needfinding**

En nuestro análisis de los segmentos objetivos, hemos identificado las siguientes necesidades principales que deben ser resueltos:

**Segmento 1: **


**Segmento 2: **



## **Capítulo III: Architecture**


## **Capítulo IV: Backend Product Implementation & Validation**


## **Capítulo V: Product Implementation & Validation



## **Conclusiones**

### Conclusiones y Recomendaciones
### Video App Validation
### Video About the product
### Video About the team

## **Glosario**

## **Bibliografía**


## **Anexos**

