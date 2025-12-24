# 📋 CHANGELOG: dashboard.html

Historial de cambios del Panel de Control.

---

## [v2.1.0] - 2025-12-23

### ✨ Features

- **Soporte Multi-Local**: Selector Coete 1 / Coete 2 en header
- Filtrado automático de cierres, cuentas y mantenciones por local
- Re-fetch de datos al cambiar de local
- Eventos NO filtrados (negocio independiente)

---

## [v2.0.0] - 2025-12-23

### ✨ Features

- **Panel Acceso Rápido**: Links a Cuentas, Mantenciones, Eventos y Cierre
- **Integración de módulos**: Muestra alertas de cuentas pendientes, mantenciones y eventos
- Fetch de todas las colecciones Firebase (cierres, cuentas, mantenciones, eventos)

### 🎨 UI/UX

- Cards interactivas con estados dinámicos
- Colores de alerta según pendientes en cada módulo

---

## [v1.1.0] - 2025-12-23

### ✨ Features

- **Panel de Quiebres de Stock**: Nueva sección que muestra items faltantes de los últimos 7 cierres
- **Ranking por frecuencia**: Items ordenados por cuántas veces faltan
- **Alertas visuales**: Items que faltan ≥3 veces se destacan en rojo con animación

### 🔧 Técnico

- Nuevo estado `stockFaltantes` para tracking de quiebres
- Procesamiento de array `stockFaltante` desde Firebase
- Contador de frecuencia por item

---

## [v1.0.0] - 2024-12-XX

### ✨ Features

- Conexión a Firebase Firestore
- Consulta de últimos 7 cierres
- KPIs: Venta Acumulada, Diferencias de Caja, Ticket Promedio (estimado)
- Gráfico de barras de evolución de ventas

### 🎨 UI/UX

- Diseño responsivo mobile-first
- Modo oscuro/claro
- Indicador de carga "Sincronizando..."

### 🔧 Técnico

- React 18 vía ES Modules
- TailwindCSS vía CDN
