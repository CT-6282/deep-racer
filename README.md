# deep-racer

Realizamos un programa de autoaprendizaje y reconocimiento para un vehículo autónomo a escala y una pista de entrenamiento.
Un vehículo autónomo, es un vehículo sin conductor, debe ser capaz de imitar las capacidades de las personas de conducir, imitando su comportamiento dependiendo del entorno en el que se encuentre.
      El vehículo cuenta con cámaras... (Agregar componentes)
      Módulo 1 - Arquitectura y Programación de Sistemas:

	•	Elegimos lenguajes de programación como Python para implementar la lógica de control y aprendizaje de los vehículos. Python nos permite aprovechar una amplia variedad de bibliotecas y marcos de trabajo relevantes para la inteligencia artificial y el procesamiento de datos en tiempo real.
	•	Utilizamos Redis como base de datos en memoria para almacenar información sobre las carreras, como tiempos de vuelta y rendimiento de los vehículos. Esto permite un acceso rápido a los datos y una gestión eficiente de la información en tiempo real.
	•	Nuestra metodología de programación sigue el enfoque ágil, lo que nos permite adaptarnos rápidamente a los cambios y agregar nuevas características durante el desarrollo.
	•	Aplicamos conceptos de Ingeniería de Software, como el principio de responsabilidad única, para asegurar un diseño modular y mantenible del sistema.
	•	Estructuramos el sistema en módulos para separar la lógica de control, el aprendizaje de la red neuronal y la interacción con el entorno de la pista.

Módulo 2 - Sistemas Inteligentes:

	•	Para cumplir con el requisito de sistemas inteligentes, implementamos una red neuronal profunda (Deep Neural Network, DNN) para el aprendizaje y control del vehículo en la pista.
	•	Utilizamos una arquitectura de red neuronal convolucional (Convolutional Neural Network, CNN) para procesar los datos de los sensores de la cámara en tiempo real y tomar decisiones de control adecuadas.
	•	Nuestro modelo matemático se basa en la retroalimentación constante entre la red neuronal y los datos en tiempo real de los sensores, permitiendo al vehículo aprender y mejorar su rendimiento en cada vuelta.

Módulo 3 - Sistemas Distribuidos:

	•	Implementamos un sistema descentralizado en el que múltiples vehículos en la pista interactúan entre sí para evitar colisiones y competir.
	•	Cada vehículo cuenta con sensores de distancia y visión, permitiéndoles detectar y responder a la presencia de otros vehículos en su entorno.
	•	Establecemos comunicación bidireccional entre los vehículos utilizando protocolos de red estándar, permitiendo la transmisión de datos de posición y velocidad en tiempo real.
	•	Justificamos el uso del protocolo MQTT (Message Queuing Telemetry Transport) debido a su eficiencia en la transmisión de mensajes en un entorno distribuido en tiempo real.
