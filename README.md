# 📘 ESTRUCTURA FUNDAMENTAL, SEMÁNTICA Y JERARQUIA DE TEXTO EN HTML

---

# 📂 ESTRUCTURA DEL PROYECTO

Dentro de la carpeta raíz crear la siguiente estructura:

```text
ejercicio_01/
│
├── index.html
└── README.md
```

---

# 🌐 ¿QUÉ ES LA ESTRUCTURA FUNDAMENTAL EN HTML?

La estructura fundamental es la base obligatoria de toda página web.  
Permite que el navegador interprete correctamente el documento HTML.

---

# 🧱 ESTRUCTURA BÁSICA

```html
<!DOCTYPE html>
<html lang="es">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Título de la página</title>
</head>

<body>

</body>

</html>
```

---

# 📖 EXPLICACIÓN DE CADA PARTE

## 🔹 `<!DOCTYPE html>`

Indica que el documento utiliza HTML5.

```html
<!DOCTYPE html>
```

---

## 🔹 `<html>`

Contiene todo el contenido de la página.

```html
<html lang="es">
```

El atributo `lang="es"` indica que el idioma del documento es español.

---

## 🔹 `<head>`

Contiene información de configuración del documento.

```html
<head>
</head>
```

Dentro del `<head>` normalmente encontramos:

- metadatos
- configuraciones
- enlaces CSS
- scripts
- título

---

## 🔹 `<meta charset="UTF-8">`

Permite usar caracteres especiales como:

- ñ
- tildes
- símbolos

```html
<meta charset="UTF-8">
```

---

## 🔹 `<meta name="viewport">`

Hace que la página sea adaptable a celulares y tablets.

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

---

## 🔹 `<title>`

Define el nombre que aparece en la pestaña del navegador.

```html
<title>Mi Página Web</title>
```

---

## 🔹 `<body>`

Contiene todo el contenido visible de la página web.

```html
<body>

</body>
```

---

# 🧠 ¿QUÉ ES LA ESTRUCTURA SEMÁNTICA?

La estructura semántica utiliza etiquetas con significado.

Esto mejora:

- organización del contenido
- accesibilidad
- SEO
- lectura del código

---

# 🏗️ ETIQUETAS SEMÁNTICAS PRINCIPALES

| Etiqueta | Función |
|---|---|
| `<header>` | Encabezado |
| `<nav>` | Navegación |
| `<main>` | Contenido principal |
| `<section>` | Sección |
| `<article>` | Contenido independiente |
| `<aside>` | Información adicional |
| `<footer>` | Pie de página |

---

# 📌 EJEMPLO DE ESTRUCTURA SEMÁNTICA

```html
<body>

  <header>
    <h1>Recetas Peruanas</h1>
  </header>

  <nav>
    <a href="#">Inicio</a>
    <a href="#">Recetas</a>
  </nav>

  <main>

    <section>

      <article>
        <h2>Lomo Saltado</h2>
        <p>Receta tradicional peruana.</p>
      </article>

    </section>

    <aside>
      <p>Dato adicional.</p>
    </aside>

  </main>

  <footer>
    <p>2026 - Desarrollo Web</p>
  </footer>

</body>
```

---

# 📝 ESTRUCTURA DE TEXTO

---

# 🔠 JERARQUÍA DE ENCABEZADOS

Los encabezados permiten organizar el contenido según su importancia.

HTML posee etiquetas desde `<h1>` hasta `<h6>`.

| Etiqueta | Uso |
|---|---|
| `<h1>` | Título principal |
| `<h2>` | Subtítulo |
| `<h3>` | Subsección |
| `<h4>` a `<h6>` | Niveles menores |

---

## 📌 EJEMPLO

```html
<h1>Receta Peruana</h1>
<h2>Ingredientes</h2>
<h3>Preparación</h3>
```

---

# 📄 PÁRRAFOS Y ÉNFASIS

Los párrafos se crean con la etiqueta `<p>`.

Etiquetas importantes:

| Etiqueta | Función |
|---|---|
| `<strong>` | Texto importante |
| `<em>` | Texto enfatizado |
| `<mark>` | Texto resaltado |

---

## 📌 EJEMPLO

```html
<p>La causa limeña es un plato peruano.</p>

<p>
  Es una receta <strong>muy popular</strong>.
</p>

<p>
  Tiene un sabor <em>delicioso</em>.
</p>

<p>
  Usar papa amarilla <mark>mejora el sabor</mark>.
</p>
```

---

# 📋 LISTAS

HTML permite crear listas ordenadas y desordenadas.

---

## 🔹 LISTA ORDENADA

Se utiliza `<ol>`.

```html
<ol>
  <li>Hervir las papas</li>
  <li>Preparar el relleno</li>
  <li>Servir</li>
</ol>
```

---

## 🔹 LISTA DESORDENADA

Se utiliza `<ul>`.

```html
<ul>
  <li>Papa amarilla</li>
  <li>Ají amarillo</li>
  <li>Pollo</li>
</ul>
```

---

# 💬 CITAS Y REFERENCIAS

Se utilizan las etiquetas:

| Etiqueta | Función |
|---|---|
| `<blockquote>` | Cita extensa |
| `<cite>` | Referencia |

---

## 📌 EJEMPLO

```html
<blockquote>
  “La gastronomía peruana es una de las mejores del mundo.”
</blockquote>

<p>
  Fuente:
  <cite>Cocina Peruana</cite>
</p>
```

---

# 💻 CÓDIGO Y TEXTO TÉCNICO

Se utilizan:

| Etiqueta | Función |
|---|---|
| `<code>` | Fragmento de código |
| `<pre>` | Mantiene espacios y saltos |

---

## 📌 EJEMPLO

```html
<pre>
<code>
<h1>Hola Mundo</h1>
</code>
</pre>
```

---

# ➖ LÍNEAS Y SALTOS

| Etiqueta | Función |
|---|---|
| `<br>` | Salto de línea |
| `<hr>` | Línea horizontal |

---

## 📌 EJEMPLO

```html
<p>
Primera línea<br>
Segunda línea
</p>

<hr>
```

---

# 🚀 EJEMPLO PRÁCTICO INTEGRADOR

## 📌 INDICACIONES

En la carpeta raíz crear una carpeta llamada:

```text
ejercicio_01
```

Dentro de la carpeta crear el archivo:

```text
index.html
```

Dentro del archivo `index.html` desarrollar una receta de cocina utilizando:

✅ estructura fundamental  
✅ estructura semántica  
✅ encabezados  
✅ párrafos  
✅ listas  
✅ citas  
✅ código  
✅ líneas y saltos  

---

# ✅ RESULTADO FINAL

El archivo `index.html` contendrá una receta completa aplicando todas las etiquetas trabajadas hasta el momento.