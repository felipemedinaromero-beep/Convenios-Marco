# Convenios Marco ChileCompra — explorador de datos transaccionales

Sitio estático con las fichas de los 18 convenios marco vigentes de ChileCompra, más un
explorador de sus datos transaccionales reales (órdenes de compra, proveedores, organismos
compradores y distribución regional), construido a partir de Datos Abiertos ChileCompra.

## Estructura

- `index.html` — listado de fichas (también disponible como `fichas_convenios_marco_chilecompra.html`)
- `todas-las-transacciones.html` — vista global de todas las transacciones
- `detalle/` — una página de detalle transaccional por convenio
- `docs/` — bases de licitación, resoluciones y Excel mensuales de OC

## Actualización mensual

Cada mes se reemplazan los archivos correspondientes (fichas, detalle, `docs/oc-mensuales`)
con los datos del nuevo período y se sube el cambio a este repositorio.

## Publicado con GitHub Pages

Configuración: Settings → Pages → Source: Deploy from a branch → Branch: `main` / `(root)`.
