# CristianEntrenador

App de entrenamiento para los clientes de Cristian en VivaGym.
El cliente entra con su código de 6 números, ve su rutina, registra series (kg, reps y esfuerzo/RPE)
y al terminar comparte su informe como imagen o PDF.

- Cada ejercicio tiene **opción A** y, si existe, **opción B** por si la máquina está ocupada (mismo patrón de movimiento, sin saltarse el orden).
- Los registros se guardan solo en el móvil del cliente. No se pide ningún dato personal.
- Se puede instalar en la pantalla de inicio (Safari: Compartir → «Añadir a pantalla de inicio»).

## Archivos

- `index.html` — la app (las rutinas están en `CLIENTS`, al principio del script).
- `manifest.webmanifest`, `sw.js`, `icons/` — para instalarla como app y abrirla sin conexión.
- `vendor/` — librerías para crear la imagen (html2canvas) y el PDF (jsPDF).
