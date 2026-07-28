# Prompt 01 para Codex — Bootstrap

Trabajá únicamente dentro del repositorio actual `aduken-site`.

Leé primero:

- `AGENTS.md`
- `README.md`
- `docs/brand/brand-foundation.md`
- `docs/brand/visual-direction.md`
- `docs/brand/color-and-type.md`
- `docs/product/site-map.md`
- `docs/product/home-content.md`
- `docs/implementation/roadmap.md`

Objetivo:

Crear la base técnica del sitio institucional Aduken usando Astro y TypeScript.

Alcance:

1. Inicializar Astro sin borrar la documentación.
2. Usar TypeScript estricto.
3. Configurar Prettier.
4. Crear:
   - `src/layouts/BaseLayout.astro`
   - `src/components/Header.astro`
   - `src/components/Footer.astro`
   - `src/pages/index.astro`
   - `src/styles/global.css`
   - `src/styles/tokens.css`
5. Convertir la paleta documentada en variables CSS.
6. Crear una Home mínima con:
   - Aduken;
   - `Power of Simplicity`;
   - título;
   - bajada;
   - botón `Solicitar una demo`;
   - botón `Ingresar` hacia `https://app.aduken.ar`.
7. No usar React.
8. No agregar librerías de UI.
9. No inventar logo: usar el texto `Aduken`.
10. Mantener diseño responsive y accesible.

Validar:

- `npm run build`
- `npm run check`, si está disponible.
- `npm run format:check`, si se configura.

Salida:

- Resumen breve.
- Archivos modificados.
- Resultado de validaciones.
- No imprimir archivos completos.
