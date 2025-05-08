![alt text](https://via.placeholder.com/800x450.png?text=Zen+ERD+v0.2.2+Interfaz+Principal)

(Reemplaza esta URL con una captura de pantalla principal de Zen ERD v0.2.2)
Zen ERD es una herramienta de diagramación Entidad-Relación (ERD) ligera, 100% standalone y de código abierto que funciona directamente en tu navegador web. Construida con HTML, CSS y JavaScript puro (Vanilla JS), no requiere instalación, dependencias externas ni conexión a internet para su uso básico. ¡Descarga un solo archivo y empieza a diseñar!
Diseñada para ser simple, rápida y accesible, Zen ERD te permite crear, visualizar y modificar diagramas ER básicos de forma intuitiva. Es perfecta para estudiantes, desarrolladores que necesitan un boceto rápido de bases de datos o cualquiera que busque una solución ERD sin complicaciones.
🔗 Prueba Zen ERD v0.2.2 en Vivo!
✨ Características Clave (v0.2.2)
✅ Totalmente Standalone: Funciona con un único archivo HTML. Descarga y abre en tu navegador. ¡Ideal para uso offline!
🎨 Interfaz de Usuario Personalizable:
Temas: Soporte para tema Claro y Oscuro, persistente.
Escalado de UI: Ajusta el tamaño general de la interfaz (toolbar, modales, fuentes) para tu comodidad visual.
Posición de la Barra de Herramientas: Coloca la barra donde más te guste (arriba, abajo, izquierda, derecha).
✍️ Creación y Edición Intuitiva:
Añade Entidades, Atributos (Simples, PK, AK) y Relaciones con facilidad.
Conexiones entre entidades mediante arrastrar y soltar desde puntos de conexión.
Menús contextuales (clic derecho) para acciones rápidas sobre elementos o el lienzo.
🖼️ Visualización y Navegación:
Zoom y Paneo: Navega por diagramas grandes con la rueda del ratón, botones o atajos.
Cuadrícula Visual: Activa una cuadrícula de fondo con opción de ajuste para entidades.
Cardinalidades Detalladas: Opción para mostrar/ocultar las cardinalidades originales (ej. (0,n), (1,1)) junto a las líneas de relación.
💾 Gestión de Diagramas:
Guardar/Cargar: Exporta e importa tus diagramas en formato JSON, manteniendo la estructura y la vista.
Exportar a PNG: Genera una imagen de tu diagrama actual para compartir o documentar.
Limpiar Lienzo: Reinicia el espacio de trabajo fácilmente.
⏳ Productividad:
Historial (Undo/Redo): Deshaz y rehaz acciones para corregir errores o explorar ideas.
Información de Selección: La barra de herramientas muestra detalles del elemento seleccionado.
🔧 Configuración Centralizada:
Un único modal de Configuración (🛠️) para acceder a:
Gestor de Addons: Habilita/deshabilita addons embebidos y carga addons externos (.js).
Ayuda: Visualiza los controles principales y atajos de teclado.
Opciones de Visualización: Como el toggle de cardinalidades detalladas.
🧩 Sistema de Addons:
Arquitectura modular para extender funcionalidades.
Addons embebidos actualmente:
Element Counter: Muestra el número de entidades y relaciones en la toolbar.
Relationship Resizer: Permite redimensionar el rombo de las relaciones.
UI Customizer: Gestiona el escalado de UI y la posición de la toolbar.
🛠️ Tecnologías Utilizadas
HTML5: Para la estructura semántica de la página.
CSS3: Para los estilos visuales, utilizando Custom Properties (variables CSS) para temas y la unidad rem para una UI escalable.
JavaScript (Vanilla JS ES6+): Toda la lógica de la aplicación, sin frameworks ni librerías externas.
Canvas API (2D Context): Para el renderizado dinámico del diagrama.
LocalStorage API: Para persistir las preferencias del usuario (tema, estado de addons, cuadrícula, escala de UI, posición de toolbar y visibilidad de cardinalidad detallada).
🚀 Cómo Empezar
Descarga:
Ve a la sección de Releases de este repositorio para descargar la última versión estable del archivo HTML.
O clona este repositorio: git clone https://github.com/JuanJoseJuradoSantos1/Zen-ERD---Herramienta-Minimalista-de-Diagramaci-n-Entidad-Relaci-n-Standalone.git y busca el archivo ProgramDB0.2.2.html (o la versión más reciente).
Abre en tu Navegador:
Simplemente haz doble clic en el archivo HTML descargado, o arrástralo a la ventana de tu navegador web moderno (Chrome, Firefox, Edge, Safari).
¡A Diagramar!
Usa el clic derecho para añadir entidades en el lienzo.
Arrastra desde los puntos de conexión de una entidad a otra para crear relaciones.
Explora los botones de la barra de herramientas y el modal de Configuración (🛠️).
🖼️ Más Capturas de Pantalla
(Aquí puedes añadir más capturas de pantalla mostrando diferentes características o estados. Sube tus imágenes al repositorio, por ejemplo, en una carpeta assets/img/ y enlaza a ellas así: ![](./assets/img/tu_imagen.png))
Modo Oscuro con Cardinalidades Detalladas:
![alt text](https://via.placeholder.com/700x400.png?text=Zen+ERD+-+Modo+Oscuro+Detallado)

(Reemplaza con tu captura)
Modal de Configuración Centralizado:
![alt text](https://via.placeholder.com/600x350.png?text=Zen+ERD+-+Modal+de+Configuración)

(Reemplaza con tu captura)
Gestor de Addons (accesible desde Configuración):
![alt text](https://via.placeholder.com/600x350.png?text=Zen+ERD+-+Gestor+de+Addons)

(Reemplaza con tu captura)
🛣️ Hoja de Ruta / Posibles Mejoras Futuras
Aunque Zen ERD busca la simplicidad, hay algunas ideas para el futuro:
Mejorar la edición de texto directamente en el canvas.
Exportación a formato SVG.
Soporte visual para entidades débiles.
Más tipos de atributos (compuestos, multivaluados).
Paleta de elementos flotante para una creación más rápida.
Opción para nombrar/etiquetar los "saves" del historial.
Más opciones de personalización en el modal de Configuración.
🤝 Contribuciones
¡Las contribuciones son bienvenidas! Si tienes ideas para nuevas características, mejoras, o encuentras algún bug:
Revisa si ya existe un Issue similar.
Si no, abre un nuevo Issue describiendo tu idea o el problema.
Para contribuciones de código, por favor, haz un fork del repositorio, crea una nueva rama para tus cambios y envía un Pull Request.
📜 Licencia
Este proyecto está distribuido bajo la Licencia MIT.
(Puedes añadir un archivo LICENSE con el texto de la licencia MIT si lo deseas).
Zen ERD - Creado con el objetivo de simplificar la diagramación ER.
Desarrollado con Vanilla JS puro para máxima portabilidad y aprendizaje.
