# Sprint 04 — Implementar y publicar la Home de Aduken

Trabajá únicamente dentro del repositorio `aduken-site`.

## Objetivo

Dejar una primera versión completa, responsive, accesible y publicable de la Home de Aduken. En este sprint se termina la etapa de definición y se pasa a implementación. La Home debe quedar lista para desplegar en Render.

## Fuente de verdad

Leer antes de modificar código:

- `docs/product-book/00-philosophy.md`
- `docs/product-book/13-manifesto.md`
- `docs/product-book/14-founder-story.md`
- `docs/product-book/15-commercial-philosophy.md`
- `docs/product-book/16-customer-journey.md`
- `docs/product-book/17-home-wireframe.md`
- el resto de `docs/product-book/`
- `AGENTS.md`
- `README.md`

Ante una contradicción, priorizar:

1. `17-home-wireframe.md`
2. `00-philosophy.md`
3. `13-manifesto.md`
4. documentos restantes
5. implementación actual

## Decisiones cerradas

No crear más documentación estratégica antes de implementar. No pedir nuevas definiciones visuales. Resolver con criterio profesional y dejar el sitio funcionando.

### Identidad

La experiencia debe transmitir confianza, cercanía, claridad, tranquilidad, inteligencia, profesionalismo y evolución.

Evitar estética de plantilla SaaS, neón, violeta “IA”, glassmorphism excesivo, dashboards flotantes como protagonista, stock photos corporativas, mensajes grandilocuentes, venta agresiva y animaciones decorativas.

### Concepto visual

Usar como lenguaje visual:

- capas;
- flujos;
- convergencia;
- transformación;
- comprensión antes de acción.

Las visualizaciones deben explicar ideas, no decorar.

### Dirección visual

Estética editorial, limpia y moderna:

- mucho aire;
- jerarquía tipográfica clara;
- títulos sólidos;
- fondo predominantemente claro;
- azul profundo como color de confianza;
- tonos neutros cálidos;
- verde suave para resultados o validación;
- acento cálido y contenido para acciones;
- bordes, sombras y radios discretos;
- sin saturación visual.

No agregar dependencias pesadas si no son necesarias.

## Stack

Mantener el stack actual:

- Astro;
- TypeScript;
- sitio estático;
- Render.

Reutilizar la estructura existente cuando sea razonable. Crear componentes pequeños y claros.

## Home

Implementar la Home respetando la narrativa de `17-home-wireframe.md`.

### 1. Navegación

Incluir:

- logo Aduken;
- Producto;
- Cómo trabajamos;
- Inteligencia aplicada;
- Nuestra historia;
- Ingresar;
- CTA `Conversemos sobre tu negocio`.

El menú debe funcionar correctamente en escritorio y móvil. Usar enlaces internos a secciones cuando todavía no existan páginas independientes.

### 2. Hero

Eyebrow:

`Sistema de gestión adaptable`

Título:

`Un sistema que entiende cómo trabajás.`

Texto:

`Aduken combina experiencia, acompañamiento humano e inteligencia aplicada para resolver las necesidades reales de tu negocio sin obligarte a cambiar tu forma de trabajar.`

CTA principal:

`Conversemos sobre tu negocio`

CTA secundario:

`Conocé cómo trabajamos`

Microcopy:

`No empezamos con una demo. Empezamos escuchando.`

Crear una visualización original basada en capas y flujos. No usar una captura de dashboard como imagen principal.

### 3. Negocios diferentes

Título:

`No creemos que todas las empresas deban trabajar igual.`

Representar visualmente:

Fábrica:

`Venta → Producción → Preparación → Entrega`

Ferretería:

`Venta → Entrega`

Ambos recorridos deben converger en una base común representada por Aduken. La visualización debe ser comprensible sin animación.

### 4. Problema habitual

Título:

`Cuando el sistema no entiende el trabajo, el trabajo termina rodeando al sistema.`

Mostrar:

