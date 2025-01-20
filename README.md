# Documentación del Código HTML del Portafolio

## Información General
Este proyecto corresponde a una página de portafolio personal creada en la clase **"HTML y CSS: trabajando con responsividad y publicación de proyectos"** de la unidad **Principiante en Programación G8 - ONE**, como parte de la certificación **ORACLE ONE G8 - INACAP**.

### Propósito del Proyecto
El objetivo del proyecto es presentar el portafolio personal de la desarrolladora **Ana García**, destacando su experiencia como desarrolladora Front-end con especialización en React, HTML y CSS. La página incluye:

- Una introducción profesional.
- Enlaces a redes sociales.
- Un diseño moderno, visualmente atractivo y accesible.

---

## Estructura del Proyecto

### Archivos Principales
- **`index.html`:** Página principal del portafolio.
- **`about.html`:** Página con información detallada sobre Ana García.
- **`styles/style.css`:** Archivo CSS externo para los estilos del portafolio.
- **Carpeta `assets`:** Contiene las imágenes y recursos utilizados.

### Contenido de Cada Archivo
#### `index.html`
La página principal presenta:
- Un encabezado con un menú de navegación.
- Una sección de bienvenida que incluye:
  - Un mensaje destacando los servicios de Ana García.
  - Un listado de enlaces a redes sociales con iconos.
  - Una imagen representativa.

#### `about.html`
La página "Sobre mí" contiene:
- Información sobre la experiencia profesional y habilidades de Ana García.
- Diseño alineado con la página principal.

#### `styles/style.css`
Define el diseño y estilo visual, incluyendo:
- **Variables CSS:** Para colores y tipografía.
- **Diseño Responsivo:** Uso de `flexbox` para adaptarse a diferentes dispositivos.
- **Estilos Personalizados:** Enlaces interactivos y elementos visuales modernos.

---

## Características Técnicas

### Declaración Inicial
```html
<!DOCTYPE html>
<html lang="es-mx">
```
El atributo `lang="es-mx"` establece el idioma principal como español (México).

### `<head>` (Configuraciones Básicas)
1. **Codificación de Caracteres:**
   ```html
   <meta charset="UTF-8">
   ```
2. **Compatibilidad con Navegadores:**
   ```html
   <meta http-equiv="X-UA-Compatible" content="IE=edge">
   ```
3. **Diseño Responsivo:**
   ```html
   <meta name="viewport" content="width=device-width, initial-scale=1.0">
   ```
4. **Enlace a Estilos Externos:**
   ```html
   <link rel="stylesheet" href="styles/style.css">
   ```

### `<body>` (Estructura de Contenido)
1. **Encabezado (`<header>`):**
   - Menú de navegación con enlaces a `index.html` y `about.html`.

2. **Sección Principal (`<main>`):**
   - Un mensaje de bienvenida con elementos destacados (`<strong>`).
   - Enlaces a redes sociales con iconos (GitHub, LinkedIn y Twitch).
   - Una imagen representativa con el atributo `alt`.

3. **Pie de Página (`<footer>`):**
   - Crédito a Alura Latam.

---

## Estilos y Diseño
El archivo `style.css` define:
- **Colores y Tipografía:**
  - Fondo oscuro (`#000000`) con texto claro (`#F6F6F6`).
  - Fuentes importadas: `'Krona One'` y `'Montserrat'`.
- **Diseño Responsivo:**
  - Uso de `flexbox` para una disposición flexible.
- **Interactividad:**
  - Efectos `hover` en enlaces.
  - Bordes redondeados en elementos destacados.

---

## Mejoras Futuras
1. **Navegación:**
   - Expandir el menú para incluir nuevas secciones.
2. **Contenido Adicional:**
   - Agregar un portafolio de proyectos con imágenes y descripciones.
3. **Accesibilidad:**
   - Revisar el contraste y etiquetas `aria` para mayor compatibilidad.
4. **Soporte Multilingüe:**
   - Preparar la página para varios idiomas.
5. **Favicon:**
   - Incluir un ícono representativo en la pestaña del navegador.

---

## Requisitos Técnicos
- **Directorio del Proyecto:**
  - Asegúrate de mantener los archivos `index.html`, `about.html`, y `style.css` en sus respectivas rutas.
- **Recursos de Imagen:**
  - Los archivos en la carpeta `assets` deben estar correctamente enlazados en el código.

---

## Enlaces Relacionados
- [GitHub](https://github.com/)
- [LinkedIn](https://linkedin.com/in/)
- [Twitch](https://twitch.tv/)
