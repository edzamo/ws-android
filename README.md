# Curso de Android: Guía de Ejemplos y Aprendizaje

Este repositorio es una guía completa de ejemplos prácticos para aprender desarrollo de aplicaciones Android desde los fundamentos hasta temas avanzados.

> **Nota:** Aunque el repositorio fue etiquetado inicialmente como Angular, el contenido es 100% desarrollo **Android Nativo**.

---

## 📑 Índice de Contenidos

1. [Introducción a Android](#sección-1-introducción)
2. [Interfaz de Usuario (UI)](#sección-2-iu-android)
3. [Fragments](#sección-3-fragments)
4. [Navegación](#sección-4-navegación)
5. [Listados y Adaptadores](#sección-5-listados)
6. [Almacenamiento de Datos](#sección-6-almacenamiento)
7. [Google Maps](#sección-7-maps)
8. [Consumo de API con Retrofit](#sección-8-retrofit)
9. [Proyecto Final: MecAround](#mecaround)

---

## 📂 Detalle por Secciones

### Sección 1: Introducción
Fundamentos básicos del desarrollo Android.
*   **Hola Mundo:** Primera aplicación y estructura de un proyecto.
*   **Ciclo de Vida:** Gestión de los estados de una Activity (`onCreate`, `onStart`, `onResume`, etc.).
*   **Debug:** Herramientas para depuración de código.
*   **Intents:** Comunicación entre actividades (Intents explícitos e implícitos) y paso de parámetros.

### Sección 2: IU Android
Diseño y maquetación de interfaces.
*   **Layouts:** Uso de `LinearLayout`, `RelativeLayout` y el potente `ConstraintLayout`.
*   **Componentes:** Trabajo con botones, Checkbox y RadioButtons.
*   **Librerías de Imágenes:** Carga eficiente de imágenes desde internet usando **Picasso** y **Glide**.
*   **Vectores:** Implementación de gráficos vectoriales para diferentes densidades de pantalla.

### Sección 3: Fragments
Creación de interfaces modulares y reutilizables.
*   **Tipos de Fragments:** Implementación estática y dinámica.
*   **Comunicación:** Intercambio de datos entre Fragments y Activities mediante interfaces.
*   **Multiscreen:** Adaptación de la interfaz para diferentes orientaciones (Land/Port) y dispositivos (Tablets vs Smartphones).
*   **Dialogs:** Uso de `DialogFragment` para ventanas emergentes personalizadas.

### Sección 4: Navegación
Implementación de patrones de navegación estándar de Android.
*   **Menús:** Menú de opciones y menús contextuales.
*   **Navigation Drawer:** Menú lateral desplegable.
*   **Tabs:** Navegación por pestañas con `TabLayout`.
*   **Scrolling:** Implementación de comportamientos de scroll avanzados (`ScrollingActivity`).

### Sección 5: Listados
Visualización de colecciones de datos.
*   **ListView & GridView:** Listados simples y personalizados.
*   **RecyclerView:** El estándar moderno para listas eficientes y complejas, incluyendo el uso del patrón `ViewHolder`.

### Sección 6: Almacenamiento
Persistencia de datos en el dispositivo.
*   **SharedPreferences:** Guardado de preferencias de usuario sencillas (login, ajustes).
*   **Realm Database:** Introducción y CRUD completo con la base de datos NoSQL **Realm** (Inserción, consulta, edición y borrado).

### Sección 7: Maps
Integración de servicios de geolocalización.
*   **Configuración:** Uso de la API de Google Maps.
*   **Marcadores:** Añadir, personalizar y gestionar eventos en marcadores.
*   **Cámara:** Control del zoom y posición de la cámara.
*   **Formas:** Dibujo de líneas y áreas sobre el mapa.

### Sección 8: Retrofit
Comunicación con servicios externos (Backend).
*   **Modelos:** Mapeo de respuestas JSON a objetos Java/Kotlin.
*   **Interfaces:** Definición de peticiones HTTP (GET, POST, etc.).
*   **Peticiones:** Consumo real de servicios API REST para integrar datos externos en la app.

---

## 🛠️ Proyecto Destacado: MecAround

Dentro de la carpeta `androidCourse/MecAround` y `practicaAndroid`, se encuentra el proyecto **MecAround**. Es una aplicación integradora que combina:
*   Autenticación de usuarios (Login).
*   Listados avanzados de talleres y averías.
*   Localización en mapas de servicios cercanos.
*   Sincronización de datos con un servidor remoto.

---

## 🚀 Cómo empezar
1. Clona el repositorio.
2. Abre **Android Studio**.
3. Selecciona "Open an existing project".
4. Navega hasta la carpeta de la sección o ejemplo específico que desees revisar.
5. Sincroniza con Gradle y ejecuta en un emulador o dispositivo físico.