- planillas paralelas;
- información duplicada;
- tareas repetidas;
- procesos manuales;
- personas que conocen “el truco”;
- soporte desconectado del problema real.

No atacar marcas ni competidores.

### 5. Cómo trabaja Aduken

Título:

`Primero entendemos. Después construimos.`

Flujo:

1. Escuchamos.
2. Relevamos.
3. Identificamos.
4. Proponemos.
5. Implementamos.
6. Validamos.
7. Acompañamos.

La secuencia debe ser horizontal en escritorio y vertical en móvil.

### 6. Experiencia real

Título:

`Construido desde negocios reales y dominios complejos.`

Usar la versión resumida de `14-founder-story.md`.

Incluir:

`Adaptarse al cliente no alcanza. Cada adaptación también debe poder mantenerse.`

No publicar todavía:

- `70%`;
- liderazgo en Argentina;
- cifras de producción;
- nombres de clientes;
- testimonios;
- métricas no verificadas.

Se puede mencionar experiencia en software para la industria petrolera sin cifras.

### 7. Inteligencia aplicada

Título:

`La inteligencia artificial debería sacarte trabajo, no darte nuevas cosas que aprender.`

Implementar una visualización del caso:

1. Archivo Excel.
2. Análisis.
3. Detección de productos, códigos, precios e inconsistencias.
4. Alternativas comprensibles.
5. Confirmación humana.
6. Resultado procesado.

Mostrar además:

`La IA también ayuda a validar cambios, ampliar pruebas y detectar riesgos antes de que una actualización llegue al cliente.`

No presentar la IA como magia ni como sustituto de personas.

### 8. Base y capacidades

Título:

`Una base sólida para negocios que no son iguales.`

Mostrar una base estable y capas opcionales.

Ejemplos:

- orden de producción;
- información adicional en factura;
- aprobación especial;
- importación con reglas propias;
- circuito de entrega particular.

Mensaje:

`Adaptado a tu operación. Preparado para seguir evolucionando.`

### 9. Capacidades del producto

Título:

`La gestión que necesitás, sobre una base que puede crecer.`

Mostrar grupos:

- operación comercial;
- productos y stock;
- administración;
- tesorería;
- organización.

No afirmar que una función está disponible si el repositorio no contiene una fuente de verdad que lo confirme. Si no existe un estado confiable de funcionalidades, usar lenguaje de visión general y evitar etiquetas como “disponible”.

### 10. Propuesta comercial

Título:

`No queremos que elijas Aduken por una presentación.`

Texto:

`Queremos entender tu operación, ayudarte a utilizarlo en situaciones reales y que puedas evaluar si verdaderamente mejora tu trabajo. Cuando estés convencido de que aporta valor, hablamos del acuerdo comercial.`

CTA:

`Conversemos sobre tu negocio`

Microcopy:

`Sin presión comercial. Sin una demo genérica. Empezamos por tu problema.`

No prometer uso gratuito ilimitado.

### 11. Contacto

Título:

`¿Qué parte de tu trabajo debería ser más simple?`

Campos:

- problema o proceso;
- nombre;
- empresa;
- actividad;
- correo;
- WhatsApp opcional;
- cantidad aproximada de usuarios;
- herramientas actuales, opcional.

Botón:

`Enviar y conversar`

Mensaje:

`Gracias. Vamos a leer lo que nos contaste antes de responderte.`

## Funcionamiento del formulario

Como el sitio es estático:

1. Revisar si ya existe una integración de formulario.
2. Si existe, reutilizarla.
3. Si no existe:
   - implementar validación cliente;
   - construir un correo mediante `mailto:` con asunto y cuerpo completos;
   - tomar el destinatario de `PUBLIC_CONTACT_EMAIL`;
   - documentar la variable en `.env.example`;
   - si la variable no está definida, ocultar el envío y mostrar un mensaje de configuración sólo en desarrollo.

No incorporar servicios externos pagos ni dependencias de terceros sin necesidad.

## Footer

Incluir:

