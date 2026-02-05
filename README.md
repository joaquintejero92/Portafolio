# 🎨 Portafolio Web - Trabajo Tema 4 DIW

## 📋 Información del Proyecto

**Autor:** Joaquín Ángel Tejero Cañero  
**Asignatura:** Diseño de Interfaces Web (DIW)  
**Curso:** 2º DAW  
**Tema:** Trabajo del Tema 4

---

## 🌐 Enlace al Despliegue

🔗 **[Ver Portafolio en Vivo](https://github.com/joaquingtejero92/Portafolio)**

---

## 📝 Descripción del Proyecto

Este proyecto es un **portafolio web profesional** desarrollado únicamente con HTML y CSS, sin JavaScript. Incluye todas las características modernas de CSS como:

- ✅ Modo claro/oscuro con variables CSS
- ✅ Transiciones y animaciones avanzadas
- ✅ Animaciones basadas en scroll
- ✅ View Transitions API
- ✅ Diseño totalmente responsive
- ✅ Tipografías personalizadas
- ✅ Iconos SVG
- ✅ Imágenes en múltiples formatos (PNG, WEBP, AVIF)

---

## 📂 Estructura del Proyecto

```
TrabajoTema4/
├── index.html          # Archivo HTML principal
├── style.css           # Hoja de estilos CSS
├── README.md           # Documentación del proyecto
└── assets/
    ├── icons/          # Iconos SVG
    │   ├── html5.svg
    │   ├── css3.svg
    │   ├── javascript.svg
    │   ├── diseno.svg
    │   └── git.svg
    └── img/            # Imágenes del proyecto
        ├── foto-perfil-original.png
        ├── proyecto-web.webp
        ├── proyecto-tienda.webp
        ├── proyecto-dashboard.avif
        └── adorno.png (con transparencia)
```

---

## 🎯 Secciones del Portafolio

### 1. Cabecera con Navegación
Navegación fija con logo, enlaces y botón de cambio de tema claro/oscuro.

### 2. Hero / Presentación
Sección principal con foto de perfil, título animado y botones de acción.

### 3. Habilidades
Tarjetas interactivas con efecto 3D de volteo mostrando tecnologías dominadas.

### 4. Proyectos
Galería de proyectos con animación de aparición basada en scroll.

### 5. Contacto
Formulario de contacto estilizado y centrado.

### 6. Pie de Página
Footer con enlaces y copyright.

---

## 📸 Capturas de Pantalla

### Versión Escritorio

#### Modo Claro
*(Añadir captura de pantalla aquí)*

#### Modo Oscuro
*(Añadir captura de pantalla aquí)*

### Versión Móvil

#### Hero y Navegación
*(Añadir captura de pantalla aquí)*

#### Habilidades
*(Añadir captura de pantalla aquí)*

#### Proyectos
*(Añadir captura de pantalla aquí)*

#### Contacto
*(Añadir captura de pantalla aquí)*

---

## 🛠️ Tecnologías Utilizadas

| Tecnología | Uso |
|------------|-----|
| **HTML5** | Estructura semántica del sitio |
| **CSS3** | Estilos, animaciones y responsive |
| **Google Fonts** | Tipografías: Poppins e Inter |
| **SVG** | Iconos vectoriales |
| **CSS Variables** | Temas claro/oscuro |

---

## ✨ Características CSS Implementadas

### Variables CSS
- Paleta de colores completa para modo claro y oscuro
- Variables de espaciado, tipografía y bordes
- Cambio de tema sin JavaScript usando `:has()` selector

### Transiciones (9+ implementadas)
1. Logo al hacer hover
2. Enlaces de navegación
3. Botón de cambio de tema
4. Botones de acción
5. Tarjetas de habilidad (volteo 3D)
6. Tarjetas de proyecto
7. Imágenes de proyecto (zoom)
8. Campos de formulario (focus)
9. Botón de enviar

### Animaciones (6+ implementadas)
1. `aparecerDesdeIzquierda` - Texto del hero
2. `aparecerDesdeDerecha` - Imagen del hero
3. `flotar` - Imagen de perfil flotante
4. `rotarAdorno` - Elemento decorativo giratorio
5. `rebotarFlecha` - Flecha de scroll
6. `aparecerConScroll` - Proyectos con scroll-driven

### Animación 3D
- Efecto de volteo (flip) en las tarjetas de habilidades usando `rotateY()` y `perspective`

### Animaciones Basadas en Scroll
- `animation-timeline: view()` para aparición de proyectos

### View Transitions
- Soporte para transiciones de vista entre estados

---

## 📱 Responsive Breakpoints

| Dispositivo | Breakpoint |
|-------------|------------|
| Móvil pequeño | < 480px |
| Móvil | < 768px |
| Tablet | 768px - 1024px |
| Escritorio | 1024px - 1440px |
| TV / Pantalla grande | > 1440px |

---

## 🚀 Cómo Desplegar

### Opción 1: GitHub Pages
1. Subir el código a un repositorio de GitHub
2. Ir a Settings > Pages
3. Seleccionar la rama `main` y carpeta `/ (root)`
4. Guardar y esperar a que se despliegue

### Opción 2: Netlify
1. Arrastrar la carpeta del proyecto a [netlify.com/drop](https://netlify.com/drop)
2. Copiar la URL generada

### Opción 3: Vercel
1. Conectar el repositorio de GitHub a Vercel
2. Despliegue automático

---

## 📄 Licencia

Este proyecto es un trabajo académico para el módulo de Diseño de Interfaces Web (DIW).

---

## 👤 Autor

**[Joaquin]**  
Estudiante de 2º DAW  
[https://github.com/joaquintejero92]
