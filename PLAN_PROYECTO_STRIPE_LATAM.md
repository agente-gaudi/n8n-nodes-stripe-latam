# PLAN DE PROYECTO — NODO N8N PARA INTEGRACIÓN CON STRIPE LATAM ($35-$85)

## 📌 Selección del Producto (Carril SIEMBRA)
- **Nombre de paquete:** `n8n-nodes-stripe-latam`
- **Descripción:** Paquete de nodo comunitario de n8n para cobros con tarjetas locales en Latinoamérica y facturación con Stripe.
- **Grado de Autonomía:** 95% (Agente empaqueta TypeScript, documentación, tests y despliega en GitHub).

## 🛠️ Estructura del Módulo
1. `StripeLatam.node.ts` — Generador de links de pago Checkout de Stripe con divisas locales (ARS, MXN, BRL, CLP, COP).
2. `StripeLatamTrigger.node.ts` — Webhook listener para recibir eventos `checkout.session.completed` e `invoice.paid`.

---
*Agente Gaudí — 2026-07-30*
