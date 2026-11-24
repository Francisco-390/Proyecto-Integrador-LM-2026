# 🚀 Tarea Módulo 1 - Lenguaje de Marcas (LdM)
 
**Asignatura:** Lenguaje de Marcas y Sistemas de Gestión de Información  
**Alumno:** Francisco Martínez  
**Usuario de GitHub:** `Francisco-390`  
**Repositorio:** `https://github.com/Francisco-390/Proyecto-Integrador-LM-2026`
`Proyecto-Integrador-LM-2026` 
 
---
 
## 📌 Informes y Datos de la Entrega
 
* **Tema elegido:** Coches Clásicos o Deportivos.
* **¿Por qué este tema?:** He elegido este tema porque me gustan los coches, ademas de tener suficiente infromacion para rellenar paginas y me resulta un tema facil para esta tarea.
* **Palabra del día:** 

---

## 📌 UD3 · Estructura HTML
 
Faltan metadatos completos en el <'head'>: Le faltan los elementos <'meta name="description"'>, <'meta name="keywords"'> y <'meta name="author"'> para la información de buscadores y autoría. Además, el atributo charset="UTF-8" debe ir como primer elemento dentro de <'head'> antes que el <'title'>. 
Estructura por bloques agrupados (<'div'>) y etiquetas semánticas de bloque: El contenido del <'body'> tiene los elementos sueltos sin agrupar en bloques <'div'> comentados por secciones. 
También le faltan elementos requeridos en esta unidad como el comentario <'!-- NAV: aquí irá el menú (UD4) --'>, el bloque de cita <'blockquote'>, la ficha con <'pre'> y separadores <'hr'> entre bloques temáticos. 

## 🗺️ UD3 · Mapa del sitio

| Fichero | title | Qué contiene |
|---|---|---|
| `index.html` | `Inicio \| Coches clásicos y deportivos` | Portada: presentación, lista de los cuatro coches, foto del Porsche 911, opinión, ficha de datos y enlaces oficiales. |
| `coches.html` | `Catálogo \| Coches clásicos y deportivos` | Todos los elementos de `datos.xml`: un bloque por coche con año, potencia, aceleración, velocidad máxima y tipo, y un resumen en columnas. |
| `historia.html` | `Historia \| Coches clásicos y deportivos` | Historia de los cuatro coches por décadas, línea del tiempo y mi opinión en una cita. |
| `porsche-911.html` | `Porsche 911 Carrera \| Coches clásicos y deportivos` | Mi coche favorito: por qué me gusta, ficha técnica y un poco de historia. |

### UD3 · Errores del validador W3C
 
| Página | Errores que dio el validador | Cómo los corregí |
|---|---|---|
| `index.html` | Error en imagen por tener espacios y tambien errores por poner <'dev'> mas de los que tenia abiertos| Quitando espacios y quitando los <'dev'> |
| `coches.html` | Error en la foto por poner espacios | Quitando espacios |
| `historia.html` | Nada | Nada |
| `porsche-911.html` | Nada | Nada |

### UD3 · Qué he hecho en esta unidad
 
En esta unidad he pasado de una página básica a un sitio de cuatro páginas con estructura HTML completa: DOCTYPE, `html lang="es"` y un `head` con codificación, título, descripción, palabras clave y autor. En el `body` he organizado el contenido en bloques `div` comentados, con una jerarquía de títulos sin saltos, separadores `hr`, citas con `blockquote`, fichas con `pre` y entidades como `&copy;` o `&euro;`. He ido haciendo un commit por cada mejora o página nueva para que el historial cuente el proceso. Todavía no hay enlaces entre páginas porque el menú se añadirá en otro tema.

## 📌 UD5 · Tablas y formularios

* **Qué datos de tu tema vas a poner en la tabla (y en qué página):** Voy a poner en 'historia.html' una tabla con los hitos de cada coche: coche, año, qué ocurrió y país. Son datos reales de mi tema, como las fechas de presentación y de producción.

* **Para qué servirá tu formulario (contacto, reserva, inscripción, encuesta…):** El formulario estará en 'contacto.html' y servirá para que los visitantes me envíen dudas sobre los coches o me sugieran un modelo nuevo para añadir al catálogo.


