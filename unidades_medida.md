# UNIDADES DE MEDIDA EN CSS

# ¿Qué son las unidades de medida?

Las unidades de medida sirven para definir tamaños dentro de una página web.

Se usan para:

- ancho
- alto
- texto
- márgenes
- espacios
- imágenes

---

# Ejemplo básico

```css
p{
    font-size: 20px;
}
```

Aquí:

```txt
20px
```

significa que el texto tendrá tamaño 20.

---

# Tipos de unidades

Existen 2 grupos principales:

- unidades absolutas
- unidades relativas

---

# 1. Unidades Absolutas

Son tamaños fijos.

No cambian dependiendo de la pantalla.

---

# PX

`px` significa:

```txt
pixel
```

Es la unidad más usada.

---

# Ejemplo

```css
h1{
    font-size: 40px;
}
```

El texto medirá exactamente 40 píxeles.

---

# ¿Cuándo usar PX?

Se usa para:

- bordes
- tamaños pequeños
- ajustes precisos

---

# Problema de PX

No se adapta fácilmente a diferentes pantallas.

Por eso no siempre es recomendable usarlo en todo.

---

# 2. Unidades Relativas

Son unidades que cambian dependiendo del tamaño de pantalla o del elemento padre.

Ayudan a crear diseños responsive.

---

# REM

`rem` se basa en el tamaño del texto principal de la página.

Normalmente:

```txt
1rem = 16px
```

---

# Ejemplo

```css
p{
    font-size: 2rem;
}
```

Resultado:

```txt
2rem = 32px
```

---

# ¿Por qué usar REM?

Porque:

- se adapta mejor
- facilita responsive
- mejora accesibilidad

---

# EM

`em` depende del tamaño del elemento padre.

---

# Ejemplo

```css
div{
    font-size: 20px;
}

p{
    font-size: 2em;
}
```

Resultado:

```txt
2em = 40px
```

Porque toma como referencia los 20px del `div`.

---

# Diferencia entre REM y EM

## REM

Se basa en:

```txt
html
```

## EM

Se basa en:

```txt
elemento padre
```

---

# PORCENTAJE %

Se basa en el tamaño del contenedor padre.

---

# Ejemplo

```css
div{
    width: 50%;
}
```

El ancho ocupará la mitad del contenedor.

---

# VW

`vw` significa:

```txt
viewport width
```

Se basa en el ancho de la pantalla.

---

# Ejemplo

```css
h1{
    font-size: 10vw;
}
```

El texto cambia según el tamaño de pantalla.

---

# VH

`vh` significa:

```txt
viewport height
```

Se basa en el alto de la pantalla.

---

# Ejemplo

```css
section{
    height: 100vh;
}
```

La sección ocupará toda la altura de la pantalla.

---

# ¿Qué es viewport?

Viewport significa:

```txt
área visible de la pantalla
```

Es el espacio donde se muestra la página web.

---

# Responsive Design

Responsive significa que una página se adapta a:

- celulares
- tablets
- computadoras

---

# ¿Por qué es importante?

Porque cada dispositivo tiene tamaños distintos.

---

# Ejemplo Responsive

```css
img{
    width: 100%;
}
```

La imagen ocupará todo el ancho disponible.

---

# Unidades más usadas

| Unidad | Significado | Uso |
|---|---|---|
| px | píxel | tamaños fijos |
| rem | relativo al html | textos responsive |
| em | relativo al padre | tamaños internos |
| % | porcentaje | tamaños flexibles |
| vw | ancho pantalla | diseño responsive |
| vh | alto pantalla | secciones completas |

---

# Recomendaciones para principiantes

## Usa PX para:

- bordes
- detalles pequeños

---

## Usa REM para:

- textos
- tamaños generales

---

## Usa % para:

- contenedores
- imágenes

---

## Usa VH y VW para:

- pantallas completas
- diseños responsive

---

# Ejemplo completo

```css
body{
    font-size: 16px;
}

h1{
    font-size: 3rem;
}

.container{
    width: 80%;
}

img{
    width: 100%;
}

section{
    height: 100vh;
}
```

---

# Resumen rápido

## PX

Tamaño fijo.

---

## REM

Se basa en el tamaño principal del sitio.

---

## EM

Se basa en el tamaño del padre.

---

## %

Se basa en el contenedor.

---

## VW y VH

Se basan en el tamaño de pantalla.

---

# Conclusión

Las unidades de medida ayudan a controlar tamaños dentro de una página web.
