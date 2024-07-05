# Android Studio:
Recuerda que puedes personalizar el tipo de Activity según tus necesidades (por ejemplo, Empty Activity, Bottom Navigation Activity, etc.)

- Asistente de Android Studio:

    * En el apartado de archivo haz clic derecho en la carpeta donde deseas crear la Activity (por ejemplo, app/src/main/java/com/tu_paquete/).
    * Selecciona New > Activity > Blank Activity.
    * Proporciona un nombre para la clase Java y el archivo de diseño (layout).
    * El asistente generará automáticamente los archivos necesarios y registrará la Activity en el archivo AndroidManifest.xml.

- Manualmente:
    * Crea una nueva clase Java en la ubicación deseada.
    * Extiende la clase de Activity o AppCompatActivity.
    * Implementa el método onCreate y vincula el diseño con setContentView(R.layout.tu_layout).
    * No olvides declarar la Activity en el archivo AndroidManifest.xml.

## Creando en nuestro Activitie 

Crear un botón con una imagen en Android Studio es una tarea útil y visualmente atractiva. 

* Selecciona la imagen adecuada:
    - Elige una imagen clara y relevante para la función del botón. Debe ser preferiblemente de alta resolución.
* Crea un botón en el diseño principal (Activity Main):
    - Arrastra un botón desde la paleta de elementos al diseño principal (activity_main.xml).
    - Asigna un ID único al botón en la sección de atributos (Declared Attributes).
* Agrega la imagen al botón:
    - Abre tu proyecto en Android Studio.
    - Ve a la carpeta “res” y haz clic con el botón derecho en la carpeta “drawable”.
    - Selecciona “New” y luego “Image Asset”.
    - Elige “Image” como el tipo de recurso.
    - Selecciona la imagen que deseas usar para el botón y haz clic en “Next”.
* Configura el botón:
    - En el archivo MainActivity.java, asigna un OnClickListener al botón.
    - Dentro del OnClickListener, crea un Intent para abrir la nueva actividad (layout) cuando se presione el botón.
    - Asegúrate de que el ID del botón coincida con el que asignaste en el diseño principal.
* Crea la nueva actividad (layout):
    - En el explorador de archivos, expande la carpeta “layout”.
    - Crea un nuevo layout (archivo XML) para la segunda actividad (por ejemplo, Informacion.xml).
    - Diseña la interfaz de la segunda actividad según tus necesidades.
* Inicia la nueva actividad desde el botón:
    - En el OnClickListener, utiliza el Intent para abrir la nueva actividad:

![Activitie](img/01.png)

Ahora tienes un botón con una imagen que abre una segunda actividad en tu aplicación