### UD5 · Formulario de contacto
 
* **¿Por qué `post` y no `get`?:** Uso `post` porque los datos personales (nombre, correo y teléfono) viajan ocultos y no aparecen en la URL, mientras que con `get` cualquiera podría verlos en la barra del navegador.

* **URL que aparece al probar con `get`:** http://165.0.1.0:5500/proyecto/contacto.html?nombre=Francisco&correo=francisco%40gmail.com&tel=666333444&tipo=comentario&coche=otro&mensaje=La+p%C3%A1gina+es+una+locura%2C+adem%C3%A1s+est%C3%A1n+bien+elegidos+los+coches.&interes=historia&interes=datos-tecnicos&interes=fotos#

### UD5 · Errores del validador W3C
 
| Página | Errores que dio el validador | Cómo los corregí |
|---|---|---|
| `historia.html` (tabla) | Nada | Nada |
| `contacto.html` | Nada | Nada |
 
### UD5 · Qué he hecho en esta unidad
 
En esta unidad he añadido a mi web una tabla de datos y un formulario. En `historia.html` hay una tabla de hitos con `caption`, `thead`, `tbody`, `tfoot`, `colgroup`, cabeceras con `scope` y celdas combinadas con `rowspan` y `colspan`. En `contacto.html` he creado un formulario con `post`, tres `fieldset` con `legend`, controles con `name`, `id` y su `label`, y los ocho tipos de control pedidos. Por último he enlazado la página de contacto desde la portada, la he añadido al mapa del sitio y he validado las páginas con el validador del W3C, haciendo commits por cada parte.


## 📌 Tarea 6-7 · HTML5 semántico y CSS

### Estructura semántica

Las cinco páginas (`index.html`, `coches.html`, `historia.html`, `porsche-911.html` y `contacto.html`) usan `header` con el nombre de la web y un `nav` con los cinco enlaces, un único `main`, varias `section`, `article` para el contenido que se entiende solo (cada coche, cada etapa de la historia), `aside` para contenido secundario y `footer` con la firma `<p id="firma-francisco-390">`. He quitado todos los `div` de maquetación y los `style` en línea, y he cambiado `b` e `i` por `strong` y `em`.

### Formulario HTML5 (`contacto.html`)

Controles `email`, `tel`, `url`, `number`, `date`, `color` y `range`, además de `text`, `radio`, `checkbox`, `select` y `textarea`. Uso `placeholder`, `required`, `min`/`max`/`step` y dos `pattern` con su `title` (teléfono de 9 dígitos y matrícula española). Cada campo tiene su `label for`. En la columna lateral hay un `meter` con la potencia del Porsche 911 (385 de 500 CV).

### Multimedia e interactivos (`index.html`)

Un `video` con `controls`, `poster` y dos `source` (mp4 y webm) en `media/`, dos `figure` con `figcaption` en la portada y cuatro más en el catálogo, y una sección de preguntas frecuentes con tres `details`/`summary` (el primero con `open`) donde escribo etiquetas con las entidades `&lt;` y `&gt;`.

### Hoja de estilos

`css/estilos.css` está enlazada en las cinco páginas con `<link rel="stylesheet" href="css/estilos.css">`. Tiene tres bloques: base (tipografía y colores), maquetación (cabecera, navegación, secciones y artículos) y tablas, formulario e interactivos.

### Errores del validador W3C

| Página | Errores que dio el validador | Cómo los corregí |
|---|---|---|
| `index.html` | Nada | Nada |
| `coches.html` | Nada | Nada |
| `historia.html` | Nada | Nada |
| `porsche-911.html` | Nada | Nada |
| `contacto.html` | Nada | Nada |
| `css/estilos.css` | Nada | Nada |

Las capturas de la validación están en la carpeta `capturas/`.

### Qué he hecho en esta tarea

He convertido mi web de coches a HTML5 semántico en las cinco páginas, con navegación entre ellas y una firma con mi usuario. He mejorado el formulario con controles HTML5 y validación del navegador, y he añadido un vídeo, imágenes con pie de foto y preguntas frecuentes desplegables. Por último he creado la hoja de estilos externa y la he enlazado en todas las páginas. He ido subiendo cada parte con commits convencionales y un push al terminar cada reto.