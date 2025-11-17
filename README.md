<div align="center">
  <img width="300" height="300" alt="UPC_logo_transparente" src="https://github.com/user-attachments/assets/19ec3b71-d2c6-4c4b-939f-dc5cc951dd94" />

</div>

<div align="center">
Universidad Peruana de Ciencias Aplicadas

##  Ingeniería de Software

## Ciclo 05

## Aplicaciones Web -  7468

## 
**Profesor:** Ángel Augusto Velásquez Núñez  
## INFORME DE Trabajo 
**Startup:** RentallPE  


| Integrante                        | Código     |
| --------------------------------- | ---------- |
| Saravia Huaricancha, Arturo Axel  | U202312447 |
| Cumba Rengifo, Leonardo Raúl      | U202311912 |
| Pérez Tuesta, Gabriel             | U202321281 |
| Torrejón Navarro, Braulio Rodrigo | U201711828 |



</div>


# Parte 1: ¿Que es el desarrollo web?

## ¿Qué es el desarrollo web?
El **desarrollo web** es el proceso de **crear, mantener y optimizar** sitios y aplicaciones web.  
Incluye tanto la parte visible para el usuario (**frontend**) como la lógica interna que maneja datos y procesos (**backend**).

---

##  Componentes principales

###  Frontend
La parte que los usuarios ven e interactúan.  
Incluye:
- **HTML** (estructura)
- **CSS** (estilos)
- **JavaScript** (interactividad)
- Frameworks: **React**, **Vue**, **Angular**, entre otros.
---



# ¿Qué es JSFiddle?

**JSFiddle** es un entorno de pruebas online que permite escribir y ejecutar código **HTML**, **CSS** y **JavaScript** directamente desde el navegador.

### Características principales
- Ideal para aprender, experimentar y compartir ejemplos sin necesidad de configurar un proyecto local.
- Cada proyecto se llama **fiddle** y puede guardarse y compartirse mediante un enlace único.
- Perfecto para probar ideas rápidas, crear demos o pedir ayuda en foros.
---

