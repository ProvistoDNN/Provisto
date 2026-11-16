# Provisto · Prototipo v2

Prototipo interactivo de **Provisto** ("Desperdiciar menos, vender más"), una herramienta para cafeterías y panaderías que ayuda a producir la cantidad justa cada día. El prototipo usa como caso de ejemplo a **Brot Café** (sucursales Palermo y Colegiales).

> Todos los datos (productos, ventas, precios, usuarios, sucursales) son **ficticios** y están cargados en los propios archivos con fines de demostración.

## Versiones

| Archivo | Versión | Pensada para |
|---|---|---|
| `index.html` | Escritorio | Pantallas de computadora (ancho mínimo de 1180 px) |
| `tablet.html` | Tablet | Tablet en horizontal y vertical, con controles táctiles |

Para abrir la versión tablet en la página publicada, agregá `/tablet.html` al final del link del sitio.

## Qué incluye

Ambas versiones tienen las mismas pantallas:

| Pantalla | Qué muestra |
|---|---|
| Inicio | Resumen del día, ventas por hora vs. pronóstico, alertas recientes |
| Pronóstico | Producción sugerida por producto, confirmación y edición de cantidades |
| Servicio | Monitoreo en vivo, alertas y recomendaciones de acción |
| Cierre del día | Conciliación de sobrantes, descartes y faltantes |
| Rentabilidad | Panel gerencial: mermas, ventas perdidas, margen y eficiencia por producto |
| Productos | Alta, edición y baja de productos del catálogo |
| Configuración y Perfil | Datos del negocio, plan, integración con POS y notificaciones |

### Versión tablet

- En una computadora se muestra dentro de un marco de tablet, con botones para cambiar entre **Horizontal** y **Vertical** y para pasar a **Pantalla completa**.
- En una tablet real abre directamente en pantalla completa. También se puede forzar agregando `?full` al final del link.
- Las cantidades se ajustan con botones − / + en lugar de escribir, y los botones tienen un tamaño pensado para usar con el dedo.

## Cómo verlo

**Opción 1 · Local:** abrí `index.html` o `tablet.html` en el navegador (doble clic). No requiere instalación ni servidor.

**Opción 2 · GitHub Pages:**
1. En el repositorio, entrá a **Settings → Pages**.
2. En *Build and deployment*, elegí **Deploy from a branch**.
3. Seleccioná la rama `main` y la carpeta `/ (root)`, y guardá.
4. A los pocos minutos la página queda publicada en `https://<tu-usuario>.github.io/<nombre-del-repo>/`, y la versión tablet en `https://<tu-usuario>.github.io/<nombre-del-repo>/tablet.html`.

## Tecnologías

- HTML, CSS y JavaScript puro (sin dependencias de build).
- [Chart.js 4.4.1](https://www.chartjs.org/) cargado desde CDN para los gráficos.
- Tipografías [Poppins](https://fonts.google.com/specimen/Poppins) y [Gochi Hand](https://fonts.google.com/specimen/Gochi+Hand) desde Google Fonts.

Los gráficos y las tipografías necesitan conexión a internet; sin ella, la página funciona pero los gráficos no se muestran.

## Notas

- Es un prototipo: los cambios que se hacen en la interfaz viven solo en memoria y se pierden al recargar.
