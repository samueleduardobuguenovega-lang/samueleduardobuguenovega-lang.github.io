# Portafolio de Samuel Bugueño Vega — página de presentación

**Objetivo:** una página pública que en 30 segundos le diga a un reclutador quién es,
qué stack maneja y qué construyó. Egreso/práctica como caso de uso principal.
**Superficie:** Decide/Learn (convencer), no Monitor ni Compare. Una idea por sección,
hero solo en la apertura.
**Dueño del pedido:** Nek (Samuel Bugueño Vega).

## Hechos verificados (fuente)

- Nombre: Samuel Bugueño Vega. GitHub: `samueleduardobuguenovega-lang`.
- Sitios en vivo verificados HTTP 200 el 2026-11-20:
  - https://brujula-coquimbo.web.app (Brújula / DecideTuCarrera)
  - https://decidetucarrera.web.app (mismo producto, dominio alterno)
  - https://nenekos-c1e77.web.app (Los Ñeñecos, cliente real en Ovalle)
- Repos públicos: `creando-sabores`, `SistemaBodegaAppAndroid`, `FinControl`,
  `SimpleGPSMapApp`, `SimpleMultimediaApp`, `Semana06Actividad21`,
  `Semana7Actividad22ThreadsYSensores`, repo de perfil.
- Repos privados con producto público: `brujula`, `los-nenecos`, `ga-streetwear`, `iron-tide`.
- Capturas reales disponibles: `assets/` (Brújula móvil, Ñeñecos escritorio y móvil,
  GA Streetwear escritorio, render de Iron Tide).
- Stack verificado por repos: SvelteKit 5, TypeScript, Tailwind 4, Firebase,
  Playwright, Vitest, Java/Android (SQLite, Gradle), Godot 4.7.2 + GDScript, Python.

## Datos pendientes de Nek (no inventar)

- Correo de contacto y LinkedIn.
- Institución y nombre exacto de la carrera en curso (los repos dicen "Analista Programador").
- Ciudad y disponibilidad (práctica / part-time / full-time) y desde cuándo.
- Foto de perfil: opcional; sin foto la página se sostiene igual.

## Tareas

### T1 — Inventario de contenido y evidencias
- S1 Copiar capturas reales a `assets/` y generar versiones optimizadas (webp/jpg).
- S2 Verificar en vivo cada URL publicada antes de enlazarla.
- S3 Redactar la ficha de cada caso: problema, qué hice, stack, resultado, link.

### T2 — Sistema de diseño
- S1 Paleta: negro cálido, papel, un solo acento (cobre). Sin gradientes.
- S2 Tipografía: Instrument Serif (display), Instrument Sans (texto), JetBrains Mono (metadatos), self-hosted.
- S3 Escala tipográfica fluida con `clamp()`; cuerpo mínimo 17 px en móvil.

### T3 — Estructura y hero
- S1 Rail fijo con nombre, rol, estado y contacto en escritorio; cabecera compacta en móvil.
- S2 Titular de dos líneas que dice qué construye, no adjetivos.
- S3 CTA: ver trabajo, descargar CV (cuando exista), correo.

### T4 — Sección de trabajo
- S1 Cinco casos con índice, captura real, rol, stack y enlace en vivo.
- S2 Layout alternado (no grilla de tarjetas iguales).
- S3 Estados de hover/focus reales; nada de decoración sin jerarquía.

### T5 — Stack y método
- S1 Stack agrupado por profundidad real (diario / desplegado / aprendiendo).
- S2 Método: pruebas antes del arreglo, medición, documentación, verificación.
- S3 Cada afirmación del método con un ejemplo concreto del trabajo real.

### T6 — Formación y contacto
- S1 Formación con institución, carrera y periodo (pendiente de dato).
- S2 Contacto: correo, GitHub, ciudad, disponibilidad.
- S3 Pie con nota de cómo está construida la página.

### T7 — Responsive y QA
- S1 Revisar 390×844, 768 y 1440; sin overflow horizontal ni texto cortado.
- S2 `prefers-reduced-motion` respetado; foco visible en todos los enlaces.
- S3 Capturas de la página renderizada como evidencia.

### T8 — Publicación
- S1 Elegir host según credenciales disponibles.
- S2 Desplegar y verificar la URL pública con HTTP 200.
- S3 Dejar el comando de re-despliegue escrito en el README.

## Log

- **2026-11-20** — T1–T8 primera pasada hecha: página construida, verificada a 390×844 y 1440×900
  (sin overflow, fuentes e imágenes cargando), publicada en GitHub Pages.
  URL: https://samueleduardobuguenovega-lang.github.io/ (HTTP 200).
  Repo: `samueleduardobuguenovega-lang.github.io` (público, solo el sitio). Commit `30360f4`, luego `7cc3726`.
  Pendiente: correo y LinkedIn en el CTA, institución de la carrera, CV en PDF si lo quiere.