![dadadadadad](https://github.com/user-attachments/assets/0a074772-809c-43a0-902a-5156044232b9)

Video sobre la introduccion:
https://youtu.be/5DU6wJm21i0




# Parte 3: Fundamentos de Estructura y Navegación en HTML

## Objetivo 


Dominar los elementos esenciales de HTML para **organizar información** mediante listas, **insertar contenido visual** accesible con imágenes y **conectar documentos** web a través de enlaces, permitiendo la creación de páginas web estructuradas y navegables.
---
##  Teoría

### 1. Listas (`<ul>`, `<ol>` y `<li>`)

Sirven para agrupar información. Siempre requieren una etiqueta contenedora y etiquetas para los ítems.

* **`<ul>` (Unordered List):** Crea una lista desordenada con **viñetas** (puntos). Se usa cuando el orden de los elementos no altera el sentido.
* **`<ol>` (Ordered List):** Crea una lista ordenada con **números** o letras. Se usa cuando la secuencia es importante (paso 1, paso 2...).
* **`<li>` (List Item):** Es cada ítem individual. Va anidado dentro de `<ul>` u `<ol>`.

### 2. Imágenes (`<img>`)

Permite incrustar contenido visual. Es una etiqueta "vacía" (no tiene cierre `</img>`).

* **`src` (Source):** Atributo obligatorio que indica la **ruta** o URL donde se encuentra la imagen.
* **`alt` (Texto Alternativo):** Atributo crucial para accesibilidad y SEO. Describe la imagen si no carga o para lectores de pantalla. (Si es decorativa, usar `alt=""`).
* **`width` / `height`:** Definen el ancho y alto para reservar el espacio visual.

### 3. Enlaces (`<a>`)

Es el elemento "ancla" (*Anchor*) que permite la navegación (hipertexto).

* **`href` (Hypertext Reference):** Atributo obligatorio que define el **destino** (URL) al que se dirige el usuario al hacer clic.
* **Contenido (Texto ancla):** Lo que va entre `<a>` y `</a>` es lo que el usuario ve y puede cliquear.
* **`target="_blank"`:** Atributo opcional que fuerza al navegador a abrir el enlace en una **pestaña nueva**.



# Parte 4: Introducción a CSS

## Objetivo
Explicar qué es CSS, cómo funciona su sintaxis y mostrar ejemplos prácticos aplicados a una página web sencilla.

---

## Teoría

### ¿Qué es CSS?
CSS significa **Cascading Style Sheets** (Hojas de Estilo en Cascada).  
Su función principal es separar el contenido (HTML) del diseño (CSS).

Con CSS se puede:
- Cambiar colores, tamaños y fuentes.
- Definir márgenes y espacios.
- Adaptar el diseño a distintos dispositivos (PC, tablet, móvil).
- Crear animaciones y transiciones.

Ejemplo cotidiano: Facebook se ve distinto en celular, tablet y computadora, gracias a CSS.

---

### Anatomía de CSS
Un bloque de CSS se compone de:

1. **Selector**: indica qué elemento HTML se va a modificar (`p`, `h1`, `.clase`, `#id`).
2. **Llaves `{ }`**: delimitan el bloque de estilos.
3. **Propiedades**: características que queremos cambiar (`color`, `font-size`, `margin`).
4. **Valores**: el resultado que asignamos a la propiedad (`blue`, `20px`, `center`).

Ejemplo:

```css
p {
  color: blue;
  font-size: 18px;
}
```

### ¿Por qué en cascada?
CSS aplica siempre la última regla definida para un mismo selector.

Ejemplo:

```css
p { color: red; }
p { color: blue; }
```
El párrafo será azul, porque CSS toma la última regla.
### Ejemplos prácticos
Ejemplo 1: Estilos básicos en <style>

```HTML
<!DOCTYPE html>
<html>
<head>
  <style>
    body {
      background-color: lightblue;
      font-family: Arial, sans-serif;
    }
    h1 {
      color: darkblue;
      text-align: center;
    }
    p {
      margin: 20px;
      padding: 10px;
      border: 2px solid gray;
      text-align: justify;
    }
  </style>
</head>
<body>
  <h1>Mi página con CSS</h1>
  <p>Este párrafo tiene estilo aplicado con CSS.</p>
</body>
</html>
```
Ejemplo 2: Uso de clases

```HTML
<h1 class="primario">Título principal</h1>
<h1>Título secundario</h1>

<style>
  .primario {
    color: blueviolet;
  }
</style>
```
Ejemplo 3: Flexbox para alinear elementos
```HTML
<div class="diver">
  <div><h1>Prueba 1</h1></div>
  <div><h1>Prueba 2</h1></div>
</div>

<style>
  .diver {
    display: flex;
    justify-content: space-around;
    align-items: center;
  }
  .diver h1 {
    border: 1px solid gray;
    padding: 10px;
  }
</style>


```
Ejemplo 4: Grid Layout
```HTML
<div class="grid">
  <div>Bloque 1</div>
  <div>Bloque 2</div>
</div>

<style>
  .grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 20px;
  }
</style>

```
Se crean dos columnas iguales con separación.
---
## Conclusión
CSS es sencillo de aprender y muy poderoso.
Con unas pocas líneas podemos transformar una página básica en algo atractivo y responsivo.
En próximos capítulos veremos cómo organizar mejor los estilos en archivos externos y cómo aplicar buenas prácticas.

---
## Elaboración
# Universidad Peruana de Ciencias Aplicadas

**Carrera:** Ingeniería de Software  
**Curso:** 1ASI0730 Aplicaciones Web  
**Período:** 202520  

**Equipo:** RentalPE 
**Líder:** Braulio [Apellido]  
**Integrantes:** [Nombres y Apellidos]  
**Fecha de entrega:** Domingo 16 de Noviembre del 2025



