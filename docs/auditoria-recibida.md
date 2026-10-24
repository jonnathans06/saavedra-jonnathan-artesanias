# Respuesta a la auditoría recibida

**Estudiante:** Jonnathan Javier Saavedra Villegas  
**Proyecto:** Raíces Artesanías  
**Número de ficha:** 27  
**Auditor:** Elkin Jair Chamba Maura  
**Ficha del auditor:** 28

## 1. Respuesta a los hallazgos

### Hallazgo 1: Orden de las áreas del Grid en dispositivos móviles

**Decisión:** Aceptado y corregido.

**Justificación:** Se identificó que el orden de las áreas del diseño no cumplía con el requisito personalizado de la Ficha 27.

**Corrección realizada:** Se modificó `grid-template-areas` dentro del breakpoint de 900 px para reorganizar las secciones en dispositivos móviles.

**Verificación:** Se comprobó que las áreas del Grid cambian de orden correctamente en la vista móvil.

### Hallazgo 2: Desbordamiento horizontal a 360 px

**Decisión:** Aceptado y corregido.

**Justificación:** Se detectó un desbordamiento horizontal en pantallas de 360 px de ancho.

**Corrección realizada:** Se ajustó la distribución de la sección de contacto y las dimensiones de sus elementos para evitar el desbordamiento horizontal.

**Verificación:** Se comprobó que la página se adapta correctamente a las resoluciones evaluadas sin presentar el desbordamiento señalado.

### Hallazgo 3: Navegación por teclado y foco visible

**Decisión:** Aceptado y corregido.

**Justificación:** Se identificaron aspectos que debían mejorarse en la ubicación del enlace para saltar al contenido principal y en la navegación mediante teclado.

**Corrección realizada:** Se ajustó el enlace «Saltar al contenido principal» y se mejoraron los indicadores visuales de foco.

**Verificación:** Se comprobó el funcionamiento de la navegación mediante teclado y la visibilidad del foco en los elementos interactivos.

### Hallazgo 4: Validación del formulario y estilos del textarea

**Decisión:** Aceptado y corregido.

**Justificación:** Se identificó la necesidad de reforzar la validación del campo de celular y revisar los estilos del área de texto.

**Corrección realizada:** Se incorporó `pattern="[0-9]{9}"` al campo de celular y se revisaron los estilos CSS del elemento `textarea`.

**Verificación:** Se comprobó la validación del campo de celular y la presentación del área de texto.

### Hallazgo 5: Orden de la familia de fuentes CSS

**Decisión:** Aceptado y corregido.

**Justificación:** Se identificó una declaración de la familia tipográfica que debía revisarse.

**Corrección realizada:** Se ajustó la declaración de la variable `--fuente-texto` para establecer `Arial` como fuente principal y `sans-serif` como alternativa genérica.

**Verificación:** Se comprobó la declaración de la familia tipográfica en el CSS.

## 2. Verificación posterior a las correcciones

Después de aplicar las modificaciones, se verificó el funcionamiento de la página, la adaptación a las resoluciones evaluadas, la distribución de las áreas del Grid, la validación del formulario y la navegación mediante teclado.

Las evidencias de las verificaciones realizadas se encuentran en la carpeta `evidencias` del proyecto.

## 3. Conclusión

La auditoría recibida permitió identificar oportunidades de mejora en el proyecto Raíces Artesanías. Se aceptaron los hallazgos señalados y se aplicaron las correcciones correspondientes.

Las verificaciones posteriores permitieron comprobar el funcionamiento de los elementos corregidos y mejorar la adaptación responsive, la organización del diseño, la validación del formulario y la accesibilidad de la página.
