---
title: Phoenix Quick Landing
sdk: static
description: Landing page ultra‑rápida para carta digital, reservas y pedidos vía WhatsApp.
---
# Phoenix Quick Landing

Esta es una página estática optimizada para móviles (<1 s de carga) que incluye:

- **Hero** con gradiente y CTA llamativo.
- **Generador de QR** para la carta digital.
- **Tarjetas de menú** con botón “Añadir a WhatsApp”.
- **Botones de reserva y pedido** que abren WhatsApp con mensajes predefinidos.
- **Carrusel de videos verticales** (plato estrella, cocina en vivo, ambiente).
- **Actualización del video del plato estrella** mediante JSON remoto.
- **Compatibilidad PWA** (manifest y Service Worker).
- **Botón flotante de WhatsApp** siempre visible.
- **Navbar** con blur y menú hamburguesa responsive.
- **Footer** completo con enlaces y redes sociales.

## Instalación

1. Copia `index.html`, `manifest.json` y `service-worker.js` en la raíz de tu hosting estático (Netlify, Vercel, GitHub Pages, etc.).
2. Accede a la URL y, si lo deseas, añade la página a la pantalla de inicio (PWA).

## Personalización

- Cambia la constante `weeklyJson` en el script por la URL real de tu JSON semanal.
- Sustituye `whatsappNumber` por tu número de WhatsApp con prefijo de país.
- Modifica los textos y precios de los platos en la sección `.menu-grid`.
- Ajusta los colores en `:root` si deseas otra paleta.

## Licencia

MIT © 2024 Phoenix.