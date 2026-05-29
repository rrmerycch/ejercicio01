# CSS (Cascading Style Sheets)

CSS es un lenguaje que nos permite dar estilos a nuestros elementos HTML, como colores, tamaños, posiciones, escalas, formatos y transiciones.

---

# Maneras de aplicar CSS a nuestro documento HTML

## 1. En línea

Esta manera de aplicar CSS consiste en usar el atributo `style` directamente dentro de una etiqueta HTML.

```html
<p style="color:pink; font-size:23px;">
    Este es el texto
</p>
```

---

## 2. Embebido

Este tipo de CSS permite usar la etiqueta `<style>` dentro del documento HTML para aplicar estilos.

Por convención, la etiqueta `<style>` se coloca dentro de la etiqueta `<head>`.

```html
<head>
    <style>
        p{
            color: blue;
            font-size: 20px;
        }
    </style>
</head>
```

---

## 3. Archivo externo

Este método consiste en crear un archivo `.css` separado y enlazarlo al documento HTML mediante la etiqueta `<link>`.

```html
<head>
    <link rel="stylesheet" href="style.css">
</head>
```

### Archivo `style.css`

```css
p{
    color:red;
    font-size:22px;
}
```
