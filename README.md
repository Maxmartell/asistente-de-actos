# Asistente de Actos

Aplicación web para armar la planimetría de un acto: ubicar sillas, mesas, escenario, atril y banderas en auditorios, aulas, salones en U y banquetes, y sentar a las personas según el orden de precedencia.

## Qué permite hacer

- Generar planos de auditorio (con bloques izquierda, centro y derecha, cada uno con sus filas y columnas), aula, salón en U y banquete.
- Arrastrar sillas, pasillos y objetos; agregar todos los pasillos que haga falta, verticales u horizontales.
- Girar y agrandar o achicar el escenario, la mesa, el atril y la bandera, y poner sillas encima para la mesa académica.
- Cargar una lista de invitados y asignarlos en orden: el lugar 0 es el centro de cada fila, los impares van a la derecha y los pares a la izquierda.
- Asignar por zona (izquierda, centro, derecha), marcar categorías y revisar el plano.
- Deshacer, imprimir o guardar en PDF.

## Cómo usarla

Abrí `index.html` en el navegador. No necesita instalación ni servidor.

Los datos se guardan solo en el navegador de cada persona (almacenamiento local). Se pueden borrar con el botón "Borrar datos guardados".

## Publicarla con GitHub Pages

1. Subí `index.html` y este archivo a un repositorio público.
2. En **Settings > Pages**, elegí **Deploy from a branch**, rama `main`, carpeta `/ (root)`, y guardá.
3. La página queda en `https://TU-USUARIO.github.io/NOMBRE-DEL-REPOSITORIO/`.

## Nota sobre la IA

Las funciones "Armar plano con IA" y "Ordenar por precedencia" solo funcionan cuando la página se abre dentro de Claude. Fuera de Claude, ese bloque se oculta solo y el resto de la aplicación funciona igual.
