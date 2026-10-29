# Portafolio Interactivo

Práctica calificada de Hojas de Estilo en Cascada Avanzado — PC3

## 📋 Descripción

Página web tipo portafolio desarrollada con Bootstrap 5 y CSS avanzado. Cuenta con tres páginas:

- **Inicio** — Presentación, proyectos con efectos visuales y animaciones
- **Ubicación** — Mapa y explicación de atención presencial y virtual
- **Contacto** — Formulario independiente

Totalmente responsiva para móviles, tablets y escritorio.

## ✨ Estructura del proyecto

- `index.html` — Página principal
- `ubicacion.html` — Ubicación, mapa y modalidades de atención
- `contacto.html` — Formulario de contacto
- `estilos.css` — Transformaciones, animaciones y estilos personalizados

## ✨ Efectos aplicados

### 🔄 Transformaciones 2D

- **Rotación**: Tarjeta 1 → `transform: rotate(10deg)` al pasar el mouse
- **Escalado**: Tarjeta 2 → `transform: scale(1.1)` al pasar el mouse
- **Traslación**: Tarjeta 3 → `transform: translateY(-10px)` al pasar el mouse
- Todas con `transition: all 0.3s ease` para suavidad

### 🎭 Transformación 3D

- Contenedor con `perspective: 1000px`
- Tarjeta con `transform-style: preserve-3d` + `rotateX(15deg) rotateY(15deg)`

### 🎬 Animaciones CSS

- **Título deslizante**: `@keyframes deslizarEntrada` — entrada desde la izquierda
- **Loader**: `@keyframes girar` — círculo giratorio infinito

## 🛠️ Tecnologías

- HTML5
- Bootstrap 5.3.3 (CDN)
- CSS3 puro
- Google Maps Embed

## 👤 Autor

- [Tu Nombre]
