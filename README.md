# MenuFlow — Frontend Expo

Prototipo frontend de MenuFlow para una exposición. Es una página estática, responsive y sin dependencias externas.

## Qué demuestra

- UX/UI para cliente QR y panel de restaurante.
- Flujo de pedido en tiempo real simulado.
- Seguridad por diseño: RBAC, tenant isolation, validación y auditoría como principios.
- Responsive móvil/desktop.
- Accesibilidad básica: HTML semántico, foco natural, botones claros y `aria-live` para feedback.
- Rendimiento: un solo `index.html`, sin frameworks ni llamadas externas.
- Escalabilidad conceptual: preparada para conectarse a Next.js + API Node/Express + MongoDB + Socket.IO.

## Ejecutar

Abre `index.html` directamente en el navegador.

## Publicar en GitHub Pages

1. Crea un repositorio, por ejemplo `menuflow-expo`.
2. Sube `index.html` y `README.md`.
3. Ve a **Settings → Pages**.
4. En **Build and deployment**, selecciona `Deploy from a branch`.
5. Selecciona `main` y `/ (root)`.
6. Guarda y espera a que GitHub Pages publique el sitio.

## Importante

Los datos y el login son demostrativos. No se procesan pagos ni credenciales reales.
