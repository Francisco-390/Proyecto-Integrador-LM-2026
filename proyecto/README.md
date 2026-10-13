# 🚀 Tarea Módulo 1 - Lenguaje de Marcas (LdM)

**Asignatura:** Lenguaje de Marcas y Sistemas de Gestión de Información  
**Alumno:** Francisco Martínez  
**Usuario de GitHub:** `Francisco-390`  
**Repositorio:** `Proyecto-Integrador-LM-2026`  

---

## 📌 Informes y Datos de la Entrega (Reto 1 y Reto 4)

* **Tema elegido:** Coches Clásicos o Deportivos.
* **¿Por qué este tema?:** He elegido este tema porque me gustan los coches, ademas de tener suficiente infromacion para rellenar paginas y me resulta un tema facil para esta tarea.
* **Palabra del día:** Meta.
* **Qué he hecho en esta entrega:** 3º Entrega: he seguido el archivo HTML, enlazado la imagen.

---

## 🗂️ 1. Estructura del Proyecto

Tu repositorio local y remoto debe contener obligatoriamente la siguiente estructura de archivos y carpetas:

```text
Lenguaje-de-marcas-Tarea-Modulo-1/
└── proyecto/
    ├── index.html
    ├── datos.xml
    ├── img/
    │   └── (imágenes del proyecto)
    └── README.md
```

---

## 🛠️ 2. Resumen de Retos y Requisitos

### 🟢 Reto 1: Configuración Inicial del Proyecto
1. Crear la estructura de carpetas `proyecto/`, `proyecto/img/`, `index.html`, `datos.xml` y `README.md`.
2. Completar los datos de la cabecera de este `README.md` (nombre, usuario, tema, motivo y palabra del día).
3. **Commit inicial obligatorio:**
   ```bash
   git commit -m "feat(proyecto): initial project setup"
   git push
   ```
   *⚠️ Límite de entrega del Reto 1: Jueves 08/10/2026 antes de las 14:30.*

---

### 🔵 Reto 2: Desarrollo de la Página Web (`index.html`)
* [ ] Doctype HTML5 (`<!DOCTYPE html>`) y elemento raíz con idioma español (`<html lang="es">`).
* [ ] Sección `<head>` con `<meta charset="UTF-8">`, viewport y `<title>Tema - Francisco Martínez</title>`.
* [ ] Comentario en HTML con tu nombre completo y la fecha actual.
* [ ] Encabezado principal `<h1>` con el nombre de tu proyecto y al menos un `<h2>` para una sección.
* [ ] Mínimo 2 párrafos introductorios con texto en negrita (`<strong>`) y cursiva (`<em>` o `<i>`).
* [ ] Una imagen almacenada dentro de `proyecto/img/` con atributos `src`, `alt` descriptivo y `width`.
* [ ] Una lista (`<ul>` o `<ol>`) con al menos 3 elementos clave de tu tema (deben coincidir con el XML).
* [ ] Dos enlaces (`<a>`):
  1. Un enlace externo a una web real sobre la temática (con atributo `title`).
  2. Un enlace interno hacia el archivo `datos.xml`.
* [ ] Código limpio: sangría de 2 espacios por nivel, etiquetas cerradas y correctamente anidadas.
* [ ] Probar visualización con la extensión **Live Server**.

---

### 🟡 Reto 3: Creación del Archivo de Datos (`datos.xml`)
* [ ] Prólogo XML en la primera línea: `<?xml version="1.0" encoding="UTF-8"?>`.
* [ ] Un comentario explicativo en la parte superior sobre los datos contenidos.
* [ ] **Elemento raíz único** con el atributo de propietario: `<catalogo propietario="Francisco-390">`.
* [ ] Al menos 3 elementos hijos principales (mismos elementos de la lista HTML), cada uno con un atributo `id` único (ej. `id="101"`, `id="102"`, `id="103"`).
* [ ] Cada elemento hijo debe incluir al menos 3 sub-elementos. Uno de ellos debe ser **numérico con punto decimal y atributo de unidad** (ej. `<duracion unidad="min">3.5</duracion>` o `<precio moneda="EUR">12.95</precio>`).
* [ ] Incluir al menos un **elemento vacío** (ej. `<destacado/>`).
* [ ] Documento bien formado con **0 errores** en el panel *Problemas* de VS Code (`Ctrl+Shift+M`).

---

### 🔴 Reto 4: Revisión Final y Entrega
1. Verificar enlaces, imágenes y renderizado con Live Server.
2. Confirmar 0 errores sintácticos en `datos.xml`.
3. Completar el apartado **"Qué he hecho en esta entrega"** en este `README.md`.
4. **Commit final obligatorio:**
   ```bash
   git commit -m "feat(proyecto): first html and xml delivery"
   git push
   ```
5. Entregar la URL de tu repositorio de GitHub (`https://github.com/Francisco-390/Lenguaje-de-marcas-Tarea-Modulo-1`) en la plataforma Canvas.

---

## 📜 3. Reglas Estrictas del Historial de Git / Commits

Para asegurar la validez del trabajo, debes cumplir las siguientes normas de control de versiones:

1. **Mínimo 6 commits** en total utilizando formato convencional (`feat:`, `fix:`, `docs:`, `style:`, `refactor:`, `chore:`).
2. **2 Commits obligatorios con mensaje exacto:**
   * `feat(proyecto): initial project setup`
   * `feat(proyecto): first html and xml delivery`
3. **Distribución de cambios por archivo:**
   * `index.html` debe verse modificado en al menos **3 commits distintos**.
   * `datos.xml` debe verse modificado en al menos **2 commits distintos**.
4. **Subidas continuas:** Realizar `git push` tras cada reto completado (se requieren **al menos 4 subidas/pushes distintos** al repositorio remoto).
5. **Prohibido reescribir el historial:** No usar `git push --force`, `rebase` o `commit --amend` tras publicar commits.

---

## 📋 4. Lista de Comprobación Final (Checklist)

- [ ] Repositorio público con el nombre correcto.
- [ ] Archivos creados en la ruta `proyecto/` (`index.html`, `datos.xml`, `img/`, `README.md`).
- [ ] La palabra del día está incluida en el `README.md` y subida antes de las 14:30.
- [ ] Coincidencia exacta entre los 3 elementos de la lista de `index.html` y los de `datos.xml`.
- [ ] Atributo `propietario="Francisco-390"` configurado en la etiqueta raíz de `datos.xml`.
- [ ] Mínimo de 6 commits y 4 pushes registrados en GitHub.
- [ ] Preparado para la **defensa presencial de 5 minutos** (explicar código, justificar commits y corregir un error introducido en vivo).