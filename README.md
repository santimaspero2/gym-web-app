# GymTracker (Google Apps Script + Sheets)

Una aplicación web ligera, de código abierto y completamente gratuita para registrar tus sesiones de entrenamiento, utilizando Google Sheets como base de datos NoSQL y Google Apps Script como motor de despliegue.
## Características
    Zero-cost: Utiliza la infraestructura gratuita de Google.

    Base de Datos NoSQL: Gestión de datos sencilla mediante hojas de cálculo.

    Fácil despliegue: Configuración en menos de 5 minutos.

    Diseño Responsivo: Interfaz limpia para registrar series desde el móvil en el gym.

## Cómo instalarlo (Quick Start)
Sigue estos pasos para desplegar tu propia instancia de GymTracker.

### Preparar la Base de Datos
1. Crea una nueva Google Sheet.
2. Nombra la primera pestaña como Registros.
3. Crea los siguientes encabezados en la primera fila:
4. Fecha, Ejercicio, Series, Repeticiones, Peso (kg), Notas.
5. Copia el ID de tu hoja (es el código largo que aparece en la URL entre /d/ y /edit).

### Configurar Apps Script
1. En tu Google Sheet, ve a Extensiones > Apps Script.
2. Borra todo el contenido y pega el código de Code.gs (disponible en este repo).
3. Busca la variable SHEET_ID en el código y pega el ID que copiaste en el paso anterior.
4. Crea un nuevo archivo llamado Index.html y pega el contenido del archivo correspondiente del repo.

### Desplegar
1. Haz clic en el botón azul Implementar > Nueva implementación.
2. Selecciona Aplicación web.
3. En Configuración:
  - Descripción: GymTracker MVP
  - Ejecutar como: Yo
  - Quién tiene acceso: Cualquiera
4. Haz clic en Implementar y autoriza los permisos de Google.

    ¡Listo! Copia la URL que te proporciona Google; esa será tu app.

## Stack Tecnológico
    Frontend: HTML5, CSS3 (Tailwind CSS via CDN), JavaScript Vanilla.
    Backend: Google Apps Script (Node.js runtime).
    Storage: Google Sheets (Google Sheets API).

## Contribuciones
Este proyecto es 100% open source. Si tienes alguna mejora, siéntete libre de abrir un Pull Request o crear un Issue con tus sugerencias.

Hecho con <3 por Santi :D
