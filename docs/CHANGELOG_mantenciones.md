# 📋 CHANGELOG: mantenciones.html

Historial de cambios del Módulo de Control de Mantenciones.

---

## [v1.0.0] - 2025-12-23

### ✨ Features

- **Registro de problemas**: Reportar fallas en equipos con descripción y ubicación
- **Prioridades**: Alta, Media, Baja con colores distintivos
- **Estados workflow**: Reportado → En Proceso → Cerrado
- **Asignación**: Técnico interno, servicio externo o por asignar
- **KPIs**: Contadores de reportados, en proceso y cerrados

### 🎨 UI/UX

- Formulario modal con selector de equipo, ubicación y prioridad
- Botones de acción (Iniciar, Cerrar) en cada card
- Modo oscuro/claro
- Indicadores visuales de prioridad y estado

### 🔧 Técnico

- Firebase Firestore (colección `mantenciones`)
- React 18 vía ES Modules
