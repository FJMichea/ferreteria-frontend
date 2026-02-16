# 🎨 ERP Ferretería - Panel Web Analytics (Frontend)

Este repositorio contiene la Interfaz de Usuario (UI) Cliente del Sistema de Gestión de Ferretería. Diseñado bajo el enfoque "Mobile First" y estilizado con estética *Dark Analytics* para un uso industrial prolongado sin fatiga visual.

## 🚀 Tecnologías y Librerías
* **HTML5, CSS3 & JavaScript (Vanilla):** Lógica asíncrona (`fetch`) y manipulación del DOM sin recargas (Single Page Application feel).
* **Bootstrap 5:** Sistema de grillas y componentes responsivos.
* **Chart.js:** Visualización avanzada de datos (Gráficos de Barra y Medidor Gauge).
* **SweetAlert2:** Alertas de validación y control estricto de errores.
* **SheetJS (XLSX) y jsPDF:** Motor de exportación de reportes de auditoría generados del lado del cliente.

## 💡 Funcionalidades Actuales (Fase 1)
* **Dashboard BI en Tiempo Real:** Consumo de métricas API (Capital inmovilizado, Rotación, Top Ventas).
* **Control de Acceso (RBAC):** Renderizado condicional de botones destructivos (eliminar) bloqueados para vendedores y habilitados para Administradores.
* **Buscador Dinámico Instantáneo:** Filtro inteligente en memoria sin consultas constantes al servidor.
* **Paginación del Lado del Cliente:** Gestión de catálogos masivos asegurando un rendimiento fluido.
* **Libro Mayor de Movimientos:** Trazabilidad completa con opciones de exportación (Excel/PDF) para contabilidad.

## 🔮 Roadmap y Futuras Mejoras (Fase 2 y 3)
El diseño modular de esta interfaz permite la futura integración de:
1. **Módulo POS (Punto de Venta):** Interfaz dedicada para cajeros que permita escanear productos y generar ventas rápidas de mostrador, conectadas directamente al inventario.
2. **Abastecimiento Inteligente (Auto-PO):** Módulo de Proveedores que, al detectar stock crítico, genere un borrador de Orden de Compra (PDF) automático listo para enviar.
3. **Lector de Códigos de Barras Web:** Integración de la API `MediaDevices` para usar la cámara del dispositivo móvil o tablet como escáner directo en la interfaz web.

---
*Este proyecto consume la API REST construida en Django . 
Desplegado como sitio estático de alta disponibilidad.*

Realizado por : Francisco Michea.