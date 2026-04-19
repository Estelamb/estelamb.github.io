---
layout: ../../layouts/PostLayout.astro
title: "<span class='lang-es block'>Defensa de mi Segundo PFG: IA embebida en Agricultura de Precisión</span><span class='lang-en hidden'>Defense of my Second PFG: Embedded AI in Precision Agriculture</span>"
description: "<span class='lang-es block'>Hoy he presentado mi segundo Proyecto Fin de Grado, esta vez en Ingeniería Electrónica, centrado en el despliegue de modelos de IA en hardware embebido para UAVs.</span><span class='lang-en hidden'>Today I presented my second Bachelor's Thesis, this time in Electronic Engineering, focused on deploying AI models on embedded hardware for UAVs.</span>"
date: "2025-09-19"
---

<div class="lang-es block">

# Defensa de mi Segundo PFG: IA embebida en Agricultura de Precisión

*Defensa del proyecto en la Escuela Técnica Superior de Ingeniería de Sistemas de Telecomunicación (UPM).*

Hoy, **19 de septiembre de 2025**, cierro formalmente mi etapa de Grado defendiendo mi segundo Proyecto Fin de Grado (PFG), correspondiente a la Ingeniería Electrónica de Comunicaciones en la Universidad Politécnica de Madrid (UPM).

