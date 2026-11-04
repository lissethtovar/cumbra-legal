# INS-0031 — v11 de Anestesia, solo borrador

Responsable de la propuesta: Codex. Auditoría: Claude. Aceptación: Lisseth por Andamia.

Base: `ce83eeed1202e9d63c726d78bf267e6837a14057` (v10). Rama `codex/ins0031-privacidad-v11`; no fusionar ni publicar. La v10 de main continúa vigente y no se modificó Trauma.

Se añaden RevenueCat, finalidad de acceso/compra/restauración, identificador vinculado e historial, base de prestación contractual/obligaciones legales, transferencias y límite de borrado/retención. Se retira la afirmación absoluta sobre ausencia de fines propios de todos los proveedores, que ya estaba observada para Expo.

No se certifican contratos aceptados, plazos no medidos, región efectiva ni comportamiento de un binario inexistente. El HTML marca los puntos que deben completarse antes de la aceptación: contraparte y configuración de RevenueCat, retención y procedimiento de supresión. No se afirma que una eliminación de cuenta cancele la suscripción.

Fuentes primarias consultadas el 2026-11-04:

- [RevenueCat, DPA](https://www.revenuecat.com/dpa): tratamiento por instrucciones y transferencias; no acredita aceptación por Andamia.
- [RevenueCat, privacidad](https://www.revenuecat.com/privacy): categorías de transacción e identificadores y retención; confirmar configuración efectiva.
- [RevenueCat, Apple App Privacy](https://www.revenuecat.com/docs/platform-resources/apple-platform-resources/apple-app-privacy): historial de compras; con UUID de cuenta se propone vinculado.
- [Apple, suscripciones](https://developer.apple.com/app-store/subscriptions/): términos y presentación de suscripción/oferta.

Antes de publicar: revisar el diff, completar los pendientes, contrastar el tráfico y configuración del candidato, aceptar Lisseth la versión final, y coordinar por separado la publicación. Ninguno de estos pasos se presume cumplido por este commit.
