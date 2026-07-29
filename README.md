# Aduken Site

Sitio institucional y comercial de Aduken.

## Dominios

- Sitio público: `https://www.aduken.ar`
- Dominio raíz: `https://aduken.ar` → redirección a `www`
- Aplicación productiva: `https://app.aduken.ar`
- Aplicación de pruebas: `https://test.aduken.ar`
- API productiva: `https://api.aduken.ar`
- API de pruebas: `https://api-test.aduken.ar`

## Tecnología

- Astro
- TypeScript
- CSS
- Render Static Site
- GitHub

## Product Book

La carpeta [docs/product-book](docs/product-book) es la fuente principal de posicionamiento, mensaje, audiencia y narrativa del sitio institucional.

- Guiar la implementación desde los documentos de esa carpeta.
- No inventar mensajes ni funcionalidades fuera de la especificación.
- Traducir las decisiones técnicas a beneficios claros para el usuario.

## Despliegue en Render

1. Crear un servicio de Render Static Site para este repositorio.
2. Usar el comando de build: `npm run build`.
3. Usar la carpeta de salida: `dist`.
4. Definir la variable de entorno `PUBLIC_CONTACT_EMAIL` con la dirección de contacto deseada para el formulario.
   - Alternativa: definir `PUBLIC_CONTACT_ENDPOINT` con un endpoint que reciba POST JSON para enviar mensajes desde el formulario (p. ej. Formspree, Getform o una función serverless propia).
   - Opcional: definir `PUBLIC_WHATSAPP_NUMBER` con el teléfono internacional (sin signos ni espacios, p. ej. 5491122334455) para mostrar un botón de "Chatear por WhatsApp".
5. Publicar desde la rama principal.

## Próximos pasos

1. Aprobar identidad visual.
2. Incorporar el logo definitivo.
3. Crear la base Astro.
4. Implementar la Home.
5. Publicar primero con la URL temporal de Render.
6. Configurar `www.aduken.ar`.
