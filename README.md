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


# Tabla de Videos Explicativos

| Parte / Capítulo | Tema / Sección                                | Enlace al Video                                                                 |
|------------------|-----------------------------------------------|---------------------------------------------------------------------------------|
| Parte 1          | Introducción al desarrollo web y JSFiddle     | [https://youtu.be/5DU6wJm21i0](https://youtu.be/5DU6wJm21i0)                     |
| Parte 2          | Introducción a HTML                           | [https://youtu.be/aF9WwEA8njA](https://youtu.be/aF9WwEA8njA)                     |
| Parte 3          | Fundamentos de estructura y navegación en HTML| https://youtu.be/FF4m9LQd9HE                            |
| Parte 4          | Introducción a CSS                            | [https://youtu.be/owa--QCDIPk?si=G_afU5FmXVHjpZHd](https://youtu.be/owa--QCDIPk?si=G_afU5FmXVHjpZHd) |
| Parte 5       | Crear una página web sencilla (HTML + CSS)    | [https://youtu.be/UExaAIWPufk](https://youtu.be/UExaAIWPufk)                     |
| Parte 6       | Consejos y proximos pasos  | https://youtu.be/cQO8vDSFCQM                    |



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

# Parte 2: Introducción a HTML

## Objetivo
Explicar qué es HTML, cómo funciona su estructura básica y cómo se utiliza para construir el contenido de una página web.

---

## ¿Qué es HTML?

HTML significa **HyperText Markup Language** (Lenguaje de Marcado de Hipertexto).  
Es el **lenguaje base de toda página web**, responsable de definir la estructura y el contenido: textos, imágenes, botones, enlaces, tablas, formularios y más.

HTML **no es un lenguaje de programación**, sino un lenguaje de marcado que organiza la información en bloques llamados **elementos** o **etiquetas**.

Ejemplos de etiquetas:  
- `<h1>` para títulos  
- `<p>` para párrafos  
- `<img>` para imágenes  
- `<a>` para enlaces  
- `<div>` para contenedores  

---

## Estructura básica de un documento HTML

Un archivo HTML típico contiene:

```html
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Mi primera página</title>
</head>
<body>
  <h1>Hola mundo</h1>
  <p>Este es mi primer documento HTML.</p>
</body>
</html>
```
Explicación de cada parte:
- `<!DOCTYPE html>` Indica que el documento usa HTML5
- `<html>` → Contenedor raíz de toda la página. 
- `<head>` → Contiene metadatos (título, codificación, estilos, scripts).
- `<body>` → Contiene todo lo visible por el usuario.

## Estructura básica de un documento HTML
Una etiqueta está compuesta por:
```html
<p>Este es un párrafo</p>
```

Video Explicativo: https://youtu.be/aF9WwEA8njA


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

Video explicativo: https://youtu.be/FF4m9LQd9HE

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

## Conclusión
CSS es sencillo de aprender y muy poderoso.
Con unas pocas líneas podemos transformar una página básica en algo atractivo y responsivo.
En próximos capítulos veremos cómo organizar mejor los estilos en archivos externos y cómo aplicar buenas prácticas.

Video sobre la explicacion:
https://youtu.be/owa--QCDIPk?si=G_afU5FmXVHjpZHd

---
# Capítulo 5 – Crear una Página Web Sencilla

## Introducción
En esta quinta lección vamos a crear un proyecto personal: una página web sencilla utilizando **HTML** y **CSS**.  
El ejemplo será un perfil personal que muestra un título, el nombre del estudiante, su edad y una sección con sus gustos.

---

## Estructura HTML

Toda la página estará contenida dentro de un `div`, que funciona como un **contenedor del contenido**.

### Encabezado Principal
- Utilizamos la etiqueta `h1` para el título principal:  
  **Perfil personal** (`<h1>`)

- Luego agregamos dos párrafos (`<p>`) con información personal:
  - *Mi nombre es* (en `<strong>`) seguido del nombre.  
  - *Mi edad es* (también en `<strong>`) seguido de la edad.  

Ambos párrafos usan la clase `.data`, que será estilizada desde CSS.

### Sección de Gustos
Después del encabezado, se incluye otro contenedor (`div`) con clase `.contenedor`. Dentro de él:

- Un separador `<hr>`.
- Un subtítulo `<h2>` llamado **Mis gustos**.
- Un `div` adicional que contiene:
  - Un subtítulo `<h3>` (por ejemplo, *Lectura de cómics*).
  - Una imagen usando la etiqueta `<img>`, con la clase `.imagen1`, el atributo `src` con la dirección de la imagen y el atributo `alt`.

Luego se repite la estructura para un segundo gusto:
- Un `<h3>` (por ejemplo, *Jugar videojuegos*).
- Otra etiqueta `<img>` con la misma clase `.imagen1`.

> Nota: La etiqueta `<img>` no necesita etiqueta de cierre.

---

## Estilos con CSS

En el archivo CSS se definen los estilos utilizando **selectores de etiquetas y clases**.

### Estilos Generales
- Se estiliza el `body` con un color de fondo usando un código hexadecimal.  
- Los colores pueden obtenerse de cualquier paleta disponible en internet.

### Estilo del Título Principal (`h1`)
El selector `h1` se utiliza directamente porque es una etiqueta:

```css
h1 {
  text-align: center;
}
```

### Estilos de los Datos Personales
Para referenciar clases en CSS se utiliza un punto antes del nombre:
```css
.data {
  text-align: center;
  font-size: 20px;
  color: #555;
}

```
El tamaño de letra se puede ajustar según preferencia.

### Estilos de las Imágenes
La clase  define
```css
.imagen1 {
  height: 400px;
}

```
Este valor puede modificarse según la estética deseada.

Estilos del Contenedor (.contenedor)
El contenedor que agrupa los gustos se centra con:
```css
.contenedor {
  text-align: center;
}

```
Todo lo que esté dentro del contenedor se ajustará a este estilo.

Esta página web de perfil personal es un ejemplo básico para practicar HTML y CSS.
Con unos pocos elementos (div, h1, h2, h3, p, img) y clases simples, es posible estructurar y estilizar contenido web.
El objetivo es que los estudiantes se interesen por la programación web y puedan expandir el proyecto con sus propios datos, imágenes y estilos.

Video explicativo: https://youtu.be/UExaAIWPufk
---
# Capítulo 6 – Mejores Prácticas y Continuidad en el Desarrollo Web

## Introducción
En esta sesión final no se trata de aprender un nuevo código, sino de **reflexionar** sobre cómo llevar nuestro trabajo al siguiente nivel.  
Hablaremos de **mejores prácticas**, **errores comunes** y **dónde continuar aprendiendo**.

---

## Mejores Prácticas

El desarrollo web no basta con que el código funcione, debe ser:
- **Sostenible**
- **Legible**
- **Eficiente**

Siempre piensa en el siguiente desarrollador que leerá tu código (muy probablemente serás tú mismo en 6 meses).

### Tres palabras clave:
1. **Limpieza semántica**  
   - Usar etiquetas HTML con significado: `<header>`, `<footer>`, `<article>`.
2. **Modularidad en CSS**  
   - Evitar estilos globales desordenados.  
   - Organizar CSS para que cada componente sea independiente.
3. **Comentarios útiles**  
   - Documentar las partes complejas del código.  
   - Evitar comentarios obvios, enfocarse en lo que realmente necesita explicación.

---

## Errores Comunes

1. **Dependencia de un solo navegador**  
   - Probar siempre en **Chrome, Firefox y Safari**.  
   - Lo que funciona en uno puede romperse en otro.

2. **Código “spaghetti”**  
   - Mezclar lógica de JavaScript dentro de HTML o viceversa.  
   - Mantener la **separación de responsabilidades**:  
     - HTML → estructura  
     - CSS → estilo  
     - JavaScript → comportamiento

---

## Consejos Claves y Referencias

### 1. Validar tu código
- Regla de oro: usar herramientas de validación para revisar sintaxis de **HTML, CSS y JavaScript**.  
- Detecta errores que el navegador o tus ojos pueden pasar por alto.  
- Un código validado es un código robusto.

### 2. Explorar la documentación en MDN
- **MDN (Mozilla Developer Network)** es la biblia del desarrollo web.  
- Fuente confiable y detallada para propiedades de CSS y métodos de JavaScript.  
- Siempre consulta MDN cuando tengas dudas.

---

## Control de Versiones y Futuro Profesional

- Adoptar el uso de **Git** y plataformas como **GitHub**.  
- Beneficios:
  - Historial de tu código.
  - Volver a versiones anteriores si cometes errores.
  - Trabajo en equipo más organizado.
- **Portafolio visible**:  
  - Publicar tu código en GitHub es esencial para entrevistas y empleadores.  
  - Si tu código no está en GitHub, es como si no existiera.  
  - GitHub es la plataforma más popular de repositorios y control de versiones en el mundo.

---

## Conclusión
La lección 6 nos invita a reflexionar sobre cómo mejorar continuamente como desarrolladores:  
- Aplicar **mejores prácticas**.  
- Evitar **errores comunes**.  
- Usar **herramientas de validación** y **documentación confiable**.  
- Adoptar **Git y GitHub** para crecer profesionalmente y construir un portafolio sólido.

Video explicativo:  https://youtu.be/cQO8vDSFCQM
---


## Elaboración
# Universidad Peruana de Ciencias Aplicadas

**Carrera:** Ingeniería de Software  
**Curso:** 1ASI0730 Aplicaciones Web  
**Período:** 202520  

**Equipo:** RentalPE 
**Fecha de entrega:** Domingo 16 de Noviembre del 2025



