# Proyecto_Modulo_Reconocimiento_de_voz
Este proyecto implementa un sistema de control de un brazo robótico MyCobot 280 M5 mediante comandos de voz en español. La solución combina captura de audio en tiempo real, reconocimiento automático del habla con Google Cloud Speech-to-Text, procesamiento semántico de instrucciones y ejecución segura de movimientos en el robot.
Incluye:

🎤 Integración con un micrófono externo (JBL Quantum Stream Talk) para entrada de voz.

🧠 Módulo de parsing semántico capaz de interpretar órdenes relativas y absolutas sobre las articulaciones.

🤖 Controlador en Python para el robot MyCobot 280 M5, con validación de límites articulares.

🖥️ Interfaz gráfica (Qt/PySide6) para visualización de transcripciones, acciones y estados del robot.

⚙️ Scripts y documentación para la configuración del entorno virtual y gestión de dependencias.

El objetivo principal es demostrar la interacción humano–robot mediante voz en un entorno reproducible, orientado a investigación académica y aplicaciones educativas.
