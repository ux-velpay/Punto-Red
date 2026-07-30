# Punto Red · Prototipos UI

Prototipos de interfaz clickeables para el proyecto **Punto Red** en la plataforma **Velpay**.

## Vistas

- **`index.html` — Portales (Velpay Assistant).** Dos portales web:
  - **Portal Distribuidor** — Dashboard, Comercios, Transacciones, Comisiones, Estado de Cuenta, Conciliación y Mi Perfil.
  - **Portal Proveedor de Servicios** — Comercios (con QR y ApiKey enmascarada), Transacciones y Mi Perfil.
  - Usa el selector **"Vista de portal"** para alternar entre ambos.
- **`bo.html` — BackOffice · Alta de distribuidores.** Alta de uno o más distribuidores, cada uno con sus cuentas, esquema de comisión y proveedores de servicios; y listado de distribuidores.
- **`config-liquidacion.html` — BackOffice · Config de Liquidación.** Configuración de liquidación del comercio: Split Payments y destinos de los fondos (Comercio / Proveedor de Servicios).

## Cómo verlo

Abre cualquiera de los `.html` en un navegador. No requiere build ni dependencias.

O sírvelo localmente:

```bash
python3 -m http.server 8000
# luego abre http://localhost:8000
```

## Notas

- Es un **prototipo de referencia visual**. Todos los datos (comercios, montos, RFC, CLABE, ApiKeys) son **ficticios**.
- Hecho en HTML, CSS y JavaScript sin frameworks; sigue los tokens del sistema de diseño de Velpay.
- Responsive (la barra lateral colapsa en móvil), con foco de teclado visible y respeto a `prefers-reduced-motion`.
