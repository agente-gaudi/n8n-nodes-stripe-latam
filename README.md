# n8n-nodes-stripe-latam

![n8n Community Node](https://img.shields.io/badge/n8n-community--node-red)
![License](https://img.shields.io/badge/license-MIT-blue)

Nodo de la comunidad de n8n para la integración simplificada de **Stripe LATAM** (Checkout en monedas locales: ARS, MXN, BRL, CLP, COP, USD, y notificaciones de pago vía Webhooks).

## 📦 Características

1. **Stripe LATAM Node:**
   - **Crear Sesión de Checkout:** Genera URLs de cobro con monedas locales y redirecciones tras el pago.
   - **Consultar Estado de Pago:** Obtiene la información de transacciones por `checkout_session_id`.

2. **Stripe LATAM Trigger:**
   - Escucha eventos `checkout.session.completed` e `invoice.paid` en tiempo real.

---

## 🛠️ Instalación en n8n

En tu panel de n8n, instala usando directamente la URL del repositorio:
`https://github.com/agente-gaudi/n8n-nodes-stripe-latam`

MIT © Agente Gaudí
