---
layout: ../../layouts/PostLayout.astro
title: "<span class='lang-es block'>Defensa de mi Primer PFG: Gestión inteligente de UAVs en el Edge</span><span class='lang-en hidden'>Defense of my First PFG: Smart UAV Management at the Edge</span>"
description: "<span class='lang-es block'>Hoy he presentado mi Proyecto Fin de Grado en Ingeniería Telemática sobre gestión de flotas de drones para agricultura de precisión.</span><span class='lang-en hidden'>Today I presented my Bachelor's Thesis in Telematics Engineering on drone fleet management for precision agriculture.</span>"
date: "2025-05-14"
---

<div class="lang-es block">

# Defensa de mi Primer PFG: Gestión inteligente de UAVs en el Edge

*Defensa del proyecto en la Escuela Técnica Superior de Ingeniería de Sistemas de Telecomunicación (UPM).*

Hoy, **14 de mayo de 2025**, marca el cierre de una etapa increíble y el comienzo de otra. Esta mañana he defendido oficialmente mi Proyecto Fin de Grado (PFG) para el Grado en Ingeniería Telemática en la Universidad Politécnica de Madrid (UPM). 

El título del proyecto es largo, pero define exactamente el reto al que me he enfrentado durante estos últimos meses: **["Sistema inteligente de gestión para vehículos autónomos para agricultura de precisión en el edge"](https://oa.upm.es/89100/)**.

<img src="/defensa-tel/presentacion-principal.jpeg" alt="Estela Mora Barba posando tras la defensa del PFG" class="w-full max-h-[450px] object-cover rounded-2xl shadow-lg my-8" />

## El reto: Modernizar la agricultura desde el Edge

La agricultura de precisión necesita automatización, pero depender de la nube centralizada para operar flotas de drones (UAVs) en zonas rurales a menudo introduce latencias inaceptables y problemas de conectividad. 

Mi objetivo con este proyecto era diseñar e implementar un sistema de gestión de flota inteligente basado en **arquitectura edge**. La idea es acercar el procesamiento y la toma de decisiones al lugar donde ocurren los eventos (el campo), mejorando la autonomía, eficiencia y sostenibilidad de las operaciones agrícolas.

Para lograrlo, me apoyé en los modelos de información y flujos de trabajo derivados del proyecto europeo **AFarCloud**, enfocándome en la ejecución autónoma de misiones complejas y la gestión de dependencias entre tareas.

## El Stack Tecnológico

Desde el punto de vista del desarrollo de software y la arquitectura, ha sido un proyecto muy ambicioso. He apostado deliberadamente por herramientas de código abierto para garantizar la replicabilidad del sistema:

* **Arquitectura:** Diseño basado en microservicios distribuidos.
* **Middleware de Robótica:** Uso intensivo de **ROS2** para la comunicación directa y fiable con los UAVs.
* **Comunicaciones internas:** Implementación de **gRPC** como protocolo de alta eficiencia entre microservicios.
* **Integración externa:** API **REST** para la interacción con servicios web de terceros.
* **Persistencia:** **MariaDB** como sistema de gestión de bases de datos.
* **Telemetría y Visualización:** Integración con **ThingsBoard** y **MQTT** para la monitorización en tiempo real del estado de los drones y el progreso de la misión.

## La experiencia de la defensa

<img src="/defensa-tel/exposicion-tribunal.jpeg" alt="Estela Mora Barba durante la exposición al tribunal" class="w-full md:w-[45%] md:float-right md:ml-6 mb-6 mt-2 rounded-2xl shadow-lg object-cover max-h-[350px]" />

Presentar el proyecto ante el tribunal siempre impone respeto, pero cuando confías en el trabajo que has construido línea a línea, los nervios se transforman en ganas de contarlo. 

Durante la presentación, pude demostrar mediante simulaciones en entornos de prueba controlados cómo el sistema es capaz de actualizar dinámicamente el estado de los UAVs y mantener una latencia bajísima gracias a la arquitectura Edge. Los resultados de las pruebas (basadas en la norma ISO/IEC/IEEE 29119:2020) evidenciaron que el sistema es estable, consistente y está listo para su despliegue en escenarios reales.

## Agradecimientos

Este trabajo es el resultado de mucho esfuerzo, pero no habría sido posible sin el apoyo de quienes me rodean. 

Gracias infinitas a mis **padres** y a mi **hermano**, por ser mi pilar, por su amor incondicional y por enseñarme el valor de la perseverancia. 

A **Diego**, por su infinita comprensión y ser mi mayor fuente de calma y motivación constante. 

A **David** (el de los 9), gracias por ser mi refugio cuando más lo necesitaba, por estar presente incluso con horarios imposibles y por no dejar que me hundiera en los momentos de más presión. 

A mis amigos de siempre (**Isra, Tito David y Dani**) y a los que me han acompañado en esta última etapa universitaria (**Osvaldo, Hugo, Agus, Fer y Botas**), por las risas, las charlas eternas y hacer este camino mucho más llevadero.

A nivel académico, quiero agradecer profundamente a mi tutor, **Néstor Lucas Martínez**, por su enorme dedicación, su orientación crítica y, por supuesto, por esas necesarias "Néstor-charlas" que me daban aire cuando más lo necesitaba. 

Finalmente, un agradecimiento muy especial a mis compañeros del grupo de investigación **GRyS** por arroparme y brindarme un entorno inmejorable para crecer profesionalmente.

<div class="grid grid-cols-1 sm:grid-cols-2 gap-4 mt-12 mb-4 clear-both">
  <img src="/defensa-tel/celebracion-familia.jpeg" alt="Celebración con mi familia y pareja" class="w-full h-64 md:h-80 object-cover rounded-2xl shadow-md !m-0" />
  <img src="/defensa-tel/celebracion-amigos.jpeg" alt="Celebración con mis amigos" class="w-full h-64 md:h-80 object-cover rounded-2xl shadow-md !m-0" />
</div>

---

*Si te interesa conocer más detalles técnicos, la arquitectura completa o los resultados de las pruebas, puedes consultar la memoria pública en el Archivo Digital de la UPM:* <br><a href="https://oa.upm.es/89100/" target="_blank" class="btn-enlace inline-block mt-4 px-6 py-2.5 bg-blue-600 !text-white font-medium rounded-lg hover:bg-blue-700 transition-colors hover:no-underline shadow-sm">Ver Documento Oficial en UPM</a>

</div>

<div class="lang-en hidden">

# Defense of my First Bachelor's Thesis: Smart UAV Management at the Edge

*Project defense at the ETSIST (Technical University of Madrid - UPM).*

Today, **May 14, 2025**, marks the end of an incredible stage and the beginning of another. This morning I officially defended my Bachelor's Thesis (PFG) for the Degree in Telematics Engineering at the Universidad Politécnica de Madrid (UPM). 

The project title is long, but it exactly defines the challenge I've faced over the last few months: **["Smart management system for unmanned autonomous vehicles in precision agriculture on edge"](https://oa.upm.es/89100/)**.

<img src="/defensa-tel/presentacion-principal.jpeg" alt="Estela Mora Barba posing after the PFG defense" class="w-full max-h-[450px] object-cover rounded-2xl shadow-lg my-8" />

## The Challenge: Modernizing Agriculture from the Edge

Precision agriculture needs automation, but relying on the centralized cloud to operate drone fleets (UAVs) in rural areas often introduces unacceptable latencies and connectivity issues. 

My goal with this project was to design and implement a smart fleet management system based on **edge architecture**. The idea is to bring processing and decision-making closer to where events occur (the field), improving the autonomy, efficiency, and sustainability of agricultural operations.

To achieve this, I relied on information models and workflows derived from the European **AFarCloud** project, focusing on the autonomous execution of complex missions and the management of dependencies between tasks.

## The Tech Stack

From a software development and architecture standpoint, it has been a highly ambitious project. I deliberately opted for open-source tools to ensure the system's replicability:

* **Architecture:** Design based on distributed microservices.
* **Robotics Middleware:** Intensive use of **ROS2** for direct and reliable communication with UAVs.
* **Internal Communications:** Implementation of **gRPC** as a high-efficiency protocol between microservices.
* **External Integration:** **REST** APIs for interacting with third-party web services.
* **Persistence:** **MariaDB** as the database management system.
* **Telemetry & Visualization:** Integration with **ThingsBoard** and **MQTT** for real-time monitoring of drone status and mission progress.

## The Defense Experience

<img src="/defensa-tel/exposicion-tribunal.jpeg" alt="Estela Mora Barba during the presentation to the tribunal" class="w-full md:w-[45%] md:float-right md:ml-6 mb-6 mt-2 rounded-2xl shadow-lg object-cover max-h-[350px]" />

Presenting the project to the tribunal always commands respect, but when you trust the work you have built line by line, nerves turn into a desire to share it. 

During the presentation, I was able to demonstrate through simulations in controlled test environments how the system dynamically updates UAV states and maintains extremely low latency thanks to the Edge architecture. The test results (based on the ISO/IEC/IEEE 29119:2020 standard) showed that the system is stable, consistent, and ready for deployment in real-world scenarios.

## Acknowledgments

This work is the result of a lot of effort, but it would not have been possible without the support of those around me. 

Infinite thanks to my **parents** and my **brother**, for being my pillar, for their unconditional love, and for teaching me the value of perseverance. 

To **Diego**, for his infinite understanding and for being my greatest source of calm and constant motivation. 

To **David** (the one from the 9s), thank you for being my refuge when I needed it most, for being present even with impossible schedules, and for not letting me sink during moments of highest pressure. 

To my lifelong friends (**Isra, Tito David, and Dani**) and those who accompanied me in this university stage (**Osvaldo, Hugo, Agus, Fer, and Botas**), for the laughs, endless chats, and making this journey much more bearable.

On an academic level, I want to deeply thank my tutor, **Néstor Lucas Martínez**, for his enormous dedication, his critical guidance, and, of course, for those necessary "Néstor-talks" that gave me breathing room when I needed it most. 

Finally, a very special thanks to my colleagues from the **GRyS** research group for welcoming me and providing an unbeatable environment for professional growth.

<div class="grid grid-cols-1 sm:grid-cols-2 gap-4 mt-12 mb-4 clear-both">
  <img src="/defensa-tel/celebracion-familia.jpeg" alt="Celebration with family and partner" class="w-full h-64 md:h-80 object-cover rounded-2xl shadow-md !m-0" />
  <img src="/defensa-tel/celebracion-amigos.jpeg" alt="Celebration with friends" class="w-full h-64 md:h-80 object-cover rounded-2xl shadow-md !m-0" />
</div>

---

*If you are interested in more technical details, the full architecture, or the test results, you can consult the public thesis in the UPM Digital Archive:* <br><a href="https://oa.upm.es/89100/" target="_blank" class="btn-enlace inline-block mt-4 px-6 py-2.5 bg-blue-600 !text-white font-medium rounded-lg hover:bg-blue-700 transition-colors hover:no-underline shadow-sm">View Official Document at UPM</a>

</div>