# Raíces Artesanías

## 1. Datos generales

- **Nombre del proyecto:** Raíces Artesanías
- **Tipo de sitio web:** Página web de una tienda de artesanías
- **Estudiante:** Jonnathan Saavedra
- **Asignatura:** Programación y Plataformas Web
- **Tecnologías utilizadas:** HTML5 y CSS3
- **Práctica:** N.º 27
- **Breakpoint principal:** 900 px
- **Enlace del sitio web:** Añadir la URL de GitHub Pages cuando esté publicada.

## 2. Descripción del proyecto

Raíces Artesanías es una página web dedicada a presentar productos artesanales. Su objetivo es mostrar el catálogo de la tienda mediante imágenes, nombres, descripciones y precios, además de ofrecer información sobre el proyecto y un formulario de contacto.

La página está construida con HTML5 para organizar el contenido y CSS3 para definir su apariencia visual, distribución y adaptación a distintos tamaños de pantalla.

## 3. Características del proyecto

### 3.1. Estructura semántica

El contenido se organiza mediante secciones y elementos semánticos de HTML para facilitar la lectura y la navegación por la página.

### 3.2. Catálogo de productos

El catálogo presenta productos artesanales con imágenes, nombres, descripciones y precios. Las imágenes deben contar con textos alternativos que describan su contenido.

### 3.3. Diseño y presentación visual

La presentación se define mediante CSS. La hoja de estilos organiza los componentes y aplica los colores, espacios, tipografías y distribución visual del sitio.

### 3.4. Diseño adaptable

El diseño contempla el breakpoint principal de 900 px definido para la práctica. En pantallas pequeñas, la distribución debe reorganizarse para que el contenido se pueda consultar sin desplazamiento horizontal.

### 3.5. Búsqueda y formulario

El proyecto incluye un campo de búsqueda con sugerencias mediante `datalist` y un formulario de contacto. `datalist` proporciona sugerencias para un campo de entrada, pero no permite por sí solo seleccionar varias opciones de manera simultánea; este requisito debe comprobarse según la consigna de la práctica.

### 3.6. Accesibilidad

Se deben comprobar los textos alternativos de las imágenes, la asociación entre etiquetas y campos del formulario, la navegación mediante teclado y la visibilidad del foco en los elementos interactivos.

## 4. Aspectos por verificar

- Validación del HTML.
- Validación del CSS.
- Adaptación a diferentes tamaños de pantalla, incluido un ancho de 360 px.
- Ausencia de desplazamiento horizontal no deseado.
- Navegación mediante teclado y foco visible.
- Asociación correcta entre las etiquetas y los campos del formulario.
- Funcionamiento de los enlaces y del campo con `datalist`.
- Contraste entre los colores del texto y el fondo.

## 5. Estructura del proyecto

```text
Saavedra-Jonnathan-Artesanias/
├── .vscode/
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
└── index.html
```

Esta estructura sigue la organización mostrada para el proyecto. La carpeta `assets/` contiene los recursos visuales, `css/` contiene los estilos y `docs/` reúne la documentación y las evidencias de la práctica.

## 6. Evidencias

Las capturas de las validaciones y pruebas se guardan en `docs/evidencias/`. Se recomienda que cada captura tenga un nombre descriptivo y corresponda a una comprobación efectivamente realizada.

## 7. Estado del proyecto

El proyecto reúne la página principal, los recursos visuales y la documentación de la práctica. Para completar la revisión, se deben ejecutar las validaciones, comprobar el diseño adaptable y la accesibilidad, corregir los problemas encontrados y añadir las evidencias correspondientes.
