# 📋 CHANGELOG: cuentas.html

Historial de cambios del Módulo de Gestión de Cuentas.

---

## [v1.0.0] - 2025-12-23

### ✨ Features

- **Registro de facturas**: Crear cuentas por pagar con proveedor, monto, descripción y fecha de vencimiento
- **Estados**: Pendiente → Pagada
- **KPIs en tiempo real**: Total pendiente y total pagado
- **Filtros**: Ver pendientes, pagadas o todas
- **Lista de proveedores**: Preconfigurada con proveedores comunes del café

### 🎨 UI/UX

- Formulario modal para nueva cuenta
- Botón flotante (+) para agregar
- Modo oscuro/claro
- Cards con estado visual (rojo pendiente, verde pagado)

### 🔧 Técnico

- Firebase Firestore (colección `cuentas`)
- React 18 vía ES Modules
