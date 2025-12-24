# 📋 CHANGELOG: eventos.html

Historial de cambios del Módulo de Cotización y Gestión de Eventos.

---

## [v1.0.0] - 2025-12-23

### ✨ Features

- **Cotizador inteligente**: Calcula automáticamente según servicios y número de personas
- **Servicios disponibles**: Barra de Café, Pizzas, Brunch, Mesa Dulce, Bebidas, Decoración, Exclusividad
- **Pipeline de ventas**: Cotizado → Confirmado → Ejecutado → Cobrado
- **Generación de cotización**: Texto formateado para copiar a WhatsApp
- **KPIs**: Cotizados, confirmados e ingresos potenciales

### 🎨 UI/UX

- Formulario completo con slider de personas
- Selector múltiple de servicios con precios
- Total en tiempo real
- Botones de acción para mover en el pipeline
- Modo oscuro/claro

### 🔧 Técnico

- Firebase Firestore (colección `eventos`)
- React 18 vía ES Modules
- Cálculo dinámico: precio por persona vs precio fijo
