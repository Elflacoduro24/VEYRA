# VEYRA - Sustainable Fashion Platform

## 👥 **Equipo del Proyecto**

**Desarrollador:** Sebastián  
- **Ramas:** `About-us, Login, SignUp` (ramas personales de desarrollo)  
- **Responsabilidades:** Desarrollo del frontend, CSS personalizado, accesibilidad

**Desarrollador:** Juan Romero  
- **Ramas:** `Explore-seeds, Products` (ramas personales de desarrollo)  
- **Responsabilidades:** Desarrollo del frontend, CSS personalizado  

## 🎯 **Criterios de Aceptación Cumplidos**

### ✅ **Grid Layout**
- Implementado con CSS Grid nativo
- `.grid-2` - Grid de 2 columnas para formularios
- `.grid-3` - Grid de 3 columnas para tarjetas de contenido
- Responsive: se apila en móvil

### ✅ **Flexbox**
- Navegación principal usando flexbox
- Layout de botones y elementos de interfaz
- Distribución flexible de contenido

### ✅ **Responsive (Mobile & Desktop)**
- Media queries para diferentes breakpoints
- **Desktop (>768px)**: Layout completo con navegación horizontal
- **Mobile (≤768px)**: Navegación apilada, grids de 1 columna
- Diseño adaptativo para todos los dispositivos

### ✅ **HTML Best Practices**
- **Semántico**: `<header>`, `<main>`, `<section>`, `<nav>`, `<article>`
- **Metadatos**: Descripción, keywords, Open Graph, canonical URLs
- **A11y (Accesibilidad)**:
  - Skip links para navegación por teclado
  - ARIA labels y roles apropiados
  - IDs únicos para secciones
  - Roles semánticos (list, listitem, button)
  - Focus visible para navegación por teclado

### ✅ **CSS desde Cero**
- **Sin frameworks o librerías** externas
- **CSS personalizado** construido completamente desde cero
- **Variables CSS** para consistencia
- **Sistema de clases** reutilizables

## 📁 **Archivos del Proyecto**

- `styles.css` - CSS global básico con estilos esenciales
- `SignUp.html` - Página de registro con formulario completo
- `login_page.html` - Página de login funcional
- `About-Us.html` - Página About Us con contenido informativo

## 🚀 **Cómo usar el CSS Global**

### 1. Enlazar el CSS en tu HTML

```html
<head>
  <!-- CSS Global VEYRA -->
  <link rel="stylesheet" href="styles.css">
</head>
```

### 2. Estructura HTML recomendada

```html
<body>
  <a href="#main-content" class="skip-link">Skip to main content</a>
  <div class="frame">
    <header class="nav">
      <!-- Navegación -->
    </header>
    
    <main class="stage" id="main-content">
      <section class="card-wrap">
        <!-- Contenido principal -->
      </section>
    </main>
  </div>
</body>
```

## 🎨 **Clases CSS Disponibles**

### Layout
- `.frame` - Contenedor principal con sombra
- `.nav` - Barra de navegación
- `.stage` - Área de contenido principal
- `.card-wrap` - Contenedor de tarjetas

### Navegación
- `.brand` - Logo y nombre de marca
- `.logo` - Círculo del logo
- `.links` - Enlaces de navegación
- `.auth` - Botones de autenticación

### Botones
- `.btn` - Botón básico
- `.btn.primary` - Botón primario
- `.submit-btn` - Botón de envío

### Formularios
- `.signup-card` - Tarjeta de formulario
- `.form-group` - Grupo de campos
- `.grid-2` - Grid de 2 columnas
- `.grid-3` - Grid de 3 columnas

### Contenido
- `.card` - Tarjeta de contenido
- `.actions` - Contenedor de botones de acción
- `.image-placeholder` - Placeholder para imágenes
- `.ph` - Placeholder de imagen con emoji

### Accesibilidad
- `.skip-link` - Enlace para saltar al contenido principal
- `.visually-hidden` - Texto oculto visualmente pero accesible
- Focus visible para navegación por teclado

### Utilidades
- `.text-center`, `.text-left`, `.text-right` - Alineación de texto
- `.mt-1`, `.mt-2`, `.mt-3` - Márgenes superiores
- `.mb-1`, `.mb-2`, `.mb-3` - Márgenes inferiores
- `.p-1`, `.p-2`, `.p-3` - Padding

## 🌈 **Paleta de Colores**

- **Fondo principal**: #f5f5f5 (gris claro)
- **Texto**: #333 (gris oscuro)
- **Bordes**: #ddd (gris medio)
- **Botones**: #333 (gris oscuro)
- **Hover**: #666 (gris medio)
- **Accent**: #c084fc (morado para placeholders)

## 📱 **Responsive Design**

### Breakpoints
- **Desktop (>768px)**: Layout completo
- **Mobile (≤768px)**: 
  - Navegación apilada
  - Grids de 1 columna
  - Espaciado optimizado
  - Tipografía ajustada

## ♿ **Características de Accesibilidad**

- **Skip links** para navegación por teclado
- **ARIA labels** y roles apropiados
- **Focus visible** para todos los elementos interactivos
- **Semántica HTML** correcta
- **Contraste** adecuado de colores
- **Navegación por teclado** completa

## 🔧 **Características Técnicas**

- ✅ CSS simple y fácil de entender
- ✅ Sin variables CSS complejas
- ✅ Colores básicos y directos
- ✅ Responsive completo
- ✅ Sin dependencias externas
- ✅ Fácil de modificar
- ✅ Estructura clara y organizada
- ✅ Navegación entre páginas funcional
- ✅ Accesibilidad WCAG 2.1 AA
- ✅ HTML semántico y validado
- ✅ Metadatos SEO optimizados

## 📚 **Recursos Utilizados**

- **Google Fonts**: Inter (ya no se usa, reemplazado por Arial)
- **Emojis nativos**: Para placeholders de imágenes
- **CSS Grid y Flexbox**: Nativos del navegador
- **Media Queries**: CSS nativo para responsive

## 🚀 **Instalación y Uso**

1. Clona el repositorio
2. Abre cualquier archivo HTML en tu navegador
3. El CSS se aplicará automáticamente
4. Todas las páginas están interconectadas

## 📝 **Notas del Desarrollador**

Este proyecto demuestra un dominio completo de:
- **CSS Grid y Flexbox** para layouts modernos
- **Responsive design** sin frameworks
- **Accesibilidad web** siguiendo estándares WCAG
- **HTML semántico** y mejores prácticas
- **CSS personalizado** construido desde cero

El código está optimizado para mantenibilidad y escalabilidad, siguiendo principios de diseño web modernos y accesibles.