# Sesión 05 - Estructura de aplicaciones y Codificación en Java

La estructura de un proyecto en Android Studio sigue una convención estándar que facilita la organización y navegación del código.

## 🎯 Objetivo

Identificar los módulos que incluye Android cuando creamos un proyecto.

### Módulos

* Módulos de apps para Android : son extensiones o complementos que permiten modificar o añadir funcionalidades al sistema operativo
* Módulos de biblioteca: son componentes que permiten organizar y reutilizar código en proyectos
* Módulos de Google App Engine: son componentes que te permiten integrar tu aplicación de Android con Google App Engine, la plataforma de desarrollo y alojamiento de Google.

Android Studio muestra los archivos de tu proyecto en la vista de proyecto de Android, como se ve en la figura como se ve en la siguiente figura.

![Módulos Android Studio](img/01.png)

* Cada Módulo contiene lo siguiente

1. **manifest**: Contiene el archivo AndroidManifest.xml, que es fundamental para crear una aplicación de Android. Este archivo describe información esencial sobre tu app a las herramientas de compilación de Android, al sistema operativo Android y a Google Play.
    * **Componentes de la app**: Cada componente de la app (como actividades, servicios, receptores de difusión y proveedores de contenido) debe definirse en el archivo de manifiest como se muestra en la siguiente figura.

    ![Módulos Android Studio](img/02.png)

    * **Permisos** El archivo de manifiest también declara los permisos que la app necesita para acceder a partes protegidas del sistema o a otras apps. Además, especifica permisos que otras apps deben tener para acceder al contenido de esta app.

    * **Características de hardware y software**: El manifiest también describe las características de hardware y software que la app requiere, lo que afecta qué dispositivos pueden instalar la app desde Google Play.

2. **java**: contiene el código fuente de tu aplicación, archivos de recursos y configuraciones específicas del nivel del módulo, como el archivo de compilación y el manifiest de Android.
3. **res**: Contiene recursos esenciales para tu aplicación, como layouts, imágenes (drawables), strings, etc.



## Felicidades





## 📝 Organización de la clase

- [Práctica](Practica-01)
- [Presentación - Sesión 03](presentacion/Sesion-05.pptx)