🎵 SongLab – Taller de DOM

Maqueta base en HTML + CSS (sin JavaScript) para practicar manipulación del DOM.

Este proyecto simula un gestor de canciones donde cada canción tiene:

Título
Autor
Botón de eliminar
🧩 Estructura del proyecto
/proyecto
│── index.html
│── styles.css
│── dark.css
│── README.md
🎯 Objetivo del taller

A partir de esta maqueta, implementar funcionalidad usando JavaScript y el DOM.

⚙️ Funcionalidades a desarrollar
1. ➕ Crear canción
Tomar los valores de los inputs:
Título
Autor
Crear dinámicamente una nueva tarjeta (.song-card)
Insertarla en el contenedor .songs-grid
2. 🔍 Buscar canciones
Usar el mismo formulario
Filtrar canciones por:
Título
Autor
Mostrar solo las coincidencias

💡 Tip:

Puedes usar .includes() para comparar texto
3. 🔤 Ordenar alfabéticamente
Ordenar las canciones por:
Título (A-Z)
Reordenar el DOM sin recargar la página
4. ❌ Eliminar canción
Cada tarjeta tiene un botón "Eliminar"
Al hacer clic:
Eliminar ese elemento del DOM

💡 Tip:

Usa parentElement.remove()
5. 🌗 Modo Dark / Light
Usar el archivo dark.css
Activar/desactivar la clase:
<body class="dark-mode">
Con botones:
Light
Dark

💡 Tip:

classList.add() / classList.remove()
6. 🔢 Numeración automática
Actualizar los números de las canciones (01, 02, 03...)
Cada vez que:
Se agrega una canción
Se elimina una canción
Se ordena la lista
7. 📱 Comportamiento responsivo (ya incluido)
Analizar cómo funciona el layout con:
Grid
Flexbox
No modificar (solo entender)
🧠 Retos adicionales (opcional)
🟡 Validar que los campos no estén vacíos
🟡 Mostrar mensaje si no hay resultados en búsqueda
🟡 Evitar canciones duplicadas
🟡 Guardar canciones en localStorage
🟡 Animaciones al agregar/eliminar
🧪 Conceptos de DOM a practicar
querySelector
createElement
appendChild
remove
classList
addEventListener
innerHTML vs textContent
🚀 Resultado esperado

Una aplicación completamente funcional que permita:

Crear canciones
Buscarlas
Ordenarlas
Eliminarlas
Cambiar tema visual