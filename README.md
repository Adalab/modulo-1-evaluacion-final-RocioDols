# Módulo 1: Ejercicio de evaluación final

El ejercicio consiste en desarrollar una página web de acuerdo a un diseño dado. Hay que resolver varios puntos:

- Usar Sass.
- Usar flexbox y CSS Grid.
- Usar media queries.
- Resolver algunas interacciones usando transiciones.

---

Maquetación:

- El botón de hamburguesa (en la esquina superior izquierda) debe estar fijo en la parte superior de la pantalla y no debe desaparecer al hacer scroll. El icono de la hamburguesa debe ser un enlace a la página de Adalab. Este menú de hamburguesa no desplega ningún submenú.
- Primer módulo (Anonymous proxy): debe estar maquetado con flexbox y debe ocupar el alto de la ventana del navegador.
- Segundo módulo (Looking Through A Window): se puede maquetar usando las propiedades de CSS que se deseen.
- Tercer módulo (3 Reasons To Purchase): los 3 elementos del listado deben estar maquetados con CSS Grid en todos los tamaños de pantalla.
- Cuarto módulo (Footer): se debe maquetar usando flexbox. Todos los textos de la columna "ARTICLES" y todos los textos de la columna "TWITTER" deben ser enlaces a la página de Adalab.

Interacción:

- El botón de flecha del módulo hero debe enlazar a la sección "3 Reasons To Purchase".
- El botón de flecha del footer debe enlazar al inicio de la página.
- Todos los links del pie deben ir a https://adalab.es.
- En el hover de los botones ("Go" y "3 Reasons To Purchase") se debe incluir una transición que dejamos a vuestra elección (por ejemplo: color, tamaño, etc.).
- BONUS: hacer una pequeña animación en el botón del footer.

---

**Ejemplo de web para móvil, tablet y desktop:**

<table>
  <tr>
    <td>
       
[![mobile.png](https://i.postimg.cc/g0PNyz6Q/mobile.png)](https://postimg.cc/bZ3xpjg9)
    </td>
    <td>
       
[![tablet.png](https://i.postimg.cc/Kv6dVyMr/tablet.png)](https://postimg.cc/w7kfyZF7)   
    </td>
    <td>
       
[![desktop.png](https://i.postimg.cc/g23fbBy9/desktop.png)](https://postimg.cc/185WpBYM)
</td>
  </tr>
</table>

---

**Entrega**

La evaluación solo se considerará terminada cuando:

- Esté publicada en GitHub Pages y esté funcionando, para lo cual tendréis que subir el código, también a la carpeta docs/ del repositorio.
- El enlace a GitHub Pages esté en la página página principal del repositorio, en la parte superior, al lado de la descripción.

**Criterios de evaluación**

_General:_

- Usar una estructura adecuada de ficheros y carpetas para un proyecto web, y enlazar bien los distintos ficheros.
- Uso de control de versiones con ramas para manejar un proyecto de código.

_HTML_

- Tener el código perfectamente indentado
- Crear código HTML con sintaxis correcta, bien estructurado
- Usar etiquetas HTML semánticas adecuadas para cada pieza de contenido

_CSS / Sass_

- Tener el código perfectamente indentado
- Crear código Sass con sintaxis correcta, bien estructurado
- Usar algunas características de Sass como variables, anidación y parciales.
- Usar código CSS que usa de forma intensiva selectores de clase. No usar selectores de etiqueta ni de id
- Usar selectores de clase en inglés
- Usar el modelo de caja de CSS de forma adecuada para especificar tamaño, relleno y márgenes
- Usar estilos de texto y fondo para distintos tipos de elementos.
- Usar flexbox de forma adecuada para organizar elemento en cajas flexibles.
- Usar media queries para que los diseños se ajusten a distintos tamaños de dispositivo
- Usar posicionamiento para emplazar elementos fijos y absolutos en la pantalla.
- Usar CSS grid para emplazar elementos usando una rejilla.
- Usar transiciones CSS para dotar de dinamismo a un proyecto web.

**Instalación**

Instala el proyecto con npm

```bash
  npm install
  npm start
```

**¡Al turrón!**
