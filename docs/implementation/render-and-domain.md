# Render y dominio

## Servicio

- Nombre: `aduken-site`
- Tipo: Static Site
- Rama: `main`

## Build

```bash
npm ci && npm run build
```

Publish directory:

```text
dist
```

## Dominios

- `www.aduken.ar` → sitio institucional.
- `aduken.ar` → redirección a `www`.
- `app.aduken.ar` → aplicación productiva.
- `test.aduken.ar` → aplicación de pruebas.

Primero se valida el sitio con la URL temporal de Render. Después se configura Cloudflare.
