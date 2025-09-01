# VEYRA - CSS Básico

Este proyecto incluye un archivo CSS básico y sencillo que se puede aplicar a todas las páginas HTML.

## Archivos

- `styles.css` - Archivo CSS básico con estilos esenciales
- `SignUp.html` - Página de registro
- `login_page.html` - Página de login (usando el mismo CSS básico)

## Cómo usar el CSS Básico

### 1. Enlazar el CSS en tu HTML

```html
<head>
  <!-- CSS Básico VEYRA -->
  <link rel="stylesheet" href="styles.css">
</head>
```

### 2. Estructura HTML recomendada

```html
<body>
  <div class="frame">
    <header class="nav">
      <!-- Navegación -->
    </header>
    
    <main class="stage">
      <section class="card-wrap">
        <!-- Contenido principal -->
      </section>
    </main>
  </div>
</body>
```

## Clases CSS Disponibles

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

### Utilidades
- `.text-center`, `.text-left`, `.text-right` - Alineación de texto
- `.mt-1`, `.mt-2`, `.mt-3` - Márgenes superiores
- `.mb-1`, `.mb-2`, `.mb-3` - Márgenes inferiores
- `.p-1`, `.p-2`, `.p-3` - Padding

## Colores

El CSS usa colores simples y básicos:
- **Fondo principal**: #f5f5f5 (gris claro)
- **Texto**: #333 (gris oscuro)
- **Bordes**: #ddd (gris medio)
- **Botones**: #333 (gris oscuro)
- **Hover**: #666 (gris medio)

## Responsive

El CSS incluye un media query básico para:
- **768px y menos**: Navegación apilada, grids de 1 columna

## Características

- ✅ CSS simple y fácil de entender
- ✅ Sin variables CSS complejas
- ✅ Colores básicos y directos
- ✅ Responsive básico
- ✅ Sin dependencias externas
- ✅ Fácil de modificar
- ✅ Estructura clara y organizada
- ✅ Navegación entre páginas funcional