Este trabajo, titulado **["Dispositivo para la generación de mapas de prescripción mediante IA embebida en agricultura de precisión"](https://oa.upm.es/90982/)**, ha sido el complemento perfecto a mi formación en telemática, permitiéndome profundizar en el diseño de sistemas hardware autónomos y el procesamiento de IA en el borde.

<img src="/defensa-elec/presentacion-principal.jpeg" alt="Estela Mora Barba posando tras la defensa del PFG de Electrónica" class="w-full max-h-[450px] object-cover rounded-2xl shadow-lg my-8" />

## El reto: Inteligencia Artificial local y autónoma

El objetivo principal fue diseñar e implementar un sistema hardware autónomo basado en un dron (UAV) capaz de capturar imágenes, procesarlas localmente mediante modelos de IA y generar mapas de prescripción en tiempo real. 

A diferencia de las soluciones tradicionales, este sistema no depende de infraestructuras externas o conexión a la nube. Todo el "cerebro" reside en el dispositivo, lo que aumenta drásticamente la autonomía y la capacidad de respuesta en entornos rurales con conectividad limitada.

## El Stack Tecnológico: Hardware y Aceleración

Si en mi anterior PFG el foco fue la arquitectura de gestión, aquí el núcleo ha sido la integración de hardware de alto rendimiento para IA:

* **Hardware de IA:** Integración de aceleradores **Hailo-8 y Hailo-8L** para el procesamiento eficiente de redes neuronales en tiempo real.
* **Sensores:** Uso de cámaras RGB integradas para la captura de datos agrícolas.
* **Middleware:** **ROS2** para la comunicación interna y el control de misiones.
* **Comunicaciones:** Protocolos **gRPC** para servicios internos y **REST** para interacciones externas.
* **Despliegue:** Uso de contenedores **Docker** para garantizar la portabilidad y escalabilidad del software sobre plataformas embebidas.
* **Visualización:** Telemetría y resultados en tiempo real mediante **ThingsBoard**.

## La experiencia de la defensa

<img src="/defensa-elec/exposicion-tribunal.jpeg" alt="Estela Mora Barba durante la exposición al tribunal de electrónica" class="w-full md:w-[45%] md:float-right md:ml-6 mb-6 mt-2 rounded-2xl shadow-lg object-cover max-h-[350px]" />

Presentar este proyecto ha sido un reto técnico fascinante. He podido validar el sistema conforme a la norma ISO/IEC/IEEE 29119:2020, demostrando que el procesamiento embebido es capaz de operar bajo condiciones variables de forma estable.

Los resultados demuestran que es posible utilizar hardware de bajo costo y software de código abierto para crear herramientas de agricultura sostenible, alineadas con los Objetivos de Desarrollo Sostenible (SDG).

## Agradecimientos

Este trabajo marca un hito muy especial para mí. Nada de esto habría sido posible sin el apoyo constante de mi entorno.

Gracias infinitas a mis **padres** y a mi **hermano**, por ser mi pilar incondicional y por enseñarme que con esfuerzo todo se alcanza. 

A **Diego**, por creer en mí en cada paso y ser mi mayor fuente de motivación.

A **David** (el de los 9), gracias por estar ahí en los momentos de mayor presión y ser ese refugio necesario. 

A mis amigos (**Isra, Tito David, Dani, Osvaldo, Hugo, Agus, Fer y Botas**), por las risas y por hacer de esta etapa universitaria algo inolvidable.

A nivel académico, quiero expresar mi sincero agradecimiento al grupo de investigación **GRyS** por su apoyo incalculable. Un agradecimiento muy especial a **Xi Tao** e **Yiting** por brindarme siempre su aliento y apoyo constante; su amabilidad y respaldo han sido esenciales para completar este proyecto, y me siento verdaderamente agradecida de haber tenido a personas tan generosas a mi lado. 

Finalmente, gracias a mi tutor, **Néstor Lucas Martínez**, por su guía y dedicación a lo largo de este camino.

<div class="grid grid-cols-1 sm:grid-cols-2 gap-4 mt-12 mb-4 clear-both">
  <img src="/defensa-elec/celebracion-familia.jpeg" alt="Celebración con familia" class="w-full h-64 md:h-80 object-cover rounded-2xl shadow-md !m-0" />
  <img src="/defensa-elec/celebracion-amigos.jpeg" alt="Celebración con amigos" class="w-full h-64 md:h-80 object-cover rounded-2xl shadow-md !m-0" />
</div>

---

*Si quieres profundizar en los detalles del diseño hardware o los resultados de la IA, puedes consultar la memoria completa en el Archivo Digital de la UPM:* <br><a href="https://oa.upm.es/90982/" target="_blank" class="btn-enlace inline-block mt-4 px-6 py-2.5 bg-blue-600 !text-white font-medium rounded-lg hover:bg-blue-700 transition-colors hover:no-underline shadow-sm">Ver Documento Oficial en UPM</a>

</div>

<div class="lang-en hidden">

# Defense of my Second PFG: Embedded AI in Precision Agriculture

*Project defense at the ETSIST (Technical University of Madrid - UPM).*

Today, **September 19, 2025**, I formally close my undergraduate journey by defending my second Bachelor's Thesis (PFG), this time for the Degree in Electronic Communications Engineering at the Universidad Politécnica de Madrid (UPM).

This project, titled **["Device for generating prescription maps using embedded AI in precision agriculture"](https://oa.upm.es/90982/)**, has been the perfect complement to my telematics background, allowing me to delve into the design of autonomous hardware systems and edge AI processing.

<img src="/defensa-elec/presentacion-principal.jpeg" alt="Estela Mora Barba after the Electronic Engineering defense" class="w-full max-h-[450px] object-cover rounded-2xl shadow-lg my-8" />

## The Challenge: Local and Autonomous Artificial Intelligence

The main objective was to design and implement an autonomous hardware system based on a drone (UAV) capable of capturing images, processing them locally using AI models, and generating prescription maps in real-time.

Unlike traditional solutions, this system does not rely on external infrastructure or cloud connections. The entire "brain" resides within the device, drastically increasing autonomy and responsiveness in rural environments with limited connectivity.

## The Tech Stack: Hardware and Acceleration

While my previous PFG focused on management architecture, the core here was the integration of high-performance hardware for AI:

* **AI Hardware:** Integration of **Hailo-8 and Hailo-8L** accelerators for efficient real-time neural network processing.
* **Sensors:** Use of integrated RGB cameras for agricultural data capture.
* **Middleware:** **ROS2** for internal communication and mission control.
* **Communications:** **gRPC** protocols for internal services and **REST** for external interactions.
* **Deployment:** Use of **Docker** containers to ensure software portability and scalability on embedded platforms.
* **Visualization:** Real-time telemetry and results through **ThingsBoard**.

## The Defense Experience

<img src="/defensa-elec/exposicion-tribunal.jpeg" alt="Estela Mora Barba during the presentation to the tribunal" class="w-full md:w-[45%] md:float-right md:ml-6 mb-6 mt-2 rounded-2xl shadow-lg object-cover max-h-[350px]" />

Presenting this project has been a fascinating technical challenge. I validated the system according to the ISO/IEC/IEEE 29119:2020 standard, demonstrating that embedded processing can operate stably under variable conditions.

The results show that it is possible to use low-cost hardware and open-source software to create sustainable agriculture tools aligned with the Sustainable Development Goals (SDGs).

## Acknowledgments

This work marks a very special milestone for me. None of this would have been possible without the constant support of my loved ones.

Infinite thanks to my **parents** and my **brother**, for being my unconditional pillar and for teaching me that everything is achievable with effort. 

To **Diego**, for believing in me every step of the way and being my greatest source of motivation.

To **David** (the one from the 9s), thank you for being there during the moments of greatest pressure and being that necessary refuge. 

To my friends (**Isra, Tito David, Dani, Osvaldo, Hugo, Agus, Fer, and Botas**), for the laughs and for making this university stage something unforgettable.

On an academic level, I would also like to express my sincere gratitude to the **GRyS** research group for their invaluable support throughout this journey. A special thanks to **Xi Tao** and **Yiting** for always providing constant encouragement and support. Their kindness and backing have been essential for the completion of this project, and I am truly grateful to have had such generous and caring people by my side. 

Finally, thanks to my tutor, **Néstor Lucas Martínez**, for his guidance and dedication throughout this journey.

<div class="grid grid-cols-1 sm:grid-cols-2 gap-4 mt-12 mb-4 clear-both">
  <img src="/defensa-elec/celebracion-familia.jpeg" alt="Celebration with family" class="w-full h-64 md:h-80 object-cover rounded-2xl shadow-md !m-0" />
  <img src="/defensa-elec/celebracion-amigos.jpeg" alt="Celebration with friends" class="w-full h-64 md:h-80 object-cover rounded-2xl shadow-md !m-0" />
</div>

---

*If you want to dive deeper into the hardware design or AI results, you can consult the full thesis in the UPM Digital Archive:* <br><a href="https://oa.upm.es/90982/" target="_blank" class="btn-enlace inline-block mt-4 px-6 py-2.5 bg-blue-600 !text-white font-medium rounded-lg hover:bg-blue-700 transition-colors hover:no-underline shadow-sm">View Official Document at UPM</a>

</div>