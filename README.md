# CV Interactivo - Angie Blas

Un CV web interactivo, moderno y totalmente personalizable construido con HTML5, CSS3 y JavaScript vanilla.

## 🚀 Características

- **Diseño Moderno**: Paleta de colores vibrantes (morado, rosa, azul neón, verde)
- **Totalmente Interactivo**: Animaciones fluidas y efectos hover
- **Modo Oscuro/Claro**: Toggle con transición suave
- **Cursor Personalizado**: Efectos de partículas y seguimiento
- **Responsive**: Adaptable a todos los dispositivos
- **Animaciones CSS**: Efectos de máquina de escribir, scroll suave, y más
- **Modales Interactivos**: Para proyectos y habilidades
- **Formulario de Contacto**: Con validación y efectos visuales

## 📝 Personalización Fácil

### 1. Información Personal

Busca los comentarios `<!-- EDITABLE: -->` en el archivo `index.html`:

```html
<!-- EDITABLE: Información personal -->
<img src="URL_DE_TU_FOTO" alt="Tu Nombre" class="profile-image">

<!-- EDITABLE: Enlaces de redes sociales -->
<a href="TU_LINKEDIN" class="social-btn" data-tooltip="LinkedIn">

<!-- EDITABLE: Biografía -->
<p class="bio">Tu biografía aquí...</p>
```

### 2. Experiencia Laboral

Modifica las tarjetas de experiencia:

```html
<!-- EDITABLE: Experiencia laboral -->
<div class="experience-card">
    <h3>Tu Puesto</h3>
    <h4>Nombre de la Empresa</h4>
    <p class="period">Fecha - Fecha</p>
    <div class="experience-details">
        <ul>
            <li>Responsabilidad 1</li>
            <li>Responsabilidad 2</li>
        </ul>
    </div>
</div>
```

### 3. Habilidades Técnicas

Actualiza las habilidades en la sección correspondiente:

```html
<!-- EDITABLE: Habilidades técnicas -->
<div class="skill-chip" data-category="frontend" data-skill="NombreHabilidad">
    <i class="fab fa-html5"></i>
    <span>HTML5</span>
    <div class="skill-level" data-level="90"></div>
</div>
```

### 4. Proyectos

Personaliza tus proyectos:

```html
<!-- EDITABLE: Proyectos -->
<div class="project-card">
    <div class="project-image">
        <img src="URL_IMAGEN_PROYECTO" alt="Nombre Proyecto">
    </div>
    <div class="project-content">
        <h3>Nombre del Proyecto</h3>
        <p>Descripción del proyecto...</p>
    </div>
</div>
```

### 5. Información de Contacto

Actualiza los datos de contacto en el footer:

```html
<!-- EDITABLE: Información de contacto -->
<p>&copy; 2025 Tu Nombre. Hecho con ❤️ y mucho código.</p>
```

## 🎨 Personalización de Colores

Modifica las variables CSS en `css/style.css`:

```css
:root {
  --primary-color: #8B5CF6;    /* Morado principal */
  --secondary-color: #EC4899;   /* Rosa */
  --accent-color: #06B6D4;      /* Azul cian */
  --neon-green: #10B981;        /* Verde neón */
  --electric-blue: #3B82F6;     /* Azul eléctrico */
  --bright-pink: #F59E0B;       /* Rosa brillante */
}
```

## 📱 Secciones Incluidas

1. **Header**: Foto de perfil con animación, título con efecto typewriter
2. **Sobre Mí**: Biografía con estadísticas animadas
3. **Experiencia**: Tarjetas expandibles con detalles
4. **Habilidades**: Chips interactivos con barras de progreso
5. **Proyectos**: Grid de proyectos con modales
6. **Contacto**: Formulario funcional con validación
7. **Footer**: Enlaces sociales y información

## 🛠️ Tecnologías Utilizadas

- **HTML5**: Estructura semántica
- **CSS3**: Animaciones, Grid, Flexbox
- **JavaScript**: Interacciones y efectos
- **Bootstrap 5**: Sistema de grid y componentes
- **Font Awesome**: Iconos
- **Google Fonts**: Tipografía Poppins
- **AOS**: Animaciones on scroll

## 🚀 Instalación y Uso

1. Descarga todos los archivos
2. Personaliza tu información en `index.html`
3. Ajusta colores y estilos en `css/style.css`
4. Modifica funcionalidades en `js/script.js`
5. Abre `index.html` en tu navegador

## 📁 Estructura de Archivos

```
cv-interactivo/
├── index.html
├── css/
│   └── style.css
├── js/
│   └── script.js
├── images/
│   └── (tus imágenes)
└── README.md
```

## 🎯 Funcionalidades Interactivas

- **Cursor Personalizado**: Seguimiento con partículas
- **Modo Oscuro**: Toggle con transición suave
- **Efecto Typewriter**: Animación de texto
- **Scroll Suave**: Navegación fluida
- **Hover Effects**: En tarjetas y botones
- **Modales**: Para proyectos y habilidades
- **Animaciones**: CSS y JavaScript
- **Responsive**: Adaptable a móviles

## 🔧 Personalización Avanzada

### Añadir Nueva Habilidad

1. Duplica un `.skill-chip` existente
2. Cambia el `data-skill` y `data-category`
3. Actualiza el icono y nivel
4. Añade información en `js/script.js`

### Nuevo Proyecto

1. Crea nueva tarjeta en la sección proyectos
2. Añade modal correspondiente
3. Actualiza función `openProjectModal()`

### Cambiar Animaciones

Modifica las animaciones CSS en `css/style.css`:

```css
@keyframes tuAnimacion {
  0% { transform: translateY(0); }
  100% { transform: translateY(-10px); }
}
```

## 🌟 Tips de Personalización

- Usa imágenes de alta calidad (recomendado: 400x400px para perfil)
- Mantén consistencia en la paleta de colores
- Optimiza imágenes para web
- Prueba en diferentes dispositivos
- Utiliza herramientas como Lighthouse para optimización

## 🎨 Inspiración de Colores

Puedes cambiar toda la paleta modificando las variables CSS:

```css
/* Paleta Azul/Verde */
--primary-color: #3B82F6;
--secondary-color: #10B981;

/* Paleta Rosa/Púrpura */
--primary-color: #EC4899;
--secondary-color: #8B5CF6;

/* Paleta Naranja/Rojo */
--primary-color: #F59E0B;
--secondary-color: #EF4444;
```

## 📞 Soporte

Si tienes dudas sobre la personalización:

1. Revisa los comentarios en el código
2. Consulta la documentación de Bootstrap 5
3. Experimenta con las variables CSS

## 🚀 Deployment

Puedes hospedar tu CV en:

- **GitHub Pages**: Gratis para repositorios públicos
- **Netlify**: Deploy automático
- **Vercel**: Perfecto para proyectos estáticos
- **Firebase Hosting**: Hosting de Google

¡Disfruta creando tu CV interactivo! 🎉
# temp-rep
