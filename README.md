# Leadflow — Gestor de Leads

Webapp mobile-first para gestionar leads con embudo visual, alarmas y WhatsApp 1-click.

## Características

- **Embudo visual**: Nueva · Sin contacto → Contactado → Cotizado → Ganado / Perdido, con conteo por estado
- **Alarmas**: avisa los leads sin contactar hace más de 3 días
- **5 contactos por lead**: barra de progreso hasta cerrarlo (ganado/perdido)
- **Detalle de cada lead**: info, observaciones, historial de contactos y cambios
- **WhatsApp 1-click** por lead (registra el contacto automáticamente)
- **Respuestas rápidas** (CRUD en configuración) → envío directo por WhatsApp
- **Reportes copiables**: general y por lead
- **Estadísticas**: totales, conversión, distribución por estado
- **localStorage** (MVP, sin backend) — los datos quedan en el dispositivo
- 100% responsive, mobile-first, sin elementos que se salgan de pantalla

## Stack

Sitio estático: HTML + CSS + JS vanilla, sin dependencias ni build.

## Desarrollo

```bash
python3 -m http.server 8000
# abrir http://localhost:8000
```

## Deploy

Desplegado en Vercel como sitio estático.