- Producto;
- Cómo trabajamos;
- Inteligencia aplicada;
- Nuestra historia;
- Contacto;
- Ingresar;
- Privacidad;
- Términos.

Cierre:

`Aduken — Power of Simplicity.`

## Animaciones

Sólo animaciones sutiles que expliquen convergencia, progresión, aparición de capas, análisis del Excel y recorrido del proceso.

Requisitos:

- respetar `prefers-reduced-motion`;
- no bloquear la lectura;
- no depender de la animación para comprender;
- no agregar librerías pesadas salvo necesidad real.

## Accesibilidad

Garantizar:

- HTML semántico;
- un solo `h1`;
- jerarquía correcta;
- navegación por teclado;
- focos visibles;
- contraste suficiente;
- labels reales;
- mensajes de error asociados;
- menú móvil accesible;
- enlaces y botones correctamente diferenciados;
- soporte para reducción de movimiento.

## SEO

Implementar o revisar:

- título;
- descripción;
- canonical configurable;
- Open Graph;
- Twitter Card;
- favicon;
- `lang="es"`;
- metadatos consistentes;
- JSON-LD básico de `Organization` sólo con datos confirmados;
- no inventar dirección, teléfono ni redes sociales.

Título sugerido:

`Aduken — Un sistema que entiende cómo trabajás`

Descripción sugerida:

`Sistema de gestión adaptable con acompañamiento humano e inteligencia aplicada para resolver las necesidades reales de cada negocio.`

## Rendimiento

Objetivos:

- evitar JavaScript innecesario;
- usar CSS y Astro siempre que alcance;
- optimizar SVG;
- no cargar imágenes pesadas;
- evitar layout shifts;
- mantener buen rendimiento móvil.

## Responsive

Validar al menos:

- 360 px;
- 390 px;
- 768 px;
- 1024 px;
- 1440 px.

La narrativa debe conservarse en móvil.

## Calidad

Crear o actualizar pruebas según el stack existente.

Como mínimo:

- render de la Home;
- presencia del H1;
- navegación principal;
- CTA principal;
- formulario;
- validaciones;
- menú móvil si hay infraestructura de tests compatible.

Si Playwright ya está instalado, agregar un smoke test de la Home. No incorporar Playwright únicamente para este sprint si introduce una reestructuración desproporcionada.

## Render

Revisar la configuración existente.

Asegurar que:

- el comando de build sea correcto;
- la carpeta de salida sea correcta;
- el sitio funcione como estático;
- no haya rutas rotas;
- `.env.example` incluya variables nuevas;
- README indique cómo desplegar en Render.

No crear recursos externos ni cambiar cuentas.

Si el repositorio ya está conectado a Render, realizar commit y push únicamente si el entorno tiene permisos y la política del proyecto lo permite.

Si no puede hacer push o desplegar, dejar exactamente:

- comandos;
- variables;
- configuración;
- pasos mínimos para publicar.

## Validaciones finales

Ejecutar las disponibles en el proyecto:

- instalación limpia;
- format;
- lint;
- typecheck;
- tests;
- build;
- check.

Corregir errores.

## Criterios de aceptación

- La Home está implementada.
- Funciona en escritorio y móvil.
- La narrativa aparece antes que la lista de funciones.
- No usa `Solicitar demo` como CTA principal.
- Explica diferencias entre negocios.
- Explica IA mediante un caso concreto.
- Muestra la filosofía de adaptación mantenible.
- No inventa testimonios, métricas ni funciones.
- El formulario tiene una salida funcional o una configuración explícita.
- La build de producción termina correctamente.
- El repositorio queda listo para Render.

## Entrega

Responder con:

1. resumen;
2. archivos creados;
3. archivos modificados;
4. decisiones visuales tomadas;
5. pruebas ejecutadas;
6. resultado del build;
7. estado del despliegue;
8. URL pública, si fue posible desplegar;
9. único bloqueo restante, si existiera.

No imprimir archivos completos.
