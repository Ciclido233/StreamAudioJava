StreamAudioJava 🔊

Descripción

Sistema de gestión de contenido audio digital que permite:

- Crear y clasificar canciones y podcasts

- Registrar reproducciones y "me gusta"

- Identificar favoritos según popularidad

- Demostrar herencia y polimorfismo en Java

Estructura del código

src/  

├── modelos/  

│   ├── Audio.java          # Clase padre  

│   ├── Cancion.java        # Implementación específica  

│   ├── Podcast.java        # Implementación específica 

│   └── MisFavoritos.java   # Lógica de recomendaciones  

└── principal/  

    └── Principal.java      # Ejemplo de uso  

Funcionalidades clave

- Herencia: Cancion y Podcast extienden Audio

- Polimorfismo: Sobreescritura de getClasificacion()

- Simulación de interacciones (reproducciones/me gusta)

- Sistema de favoritos basado en popularidad




    
