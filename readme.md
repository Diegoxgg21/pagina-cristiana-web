# Acércate a Dios – Página Web Cristiana

## Descripción del proyecto
Este proyecto consiste en el desarrollo de una página web estática con temática cristiana, realizada únicamente con HTML5 y CSS3, como parte de un proyecto académico universitario. El sitio busca compartir mensajes de fe, reflexiones cristianas y versículos bíblicos, manteniendo una estructura semántica clara y un diseño sobrio y coherente.

El proyecto no utiliza backend ni bases de datos y está diseñado para ejecutarse de manera local.

---

## Estructura del proyecto

```
Proyecto/
│
├── index.html
├── nosotros.html
├── reflexiones.html
├── versiculos.html
├── contacto.html
│
├── css/
│   ├── normalize.css
│   └── styles.css
│
├── img/
│   └── iglesia.jpg, iglesia 1.jpg, iglesia 2.jpg, iglesia 3.jpg
```

---

## Tecnologías utilizadas

- **HTML5** (estructura y semántica)
- **CSS3** (estilos y diseño)
- **Google Fonts**
  - Playfair Display (títulos)
  - Open Sans (texto general)

---

## Semántica HTML

Se utilizaron etiquetas semánticas para estructurar correctamente el contenido:

- `<header>`: encabezado principal de cada página
- `<nav>`: barra de navegación
- `<main>`: contenido principal
- `<section>`: agrupación de contenido relacionado
- `<article>`: contenido independiente (reflexiones)
- `<blockquote>`: citas bíblicas y versículos
- `<footer>`: pie de página

Esto mejora la accesibilidad, legibilidad y organización del código.

---

## Diseño y maquetación

### Flexbox
Se utilizó Flexbox principalmente en:
- La barra de navegación (`.navegacion`) para alinear los enlaces horizontalmente.

### CSS Grid
Se utilizó CSS Grid en:
- Sección de reflexiones (tarjetas)
- Sección de contacto (información y formulario)
- Página de versículos (bloques de citas)

---

## Páginas del sitio

### Inicio (`index.html`)
- Presentación general
- Hero principal
- Reflexiones destacadas
- Versículo del día

### Nosotros (`nosotros.html`)
- Misión
- Visión
- Valores cristianos

### Reflexiones (`reflexiones.html`)
- Reflexiones basadas en personajes bíblicos
- Reflexiones de papas y santos
- Diseño en tarjetas con efecto hover

### Versículos (`versiculos.html`)
- Colección de versículos bíblicos
- Uso de `<blockquote>`
- Efectos de transición al pasar el mouse

### Contacto (`contacto.html`)
- Información de contacto
- Formulario visual (sin backend)

---

## Funcionalidad

- Navegación consistente en todas las páginas mediante la barra de navegacion.
- Efectos hover en tarjetas de reflexiones y versículos para mejorar la experiencia de usuario.

---

## Ejecución del proyecto

El proyecto puede ejecutarse de forma local abriendo el archivo `index.html` en un navegador web.

Para facilitar el desarrollo y la visualización de cambios en tiempo real, se recomienda el uso de "Live Server" en Visual Studio Code.

---

## Autor
Desarrollado por Diego André Medina Gonzalez

Proyecto académico desarrollado para fines educativos.

Universidad del Valle de Guatemala campus Sur

