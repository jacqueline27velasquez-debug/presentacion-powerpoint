# 🎬 Presentación Académica - Reveal.js

Una presentación académica profesional creada con **Reveal.js**, completamente personalizable y con animaciones increíbles.

## 🚀 Cómo usar

### Opción 1: Descargar y abrir localmente
1. Descarga este repositorio (botón verde "Code" → "Download ZIP")
2. Extrae la carpeta
3. Abre el archivo `index.html` en tu navegador
4. ¡Listo! Usa las flechas para navegar

### Opción 2: Usar GitHub Pages (la mejor opción) ⭐
1. Ve a los **Settings** del repositorio
2. Busca **"Pages"** en el menú izquierdo
3. En **"Source"** selecciona **"main"** o **"master"**
4. Tu presentación estará en vivo en: `https://jacqueline27velasquez-debug.github.io/presentacion-powerpoint/`
5. ¡Comparte el link con quien quieras!

## ⌨️ Controles

| Tecla | Acción |
|-------|--------|
| **→** | Siguiente slide |
| **←** | Slide anterior |
| **↓** | Contenido dentro del slide |
| **↑** | Subir en contenido anidado |
| **F** | Pantalla completa |
| **ESC** | Vista general (ver todas las slides) |
| **S** | Notas del presentador |

## 🎨 Personalización rápida

### 1. Cambiar el tema
Abre `index.html` en un editor de texto y busca la línea:
```html
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/reveal.js/4.5.0/theme/black.min.css">
```

Cambia `black` por uno de estos:
- `white` - Blanco y limpio
- `league` - Azul moderno
- `sky` - Azul claro
- `beige` - Cálido y profesional
- `simple` - Minimalista
- `blood` - Rojo oscuro
- `night` - Oscuro elegante
- `moon` - Gris oscuro
- `solarized` - Colorido

### 2. Agregar nuevas slides
Copia esto dentro de `<div class="slides">`:
```html
<section>
	<h2>Tu Título</h2>
	<p>Tu contenido aquí</p>
</section>
```

### 3. Agregar animaciones
```html
<p class="fragment">Este texto aparecerá con animación</p>
<p class="fragment fade-in">Fade in</p>
<p class="fragment grow">Crece</p>
<p class="fragment highlight-red">Se ilumina</p>
```

## 📚 Ejemplos de contenido

### Listas con animación
```html
<ul>
	<li class="fragment">Punto 1</li>
	<li class="fragment">Punto 2</li>
	<li class="fragment">Punto 3</li>
</ul>
```

### Código
```html
<pre><code class="language-javascript" data-trim>
function ejemplo() {
	return "¡Hola!";
}
</code></pre>
```

### Tabla
```html
<table>
	<tr>
		<th>Columna 1</th>
		<th>Columna 2</th>
	</tr>
	<tr class="fragment">
		<td>Dato 1</td>
		<td>Dato 2</td>
	</tr>
</table>
```

### Imagen
```html
<img src="https://images.unsplash.com/photo-..." style="width: 400px; height: auto;">
```

### Dos columnas
```html
<div style="display: flex; gap: 30px;">
	<div style="flex: 1;">
		<h3>Izquierda</h3>
		<p>Contenido</p>
	</div>
	<div style="flex: 1;">
		<h3>Derecha</h3>
		<p>Contenido</p>
	</div>
</div>
```

### Imagen de fondo
```html
<section data-background="https://images.unsplash.com/photo-..." data-background-size="cover">
	<h1 style="background: rgba(0,0,0,0.7); padding: 20px;">Título sobre imagen</h1>
</section>
```

## 🎯 Tips profesionales

1. **Mantén consistencia**: Usa los mismos colores y fuentes
2. **No abuses de animaciones**: 1-2 por slide máximo
3. **Imágenes de calidad**: Unsplash, Pexels, Pixabay
4. **Texto legible**: Asegura buen contraste
5. **Practica**: Familiarízate con los controles

## 🔗 Recursos útiles

- **Imágenes gratis**: [Unsplash](https://unsplash.com), [Pexels](https://pexels.com), [Pixabay](https://pixabay.com)
- **Iconos**: [Font Awesome](https://fontawesome.com), Emojis 😊
- **Colores**: [Coolors](https://coolors.co)
- **Documentación**: [reveal.js.org](https://revealjs.com)

## 📁 Archivos en este repositorio

- `index.html` - La presentación principal
- `README.md` - Este archivo
- `EJEMPLOS_AVANZADOS.md` - Técnicas más complejas

## 💡 Próximos pasos

1. Personaliza `index.html` con tu contenido
2. Agrega tus imágenes
3. Cambia el tema si quieres
4. Activa GitHub Pages para compartir
5. ¡Presenta con confianza! 🎉

---

**Creado con ❤️ usando Reveal.js - ¡Diviértete creando!**
