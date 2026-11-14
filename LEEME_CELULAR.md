# CALIFICATED CELULAR V1 — guía rápida

Dos funciones: **Nombrar lista** y **Hojas de respuestas** (lectura con la cámara). La pestaña **Datos** mueve la información entre tu PC y el celular.
Funciona con tu **CALIFICATED PC V11 tal como está**: no hay que cambiar nada en la PC.

## 1. Instalar en el celular (una sola vez)
La cámara en vivo solo funciona si la página se abre con https. La forma más fácil y gratis es GitHub Pages:

1. Entra a github.com, crea una cuenta y un repositorio **público** (por ejemplo `calificated-cel`).
2. **Add file → Upload files** y arrastra los 5 archivos de la carpeta del ZIP: `index.html`, `sw.js`, `manifest.webmanifest`, `icon-192.png`, `icon-512.png`. Pulsa **Commit changes**.
3. **Settings → Pages** → Source: *Deploy from a branch* → rama `main`, carpeta `/ (root)` → **Save**.
4. En 1–2 minutos tu app queda en `https://TU-USUARIO.github.io/calificated-cel/`.
5. Ábrela en Chrome del celular → menú ⋮ → **Instalar aplicación** (o *Agregar a pantalla de inicio*). Ábrela una vez con internet; después funciona sin internet.

El repositorio solo lleva el programa. **Tus alumnos y calificaciones nunca se suben a GitHub**: viven en el celular, en tu PC y en tu chat de WhatsApp.

Sin GitHub: puedes abrir `index.html` directo desde el celular. Nombrar lista y “Tomar foto” / “Elegir imagen” funcionan; la cámara en vivo no.

## 2. Ciclo de trabajo
**PC → celular** (cuando cambien alumnos, claves o imprimas hojas nuevas)
1. PC: *Exportar / Respaldo* → **Respaldo (.json)**.
2. Mándalo por WhatsApp a tu propio número, ábrelo/guárdalo en el celular.
3. Celular → **Datos → Elegir respaldo**. Quedan cargados grupos, alumnos, claves y hojas impresas.

**En el salón**
- **Nombrar lista:** “Una por una” (avanza solo al siguiente) o “Toda la lista”. Tocar el mismo estado otra vez lo quita.
- **Hojas:** abre la cámara y muestra la hoja completa (se ven los 4 cuadros de las esquinas, el hueco abajo a la derecha). Lee sola, suena y muestra nombre, tipo, aciertos y calificación. Las casillas con borde punteado son dudas: tócalas para corregir. Hojas sin leer: “Captura a mano”.

**Celular → PC**
1. Celular → **Datos** → *Asistencias (.csv)* y *Hojas leídas (.csv)* → compartir a tu WhatsApp.
2. PC: asistencias en *Exportar / Respaldo → Importar CSV*; hojas en *Examen interno → Cargar lecturas de hojas (.csv)*.

Importar el mismo archivo dos veces no duplica nada. Al traer un respaldo nuevo de la PC, el celular limpia lo que la PC ya trae.

## 3. Cuidados
- La asistencia que mandas **reemplaza el registro de ese alumno en ese día** (conserva comportamiento, participación, tarea, trabajo, sello y observación que tenía el respaldo). Si capturaste algo en la PC *después* de bajar el respaldo, vuelve a hacer el respaldo antes de pasar lista.
- La PC pide confirmar antes de importar; descarga un respaldo antes si quieres estar tranquilo.
- Para leer bien: hoja plana, de frente, con buena luz y sin sombras de tu mano; marca bien rellenada y borrado completo.
- Hojas de otro equipo (códigos no registrados en tu respaldo) se leen igual, pero eliges de quién son.
