# Changelog - Inventario

## [v1.0.0] - 2025-12-23

### ✨ Features

- **Gestión de items por categoría**: Barra ☕, Cocina 🍳, Aseo 🧹, Empaque 📦
- **Stock triple**: Seguimiento por Coete 1, Coete 2 y Bodega externa
- **Stock mínimo configurable**: Umbral personalizable por item
- **Alertas predictivas**: Sistema de semáforo (SIN STOCK 🔴, CRÍTICO ⚠️, Reponer 🟡, OK 🟢)
- **Controles de stock**: Botones +/- para ajustar cantidades rápidamente
- **Mover desde bodega**: Botón para transferir stock de bodega a local

### 🎨 UI/UX

- Selector de local en header (Coete 1 / Coete 2)
- Botón de alertas animado con contador
- Panel de alertas desplegable
- Filtros por categoría
- Items sugeridos al crear nuevo item
- Dark mode

### 🔧 Técnico

- Firebase Firestore: Colección `inventario`
- React 18 + TailwindCSS (CDN)
