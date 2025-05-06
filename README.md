Resumen de la escena

1. Environment
   
   Entorno 3D (suelo, paredes u objetos estáticos).

3. Lighting
   
   Configuración de iluminación global (luces direccionales, reflejos).

5. MR Interaction Setup Variant
   
   Configuraciones específicas para interacciones en MR.

   - Input Action Manager
     
     Gestiona las acciones de entrada (gestos, mandos, voz).
     
     Vincula inputs físicos a eventos en el proyecto (ej: botón "A" = agarrar).

   - XR Interaction Manager
     
     Interacciones: maneja agarres, pulsaciones, rayos interactivos.

   - EventSystem
     
     Sistema de eventos de Unity adaptado para MR (input por mirada/gestos).

   - XR Origin (XR Rig)
     
     Punto central del usuario en MR:
     - Camera Offset
       
       Ajuste de altura/posición de la cámara.
       - Main Camera: Cámara principal con seguimiento de movimiento (headset).
       - Gaze Interactor: Interacción basada en la mirada (para selección).
       - Gaze Stabilized: Suaviza el movimiento del rayo de mirada.
       - Left Controller / Right Controller: Representan mandos físicos o manos virtuales.
       - Left Hand / Right Hand: Modelos 3D de manos.
       - Hand Visualizer: Visualización en tiempo real de gestos.
     - Locomotion
       
	   Contenedor de todos los métodos de movimiento.
     - Hands Smoothing Post Processor
       
       Suaviza el movimiento de las manos para evitar vibraciones.

   - AR Session
     Configuración básica para ARFoundation (si se usa cámara passthrough).

   - Goal Manager
     Gestiona objetivos o misiones.

   - Object Spawner
     Genera objetos dinámicamente (para pruebas o gameplay).

7. UI
   Interfaz de Usuario (UI)

   - Coaching UI
     
     Tutoriales o indicaciones para el usuario.

   - Spatial Panel Manipulator
     
     Paneles flotantes que se pueden mover/redimensionar.

   - Tap Tooltip
     
     Mensajes contextuales.

   - Hand Menu Setup MR Template Variant
     
     Menú rápido activado por gestos.

   - Permissions Manager
     
     Solicita acceso a cámara/micrófono (necesario en Quest o móviles).
