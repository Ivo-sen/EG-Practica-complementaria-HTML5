# Práctica complementaria HTML5 - Ivo Huanambal

## 1. Ventajas de HTML5

- Mayor compatibilidad: HTML5 es más compatible con dispositivos móviles y de escritorio.
- Soporte para multimedia: Soporta de forma nativa audio y video sin necesidad de plugins externos.
- Semántica mejorada: Introduce etiquetas como `<article>`, `<section>`, `<header>`, `<footer>`, etc., que mejoran la estructura del documento y la accesibilidad.
- Mayor rendimiento: Permite mejorar la velocidad de carga de las páginas gracias a características como el almacenamiento local (`localStorage`) y el uso de cache.
- Mejor soporte para aplicaciones web: Con APIs como la API de geolocalización, almacenamiento local, etc.
- Interactividad sin necesidad de JavaScript: HTML5 incluye nuevas funcionalidades que permiten crear páginas interactivas sin depender de JS, como formularios mejorados.

## 2. ¿Por qué utilizarlo?

HTML5 es la última versión de HTML, y es ideal para crear aplicaciones web modernas que sean responsivas, accesibles y eficientes. Gracias a sus nuevas características, HTML5 simplifica la creación de contenido multimedia, mejora la accesibilidad y optimiza el rendimiento de las páginas web, haciendo que sea la opción recomendada para los desarrolladores.

## 3. Nombre ventajas

- Multimedia sin plugins (audio, video)
- Aplicaciones web ricas con APIs integradas (geolocalización, notificaciones push, etc.).
- Compatibilidad con dispositivos móviles.

## 2.A) Formatos de audio soportados

- MP3 (`.mp3`)
- Ogg Vorbis (`.ogg`)
- WAV (`.wav`)

### Ejemplo de audio en HTML5

```html
<audio controls>
  <source src="https://html5tutorial.info/media/vincent.mp3" type="audio/mpeg">
</audio>
```

## 3.A) Formatos de video soportados

- MP4 (`.mp4`) — con códec H.264
- WebM (`.webm`) — con códec VP8 o VP9
- Ogg (`.ogv`) — con códec Theora

### Ejemplo de video en HTML5

```html
<video controls width="480">
  <source src="https://www.w3schools.com/html/mov_bbb.mp4" type="video/mp4">
  <source src="https://www.w3schools.com/html/mov_bbb.ogg" type="video/ogg">
</video>
```

## 4. Formularios HTML5

### 4.A) Campo requerido

```html
<form>
  <label for="nombre">Nombre:</label>
  <input type="text" id="nombre" name="nombre" required>
  <button type="submit">Enviar</button>
</form>
```

### 4.B) Campo de tipo email

```html
<form>
  <label for="correo">Correo electrónico:</label>
  <input type="email" id="correo" name="correo" required>
  <button type="submit">Enviar</button>
</form>
```

### 4.C) Campo de tipo fecha

```html
<form>
  <label for="fecha">Fecha de nacimiento:</label>
  <input type="date" id="fecha" name="fecha" required>
  <button type="submit">Enviar</button>
</form>
```

### 4.D) Campo de tipo color

```html
<form>
  <label for="color">Elige tu color favorito:</label>
  <input type="color" id="color" name="color">
  <button type="submit">Enviar</button>
</form>
```

### 4.E) Campo de tipo número con valores mínimos y máximos

```html
<form>
  <label for="edad">Edad (entre 18 y 60):</label>
  <input type="number" id="edad" name="edad" min="18" max="60" required>
  <button type="submit">Enviar</button>
</form>
```
