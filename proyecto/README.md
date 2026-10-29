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
* **Palabra del día:** Contexto.

---

## 📌 UD3 · Estructura HTML
 
Faltan metadatos completos en el <'head'>: Le faltan los elementos <'meta name="description"'>, <'meta name="keywords"'> y <'meta name="author"'> para la información de buscadores y autoría. Además, el atributo charset="UTF-8" debe ir como primer elemento dentro de <'head'> antes que el <'title'>. 
Estructura por bloques agrupados (<'div'>) y etiquetas semánticas de bloque: El contenido del <'body'> tiene los elementos sueltos sin agrupar en bloques <'div'> comentados por secciones. 
También le faltan elementos requeridos en esta unidad como el comentario <'!-- NAV: aquí irá el menú (UD4) --'>, el bloque de cita <'blockquote'>, la ficha con <'pre'> y separadores <'hr'> entre bloques temáticos. 

## 🗺️ Mapa del sitio

| Fichero | title | Qué contiene |
|---|---|---|
| `index.html` | `Inicio \| Coches clásicos y deportivos` | Portada: presentación, lista de los cuatro coches, foto del Porsche 911, opinión, ficha de datos y enlaces oficiales. |
| `coches.html` | `Catálogo \| Coches clásicos y deportivos` | Todos los elementos de `datos.xml`: un bloque por coche con año, potencia, aceleración, velocidad máxima y tipo, y un resumen en columnas. |
| `historia.html` | `Historia \| Coches clásicos y deportivos` | Historia de los cuatro coches por décadas, línea del tiempo y mi opinión en una cita. |
| `porsche-911.html` | `Porsche 911 Carrera \| Coches clásicos y deportivos` | Mi coche favorito: por qué me gusta, ficha técnica y un poco de historia. |

### Errores del validador W3C
 
| Página | Errores que dio el validador | Cómo los corregí |
|---|---|---|
| `index.html` | Error en imagen por tener espacios y tambien errores por poner <'dev'> mas de los que tenia abiertos| Quitando espacios y quitando los <'dev'> |
| `coches.html` | Error en la foto por poner espacios | Quitando espacios |
| `historia.html` | Nada | Nada |
| `porsche-911.html` | Nada | Nada |

### Qué he hecho en esta unidad
 
En esta unidad he pasado de una página básica a un sitio de cuatro páginas con estructura HTML completa: DOCTYPE, `html lang="es"` y un `head` con codificación, título, descripción, palabras clave y autor. En el `body` he organizado el contenido en bloques `div` comentados, con una jerarquía de títulos sin saltos, separadores `hr`, citas con `blockquote`, fichas con `pre` y entidades como `&copy;` o `&euro;`. He ido haciendo un commit por cada mejora o página nueva para que el historial cuente el proceso. Todavía no hay enlaces entre páginas porque el menú se añadirá en la UD4.
