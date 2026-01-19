# Proyecto Web: GEN (Grupo Musical)

Este es el proyecto final que desarrollé el año pasado para poner a prueba mis conocimientos de **HTML y CSS**. El objetivo era crear una web completa y funcional para la banda madrileña **GEN** (Héctor del Valle, Nuria Elosegui, etc.), basándome en su historia real y su EP 'Infinity'.

### 💡 El reto: 0% Programación
Lo más importante de esta web es que **no tiene ni una sola línea de JavaScript**. Mi intención fue demostrar que, conociendo bien las bases del CSS, se puede crear interactividad y dinamismo sin recurrir a scripts externos. Es un trabajo "artesanal", hecho a base de muchas horas de investigación, vídeos y pruebas de ensayo-error.

### 🏗️ Arquitectura de Estilos: Pensando en el equipo
Una de las decisiones de las que más orgulloso estoy es la organización del código. No quería el típico archivo gigante de miles de líneas donde es imposible encontrar nada. 

He dividido el CSS en **módulos independientes** (`navbar.css`, `aside.css`, `colores.css`, `unete.css`, etc.) que luego cargo en un `styles.css` principal. Lo hice por tres razones claras:
1. **Escalabilidad:** Si mañana la web crece, es tan fácil como añadir un archivo nuevo sin tocar los demás.
2. **Mantenibilidad:** Si quiero cambiar un color o un margen, voy directo al grano.
3. **Trabajo en equipo:** Está pensado para que, si entrara otro compañero al proyecto, pudiera entender la estructura al momento y trabajar en una sección sin pisar mi código.

### 🛠️ ¿Qué técnicas he utilizado?
Para compensar la falta de programación, exprimí el CSS al máximo:

* **Checkbox Hack:** He "programado" la lógica de los formularios y botones usando el estado `:checked` de los inputs para disparar animaciones.
* **Efectos 3D:** La galería y las biografías usan transformaciones 3D (`Card Flip`) para mostrar contenido extra de forma visual.
* **CSS Moderno y Responsive:** He usado la nueva sintaxis de Media Queries (Level 4) para que la web sea totalmente adaptativa y se vea bien en cualquier móvil o tablet.

### 📂 Estructura del repositorio
- `/html`: El esqueleto de las secciones.
- `/css`: Toda la "maquinaria" visual dividida de forma limpia.
- `/imagenes`: Recursos gráficos del grupo.
- `index.html`: Punto de entrada al proyecto.

### Sobre el autor
Este proyecto fue un paso clave en mi formación como ASIR. Me enseñó que antes de usar herramientas automáticas, hay que dominar los cimientos y escribir código que sea limpio y fácil de leer para otros.

**Juan Risueño**
