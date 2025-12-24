# 📋 CHANGELOG: cierre.html

Historial de cambios del Sistema de Cierre de Turno.

---

## [v2.4.0] - 2025-12-23

### ✨ Features

- **Soporte Multi-Local**: Selector Coete 1 / Coete 2 en header
- Datos guardados con campo `local` en Firebase
- Reporte WhatsApp incluye etiqueta del local

---

## [v2.3.0] - 2025-12-23

### ✨ Features

- **Campo Equipo con Falla**: Selector de equipos para reportar problemas directamente desde el cierre
- Equipos disponibles: Máquina Espresso, Molino, Horno, Refrigerador, etc.
- Se guarda en Firebase y aparece en el reporte de WhatsApp ("🔧 EQUIPO CON FALLA")

---

## [v2.2.0] - 2025-12-23

### ✨ Features

- **Panel de quiebres mejorado**: Fondo destacado cuando hay items seleccionados
- **Contador animado**: Badge con número de faltantes que pulsa
- **Resumen visual**: Lista de items faltantes antes de revisar cierre
- **Botón dinámico**: Cambia a rojo con conteo de quiebres cuando hay faltantes

### 🎨 UI/UX

- Iconos por categoría: ☕ Barra, 🍳 Cocina, 🧹 Aseo
- Botones con efecto hover y escala al seleccionar
- Bordes destacados en rojo cuando hay quiebres

---

## [v2.1.0] - 2024-12-01

### ✨ Features

- Separación de pagos con tarjeta en Débito y Crédito
- Panel de Reporte de Quiebres por categoría (Barra, Cocina, Aseo)
- Toggle buttons para seleccionar insumos faltantes
- Integración del array `stockFaltante` en Firebase

### 🎨 UI/UX

- Modo oscuro/claro con toggle
- Vista previa estilo WhatsApp antes de enviar
- Animaciones fade-in en transiciones

---

## [v2.0.0] - 2024-11-XX

### ✨ Features

- Integración completa con Firebase Firestore
- Guardado automático en la nube al procesar
- Generación de texto formateado para WhatsApp
- Copia automática al portapapeles

### 🔧 Técnico

- Migración de Babel a ES Modules
- React 18 vía CDN

---

## [v1.0.0] - 2024-XX-XX

### ✨ Features

- Formulario básico de cierre
- Campos: Efectivo, Tarjetas, Propinas, Novedades
- Solo copia a WhatsApp (sin persistencia)
