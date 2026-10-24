# Raíces Artesanías

Sitio web de una tienda de artesanías desarrollado con HTML5 y CSS3 como parte de la práctica N.º 27 de la asignatura Programación y Plataformas Web.

**Sitio web publicado:** [Raíces Artesanías — Vercel](https://saavedra-jonnathan-artesanias.vercel.app/)

## 1. Datos generales

- **Nombre del proyecto:** Raíces Artesanías
- **Estudiante:** Jonnathan Saavedra
- **Asignatura:** Programación y Plataformas Web
- **Práctica:** N.º 27
- **Temática:** Tienda de artesanías
- **Tecnologías:** HTML5 y CSS3
- **Breakpoint principal:** 900 px

## 2. Descripción del proyecto

Raíces Artesanías es una página web dedicada a presentar productos artesanales. Su propósito es mostrar un catálogo con imágenes, nombres, descripciones y precios, además de proporcionar información sobre la tienda y un formulario de contacto.

El proyecto utiliza HTML5 para estructurar el contenido y CSS3 para definir la presentación visual, la distribución de los componentes y la adaptación a diferentes tamaños de pantalla.

## 3. Características principales

### 3.1. Estructura semántica

La página utiliza elementos semánticos de HTML para organizar el encabezado, la navegación, el contenido principal, las secciones complementarias y el pie de página.

### 3.2. Catálogo de productos

Incluye productos artesanales presentados mediante imágenes, nombres, descripciones y precios.

### 3.3. Tabla de productos

Incorpora una tabla estructurada con encabezados y elementos semánticos para organizar la información de los productos.

### 3.4. Formulario de contacto

Incluye campos etiquetados y validación nativa de HTML. El campo de celular utiliza el atributo `pattern` para restringir la entrada a nueve dígitos.

### 3.5. Campo con datalist

Implementa un campo de entrada asociado a `datalist` para proporcionar sugerencias al usuario.

**Nota:** `datalist` proporciona sugerencias para un campo de entrada; no permite por sí solo seleccionar varias opciones simultáneamente.

### 3.6. Diseño responsive

El diseño utiliza CSS Grid y Flexbox para organizar los componentes. El breakpoint principal se establece en 900 px, donde se reorganizan las áreas del diseño para adaptar la presentación a dispositivos móviles.

### 3.7. Accesibilidad

Se incorporan etiquetas asociadas a los campos del formulario, textos alternativos en las imágenes y un enlace para saltar al contenido principal. También se contemplan indicadores visuales de foco para la navegación mediante teclado.

## 4. Requisitos personalizados de la Ficha 27

- **Temática:** Tienda de artesanías.
- **Campo especial:** Entrada asociada a `datalist`.
- **Breakpoint principal:** 900 px.
- **Distribución:** Uso de `grid-template-areas` en la estructura principal.
- **Adaptación móvil:** Cambio del orden de las áreas del Grid en dispositivos móviles.

## 5. Estructura del proyecto

```text
Saavedra-Jonnathan-Artesanias/
├── assets/
│   ├── images/
│   ├── productos/
│   └── resourses/
├── css/
├── docs/
│   ├── evidencias/
│   ├── auditoria-a-compañero.md
│   ├── auditoria-recibida.md
│   ├── ficha.md
│   └── respuesta.md
├── index.html
└── README.md
```

La carpeta `assets/` contiene los recursos visuales, `css/` contiene los estilos y `docs/` reúne la documentación de la práctica, los informes de auditoría, la respuesta a los hallazgos y las evidencias.

## 6. Auditoría y correcciones

Como parte del laboratorio cruzado, el proyecto fue revisado por otro estudiante. A partir de la auditoría recibida, se realizaron correcciones relacionadas con:

- La organización de las áreas del Grid en dispositivos móviles.
- El desbordamiento horizontal en pantallas pequeñas.
- La navegación mediante teclado y los indicadores de foco.
- La validación del campo de celular.
- La declaración de la familia tipográfica en CSS.

Las decisiones tomadas y las correcciones realizadas se documentan en `docs/respuesta.md`.

## 7. Evidencias

La carpeta `docs/evidencias/` contiene las capturas correspondientes a las pruebas y verificaciones realizadas durante la práctica.

## 8. Publicación

La página está publicada en Vercel y puede consultarse en el siguiente enlace:

**[Visitar Raíces Artesanías](https://saavedra-jonnathan-artesanias.vercel.app/)**

## 9. Autor

**Jonnathan Saavedra**  
Estudiante de Programación y Plataformas Web.
