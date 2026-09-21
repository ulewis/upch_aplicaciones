# LID 301 — GitHub Pages

Frontend responsive para el sistema de control de estudiantes y asistencia del LID 301.

- Sitio: https://ulewis.github.io/upch_aplicaciones/
- Backend operativo: Google Apps Script.
- Base de datos: Google Sheets.
- La validación de roles (ADMIN, DOCENTE, ESTUDIANTE) continúa en Apps Script.
- GitHub Pages sirve como contenedor público responsive; no almacena credenciales ni datos del laboratorio.

El Web App de Apps Script debe usar `HtmlService.XFrameOptionsMode.ALLOWALL` para poder mostrarse dentro del sitio.
