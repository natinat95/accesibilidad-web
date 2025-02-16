# Proyecto de Accesibilidad Web | Web Accessibility Project

## Español

### Proceso de desarrollo

En este proyecto, desarrollamos varias páginas HTML básicas que incluyen formularios, botones, enlaces, tablas e imágenes. El objetivo principal era mejorar la accesibilidad de estas páginas, para que fueran más accesibles para personas con discapacidad, utilizando las pautas de accesibilidad web.

Las páginas HTML originales fueron las siguientes:
- **index_form.html**: Un formulario simple de registro.
- **index_buttons.html**: Botones y enlaces para interacciones.
- **index_table.html**: Una tabla con datos de usuarios.
- **index_images.html**: Una galería de imágenes.

### Pasos seguidos para validar la accesibilidad

1. **Validación inicial**:
   Usamos las herramientas **WAVE** y **Lighthouse** para realizar una validación inicial de accesibilidad en cada uno de los archivos HTML antes de aplicar mejoras. Esto nos proporcionó un informe sobre los errores y advertencias de accesibilidad.
   
2. **Mejoras de accesibilidad**:
   - Agregamos descripciones de las imágenes con el atributo `alt`.
   - Usamos roles y propiedades ARIA para mejorar la navegación con lectores de pantalla.
   - Mejoramos la estructura semántica utilizando etiquetas como `<header>`, `<main>`, `<h1>`, `<h2>`, etc.
   - Mejoramos los formularios con etiquetas `label` y asociándolas correctamente con los campos de entrada.
   - Añadimos atributos `aria-label` en botones y enlaces para describir mejor su función.

3. **Validación después de los cambios**:
   Después de implementar las mejoras, volvimos a usar las mismas herramientas para validar las páginas. El objetivo era asegurarnos de que todas las advertencias y errores de accesibilidad fueran corregidos.

### Problemas encontrados y soluciones aplicadas

Durante la validación inicial, se identificaron los siguientes problemas comunes de accesibilidad:
- **Falta de descripciones en las imágenes**: Muchas imágenes no tenían el atributo `alt`, lo que dificultaba la comprensión del contenido para los usuarios de lectores de pantalla. Se añadió un texto descriptivo adecuado en todas las imágenes.
- **Falta de etiquetas `label`** en los campos de formulario: Esto dificultaba la interacción con el formulario para personas con discapacidad visual. Se añadieron etiquetas `label` con los atributos `for` asociados correctamente a cada campo.
- **No se utilizaban roles y propiedades ARIA**: Los botones y enlaces no estaban completamente descritos para los usuarios de lectores de pantalla. Se añadieron atributos `aria-label` a los botones y enlaces para describir mejor sus funciones.

### Enlace a las capturas de pantalla

![Captura de pantalla 2025-02-16 132343](https://github.com/user-attachments/assets/29e17ad8-ed2b-4b93-936d-5ee372d0f102)

# Web Accessibility Project | Proyecto de Accesibilidad Web

## English

### Development Process

In this project, we developed several basic HTML pages that include forms, buttons, links, tables, and images. The main objective was to improve the accessibility of these pages so that they are more accessible to people with disabilities, following web accessibility guidelines.

The original HTML pages were as follows:
- **index_form.html**: A simple registration form.
- **index_buttons.html**: Buttons and links for interactions.
- **index_table.html**: A table with user data.
- **index_images.html**: An image gallery.

### Steps Followed to Validate Accessibility

1. **Initial Validation**:
   We used the **WAVE** and **Lighthouse** tools to perform an initial accessibility validation of each HTML file before applying improvements. This provided us with a report on accessibility errors and warnings.
   
2. **Accessibility Improvements**:
   - We added image descriptions using the `alt` attribute.
   - We used ARIA roles and properties to improve screen reader navigation.
   - We improved the semantic structure using tags like `<header>`, `<main>`, `<h1>`, `<h2>`, etc.
   - We enhanced the forms with `label` tags properly associated with input fields.
   - We added `aria-label` attributes to buttons and links for better description of their function.

3. **Validation After Changes**:
   After implementing the improvements, we used the same tools to validate the pages again. The goal was to ensure that all accessibility warnings and errors were fixed.

### Problems Found and Solutions Applied

During the initial validation, the following common accessibility issues were identified:
- **Missing image descriptions**: Many images did not have the `alt` attribute, which made it difficult for screen reader users to understand the content. Descriptive text was added to all images.
- **Missing `label` tags** for form fields: This made it difficult for visually impaired users to interact with the form. `label` tags were added with the correct `for` attributes associated with each field.
- **No ARIA roles and properties used**: Buttons and links were not fully described for screen reader users. `aria-label` attributes were added to buttons and links to better describe their functions.

### Link to Screenshots

![Captura de pantalla 2025-02-16 132343](https://github.com/user-attachments/assets/29e17ad8-ed2b-4b93-936d-5ee372d0f102)


