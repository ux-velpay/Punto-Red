# Punto Red · Portales (Prototipo UI)

Prototipo de interfaz, clickeable, de dos portales web para la plataforma **Velpay Assistant**:

- **Portal Distribuidor** — Dashboard, Comercios, Transacciones, Comisiones, Estado de Cuenta, Conciliación y Mi Perfil.
- **Portal Proveedor de Servicios** — Comercios (con QR y ApiKey enmascarada), Transacciones y Mi Perfil.

Usa el selector **"Vista de portal"** en la barra lateral para alternar entre ambos.

## Cómo verlo

Abre `index.html` en cualquier navegador. No requiere build ni dependencias.

O sírvelo localmente:

```bash
python3 -m http.server 8000
# luego abre http://localhost:8000
```

## Notas

- Es un **prototipo de referencia visual**. Todos los datos (comercios, montos, RFC, CLABE, ApiKeys) son **ficticios**.
- Hecho en HTML, CSS y JavaScript sin frameworks; sigue los tokens del sistema de diseño de Velpay.
- Responsive (la barra lateral colapsa en móvil), con foco de teclado visible y respeto a `prefers-reduced-motion`.
