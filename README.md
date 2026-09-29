# Formulario web con HTML, CSS y JavaScript

Proyecto educativo que implementa un formulario de registro responsivo con validaciones nativas de HTML5 y validaciones adicionales en JavaScript.

## Tecnologías

- HTML5: estructura, etiquetas accesibles y restricciones de campos.
- CSS3: estilos, CSS Grid, estados de foco/error y diseño adaptable.
- JavaScript: manipulación del DOM, eventos `input`, `blur` y `submit`, validación y almacenamiento en un objeto tipo diccionario.

## Campos y validaciones

- Nombre: obligatorio, entre 2 y 60 caracteres.
- Correo: obligatorio y con formato de correo.
- Contraseña: obligatoria, mínimo 8 caracteres.
- Edad: obligatoria, número entero entre 1 y 120.
- Teléfono: obligatorio, entre 7 y 15 dígitos; permite espacios, `+`, paréntesis, puntos y guiones.
- Perfil: selección obligatoria entre Estudiante, Docente u Otro.

## Cómo abrirlo

Abre `index.html` en un navegador web. No requiere instalación ni servidor.

Al enviar datos válidos, JavaScript crea el objeto `datosFormulario` a partir de las entradas del formulario. El objeto solo vive en la memoria de la página abierta: este proyecto no usa un servidor ni guarda datos de forma permanente. La contraseña forma parte del objeto para cumplir el ejercicio, así que usa datos de prueba y no una contraseña real.
