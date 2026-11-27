# KitchenOps Hub

Aplicación web pensada para uso móvil en turno de cocina. Permite llevar el control diario de protocolos de higiene (BPM), temperaturas de equipos de frío, rotación de inventario (FIFO) y trazabilidad de salida de platos sin depender de planillas en papel.

* **Demo en vivo:** https://bastianalarcon1a.github.io/KitchenOps-Hub/
* **PIN de prueba:** `1234`

## Origen del proyecto

Trabajando en operación y jefatura de cocina noté que el registro manual de temperaturas, checklists de apertura/cierre y conteo de comandas en papel suele generar pérdida de datos, errores de traspaso al final del día y falta de visibilidad rápida para tomar decisiones de compra o producción.

Desarrollé este sistema como una herramienta ligera que cualquier integrante del equipo pueda operar desde su teléfono en plena jornada, guardando los datos localmente y permitiendo exportar un resumen limpio al cierre de turno.

## Avance y hoja de ruta

- [x] **v1.0 - Protocolo operativo y checklist:** Tareas separadas por estación (Cuarto Frío, Caliente, Bodega, Sanitización y Despacho), barra de avance del turno y generación de resumen de cierre.
- [x] **v1.1 - Mapa de planta y control de cámaras:** Esquema interactivo de áreas de producción y almacenamiento con límites críticos de temperatura por equipo.
- [x] **v1.2 - Contador de trazabilidad y exportación CSV:** Registro rápido de salidas por preparación, sincronización con planillas físicas y descarga en formato CSV para análisis en Excel.
- [x] **v1.3 - Fichas técnicas y gramajes:** Consulta rápida de recetas estandarizadas, rendimientos y alérgenos.

## Tecnologías utilizadas

* HTML5 y CSS3
* Bootstrap 5.3.2
* JavaScript (ES6+) con persistencia en `localStorage` y `sessionStorage`
* GitHub Pages para despliegue

## Autor

**Bastián Alarcón Acevedo**  
Administrador Gastronómico Internacional | Estudiante de Técnico Analista de Datos  
GitHub: https://github.com/bastianalarcon1A
