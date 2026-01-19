# Proyecto Web: GEN (Grupo Musical)

Este es el proyecto final que desarrollé el año pasado para poner a prueba mis conocimientos de **HTML y CSS**. El objetivo era crear una web completa y funcional para la banda madrileña **GEN** (Héctor del Valle, Nuria Elosegui, etc.), basándome en su historia real y su EP 'Infinity'.

### 💡 El reto: 0% Programación
Lo más importante de esta web es que **no tiene ni una sola línea de JavaScript**. Mi intención fue demostrar que, conociendo bien las bases del CSS, se puede crear interactividad y dinamismo sin recurrir a scripts externos.

Lo que vas a encontrar aquí es un trabajo "artesanal", hecho a base de muchas horas de vídeos en YouTube, lectura de foros y pruebas de ensayo-error.

### 🛠️ ¿Qué técnicas he utilizado?
Para compensar la ausencia de programación, me apoyé en técnicas de CSS avanzado:

* **Checkbox Hack:** He "programado" la lógica de los formularios y algunos botones usando el estado `:checked` de los inputs. Así conseguí animaciones e interacción solo con estilos.
* **Efectos 3D:** La galería y algunas secciones usan transformaciones 3D (`Card Flip`) para mostrar información al pasar el ratón o pulsar.
* **CSS Moderno y Responsive:** Utilicé la nueva sintaxis de Media Queries (Level 4) para que la web sea totalmente responsive. Se adapta a móviles y tablets de forma fluida.
* **Código Organizado:** Aunque sea CSS puro, no quería un archivo de mil líneas. Dividí los estilos en módulos (`navbar.css`, `colores.css`, `unete.css`...) y los uní todos en un `styles.css` principal mediante `@import`.

### 📂 Estructura del sitio
He intentado mantener una estructura de archivos limpia y fácil de entender:
- `/html`: El esqueleto de las secciones (Quiénes somos, Galería, Únete).
- `/css`: Toda la "maquinaria" visual dividida por componentes.
- `/imagenes`: Recursos gráficos optimizados para la web.
- `index.html`: La puerta de entrada al proyecto.

### Sobre el proyecto
Esta web fue un paso clave en mi formación. Me enseñó que antes de saltar a frameworks o lenguajes de programación complejos, hay que dominar los cimientos. Está subida a Netlify y es el resultado de mi pasión por aprender cómo funcionan las cosas "bajo el capó".

**Autor:** Juan Risueño
