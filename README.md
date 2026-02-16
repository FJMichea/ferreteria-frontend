# 🎨 ERP Ferretería Quilpuecito - Panel Web Analytics (Frontend)

Este repositorio contiene la Interfaz de Usuario (UI) Cliente del Sistema de Gestión de Ferretería. Diseñado bajo el enfoque "Mobile First" (Totalmente responsivo) y estilizado con una estética *Dark Analytics/Industrial* para un uso prolongado sin fatiga visual.

## 🌐 Entorno de Producción (Live Demo)
El Frontend está desplegado como un sitio estático de alta velocidad consumiendo la API de producción.
* **Acceso al Sistema Web:** [https://ferreteria-michea-web.onrender.com/]

### 🔐 Credenciales de Acceso (Entorno Demo)
Para experimentar el **Control de Acceso Basado en Roles (RBAC)** en la interfaz, puedes iniciar sesión con:
* **Administrador (Puede eliminar productos):** Usuario: `admin` | Contraseña: `admin123_ferreteria`
* **Vendedor (Permisos de eliminación bloqueados):** Usuario: `vendedor1` | Contraseña: `12345`

## 🚀 Tecnologías y Librerías
* **HTML5, CSS3 & JavaScript (Vanilla):** Lógica asíncrona (`fetch`) y manipulación del DOM (Single Page Application feel).
* **Bootstrap 5:** Sistema de grillas y componentes adaptables a smartphones y tablets.
* **Chart.js:** Visualización avanzada de datos (Gráficos y Medidores Gauge).
* **SweetAlert2:** Alertas profesionales de validación de stock y control de errores.
* **SheetJS (XLSX) y jsPDF:** Motor de exportación de reportes de auditoría generados en el navegador.

## 💡 Funcionalidades Actuales (Fase 1)
* **Dashboard BI en Tiempo Real:** Consumo de métricas analíticas calculadas por Pandas en el backend.
* **Control de Acceso Seguro (RBAC):** Renderizado condicional de botones destructivos según el token JWT del usuario.
* **Buscador Dinámico Instantáneo:** Filtro inteligente de SKUs en memoria, sin latencia ni recargas.
* **Paginación del Lado del Cliente:** Gestión fluida de catálogos masivos para optimizar el rendimiento del navegador.
* **Libro Mayor de Movimientos:** Trazabilidad completa con opciones de exportación (Excel/PDF) con un solo clic.

## 🛠️ Instalación (Local)
Al ser una arquitectura desacoplada, el Frontend no requiere compilación:
1. Clona este repositorio.
2. Abre el archivo `login.html` en cualquier navegador web moderno, o utiliza una extensión como *Live Server* en VS Code.

## 🔮 Roadmap y Futuras Mejoras
El diseño modular de la interfaz permite futuras integraciones:
1. **Módulo POS (Punto de Venta) para caja rápida.**
2. **Generador automático de Órdenes de Compra en PDF (Auto-PO).**
3. **Integración de `MediaDevices API` para lectura de Códigos de Barras nativa desde el celular.**

---
*Desarrollado con  usabilidad web (UX/UI) y enfocado en resolver las problemáticas reales de control de inventario local.*
**Desarrollado por:** Francisco Michea.