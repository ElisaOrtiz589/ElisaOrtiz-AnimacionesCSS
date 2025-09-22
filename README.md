# Proyecto "Retro" - Desafío Animaciones en CSS

Este proyecto es una página web estática y responsiva que explora la historia fotográfica de Valparaíso a principios del siglo XX. El sitio está diseñado para ser visualmente atractivo y funcional en dispositivos móviles, tablets y de escritorio.

## Características Técnicas Implementadas

El desarrollo de este proyecto cumple con los siguientes requisitos técnicos:

### 1. Layout Moderno con Grid y Flexbox
Se utilizó una combinación estratégica de CSS Grid y Flexbox para construir un layout robusto y flexible.
- **CSS Grid**: Es la base de la estructura principal de la página (`.contenedor-principal`), permitiendo una organización clara entre el menú de navegación y el área de contenido, que se adapta de una vista de columna en móvil a una de dos columnas en escritorio.
- **Flexbox**: Se usó para alinear y distribuir elementos dentro de los componentes, como el encabezado (`.menu`), las tarjetas de la galería (`.main__galeria__fotos`), las tarjetas de cámaras (`.camaras__description`) y el pie de página (`.footer`).

### 2. Diseño Responsivo con Media Queries
La página ofrece una experiencia de usuario óptima en cualquier dispositivo gracias al uso de `media queries`. Se definieron puntos de quiebre (breakpoints) para adaptar el layout y los componentes en tres vistas principales:
- **Móvil (Mobile-First)**: El diseño base, con una navegación accesible a través de un ícono de hamburguesa.
- **Tablet**: El menú se expande a una barra de navegación horizontal y los elementos de la galería y cámaras se organizan en filas.
- **Desktop**: Se adopta un layout de panel lateral fijo para el menú, optimizando el espacio en pantallas grandes.

### 3. Animaciones y Transiciones para una Experiencia Dinámica
Se incorporaron animaciones y transiciones para dar vida a la página y mejorar la interacción del usuario.
- **Animaciones (`@keyframes`)**:
    - Un auto de época se desplaza continuamente por la parte inferior de la sección de introducción, creando un efecto visual temático.
    - Un ícono en el footer gira sobre su eje, añadiendo un detalle sutil y dinámico.
- **Transiciones y Transformaciones**:
    - La **galería de imágenes** cuenta con efectos interactivos al pasar el cursor (`:hover`). Las imágenes se escalan (`transform: scale()`), se les aplica un filtro sepia (`filter: sepia()`) y aparece una superposición con información (`overlay`), todo ello suavizado con `transition`.
    - Los íconos de redes sociales y los enlaces del menú también tienen transiciones suaves que mejoran la retroalimentación visual.

### 4. Footer Informativo
El pie de página (`footer`) está diseñado para ser funcional y estético. Contiene:
- **Enlaces a Redes Sociales**: Iconos que dirigen a perfiles de LinkedIn, X, Instagram y Facebook.
- **Información de Contacto**: Accesos directos para contactar por WhatsApp o correo electrónico.
- **Copyright**: Información sobre los derechos de autor.

### 5. Apariencia Coherente con CSS
Se ha mantenido una identidad visual consistente en todo el sitio mediante una hoja de estilos (`estilos.css`) bien estructurada. Se definieron variables implícitas a través de una paleta de colores retro, tipografías temáticas y un espaciado uniforme para asegurar una experiencia de usuario cohesiva.
