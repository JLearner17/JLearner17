# Taller: Hoja de vida ATS y portafolio con dominio propio

**SENA ADSO — Piedecuesta (jornada noche)**

Taller práctico para que cada aprendiz salga con **tres entregables reales**:

1. 📄 Una **hoja de vida ATS-friendly** (PDF) que los sistemas de selección puedan leer.
2. 🌐 Un **portafolio web** publicado y en línea.
3. 🔗 Un **dominio propio** (`tunombre.dev`, `tunombre.com`…) apuntando a ese portafolio, con el menor costo posible (gratis si se puede).

> Costo objetivo: **$0** con subdominio gratuito, o **~COP 5.000–50.000 al año** con dominio propio.

---

## 🗺️ Ruta del taller

| Módulo | Carpeta | Tiempo sugerido | Resultado |
|--------|---------|-----------------|-----------|
| 0. Preparación | [Requisitos](#-requisitos-antes-de-la-clase) | — | Cuentas y herramientas listas |
| 1. Hoja de vida ATS | [`01-hoja-de-vida-ats/`](01-hoja-de-vida-ats/) | 1 h 30 | `CV-Nombre-Apellido.pdf` |
| 2. Portafolio | [`02-portafolio/`](02-portafolio/) | 1 h 30 | Sitio web local funcionando |
| 3. Despliegue y dominio | [`03-despliegue-dominio/`](03-despliegue-dominio/) | 1 h | Sitio en línea + dominio |
| 4. Perfil de GitHub | [`04-perfil-github/`](04-perfil-github/) | 45 min | README de perfil publicado |

El detalle minuto a minuto para el instructor está en [`plan-de-clase.md`](plan-de-clase.md).

## 🧰 Requisitos antes de la clase

- Cuenta de **GitHub** ([github.com/signup](https://github.com/signup)) con correo que revises.
- **Git** y **VS Code** instalados.
- Un correo **profesional** (nombre.apellido@gmail.com — sin apodos).
- Foto de perfil sencilla y bien iluminada (opcional, para el portafolio; **no** va en la hoja de vida ATS).
- Tu información básica: estudios, experiencia (aunque sea de proyectos), habilidades.
- Tarjeta/medio de pago **solo** si decides comprar un dominio (no es obligatorio).

## 📁 Contenido del repositorio

```
curso-cv-portafolio/
├── README.md
├── plan-de-clase.md                 ← guion para el instructor
├── recursos.md                      ← enlaces útiles
├── 01-hoja-de-vida-ats/
│   ├── guia.md                      ← cómo funciona un ATS y cómo escribir para él
│   ├── cv-plantilla.html            ← CV completo: editas en el navegador y "Guardar como PDF"
│   ├── cv-plantilla.docx            ← el mismo CV en Word (una columna, ATS-friendly)
│   ├── plantilla-cv.md              ← versión en texto para ir preparando el contenido
│   ├── herramientas/generar_docx.py ← (instructor) regenera el .docx
│   ├── checklist-ats.md             ← lista de verificación final
│   ├── verbos-y-logros.md           ← verbos de acción y fórmula de logros
│   └── verificador-ats.html         ← herramienta: compara tu CV con una oferta (en tu navegador)
├── 02-portafolio/
│   ├── guia.md                      ← qué debe tener un portafolio y qué proyectos mostrar
│   └── plantillas/                  ← 4 plantillas (GSAP · HUD+Blossom · Nebula+Swiper · Holo+Bootstrap): solo reemplazas datos
├── 03-despliegue-dominio/
    ├── guia-despliegue.md           ← GitHub Pages paso a paso (+ alternativas)
    └── guia-dominio.md              ← dominios gratis y baratos + configuración DNS
└── 04-perfil-github/
    ├── README.md                    ← plantilla del README de perfil (repo TU-USUARIO/TU-USUARIO)
    ├── GUIA.md                      ← paso a paso: crear el repo, subir imágenes y archivos, badges
    ├── ejemplo-comentado.md         ← la plantilla explicada línea por línea
    └── assets/                      ← banner, foto y captura de ejemplo (SVG)
```

## 🧭 Filosofía

- **Honestidad ante todo**: nada de inventar experiencia ni esconder palabras clave en texto invisible. Los reclutadores y los sistemas lo detectan, y te cuesta la oportunidad.
- **Simple gana**: un CV de una página con buena información vence a uno “bonito” que el ATS no puede leer.
- **Gratis primero**: todo el flujo funciona con herramientas gratuitas; el dominio propio es opcional.
- **Que quede en tu GitHub**: tu portafolio también es una muestra de cómo trabajas con Git.

## 📜 Licencia

Material educativo de uso libre para aprendices e instructores. Adáptalo a tu ficha.
