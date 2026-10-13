# Raúl Cancela Martín

**AI-Augmented Engineer & Cloud Automation Architect**

Orquestación de IA (Gemini, Claude, DeepSeek) · Arquitecturas Cloud & Entornos Híbridos · Automatización Enterprise con GAM y Python

📍 Madrid, España (Remoto — abierto a viajes puntuales) · 📧 arulcancela@gmail.com · 📱 +34 625 731 263
🔗 linkedin.com/in/arulcancela · 💻 github.com/arulcancela · 🌐 arulcancela.github.io

---

## PERFIL PROFESIONAL

Soy físico de formación y un constructor nato. Mi especialidad no es memorizar sintaxis
ni escribir código *boilerplate* desde cero, sino **orquestar inteligencia artificial**
(Gemini, DeepSeek, Claude, ChatGPT) y entornos agénticos para **diseñar, construir y
desplegar soluciones tecnológicas complejas a una velocidad sin precedentes**. Me defino
como un **AI-Augmented Engineer**.

Cuento con **15 años de experiencia** en infraestructuras Cloud, entornos híbridos y
migraciones Enterprise (con amplia trayectoria en Google Workspace, Microsoft 365 y GCP).
Mi base en Física Aplicada me confiere una alta capacidad de abstracción para entender
rápidamente la lógica de cualquier sistema y adaptarme con agilidad a nuevos entornos
tecnológicos, plataformas cloud o stacks de software.

Mi verdadero valor diferencial radica en el **desarrollo asistido por IA** aplicado a
automatizaciones de alto impacto en GAM y Python: comprendo la arquitectura, guío a la IA
con rigor lógico y **valido iterativamente el código con pruebas automatizadas** para
garantizar su robustez en producción.

En mi faceta más *maker*, gestiono mi propia infraestructura: modelos LLM en local con
Ollama (privacidad estricta), agentes de IA vía API, bots de trading y domótica avanzada
(Home Assistant en Raspberry Pi con Pi-hole). Busco retos en remoto donde aplicar esta
filosofía de *Ingeniero Aumentado*: usar la IA para multiplicar la eficiencia operativa,
resolver problemas de arquitectura y automatizar procesos en cualquier ecosistema.

**Disponibilidad:** Inmediata. Remoto (prioritario), híbrido flexible en Madrid o viajes puntuales.
Jornada completa, parcial o freelance/contractor (B2B).

---

## PROYECTOS DESTACADOS

> Portfolio completo y verificable en **github.com/arulcancela** — 7 repositorios,
> todos con integración continua (CI) y pruebas automatizadas.

### workspace-tenant-auditor — Auditoría de seguridad para Google Workspace
*Python · Admin SDK · Reports API · Service Account + Domain-Wide Delegation · Docker · CI/CD*

Herramienta CLI que audita la configuración de seguridad de un tenant de Google Workspace
ejecutando **12 comprobaciones** (usuarios sin doble verificación, superadmins, compartición
externa en Drive, aplicaciones OAuth de terceros, cuentas inactivas, unidades organizativas,
Vault...), prioriza los hallazgos por **severidad** y genera un **informe ejecutivo en
HTML/PDF/JSON** con evidencia y recomendaciones.

- **60 tests automatizados**, 78% de cobertura, integración continua (GitHub Actions).
- Arquitectura por capas y autenticación con **mínimo privilegio** (solo lectura).
- **Modo demostración** sin credenciales y ejecución reproducible con Docker.

🔗 github.com/arulcancela/workspace-tenant-auditor

### linkedin-job-hunter — Búsqueda y evaluación de ofertas con IA
*Python · Pydantic · LLM (Gemini/DeepSeek) · Notion API · Telegram Bot · CI/CD*

Sistema autónomo que busca ofertas de empleo, las evalúa de forma cuantitativa contra un
perfil profesional configurable mediante un LLM, calcula un **fit score (0-100)** y genera
un dossier con carta de presentación y nota de contacto.

- Evaluación por IA, detección de brechas de competencias y alertas automáticas.
- **Arquitectura por capas** (ingesta, motor, integraciones) y perfil configurable.
- **16 tests** con integración continua, incluyendo validación de ausencia de datos personales.

🔗 github.com/arulcancela/linkedin-job-hunter

### url-shortener — Acortador de URLs con analíticas
*Next.js 14 · TypeScript · Prisma · NextAuth · PostgreSQL · Vercel · CI/CD*

Aplicación web full-stack con autenticación, analíticas de clics en tiempo real, códigos QR
y rate limiting distribuido. **Desplegada en producción.**

- **41 tests unitarios** + pruebas end-to-end (Playwright).
- Arquitectura desacoplada y lógica de negocio testeable sin servidor.

🔗 github.com/arulcancela/url-shortener

### agente-deepseek — Agente administrador autónomo de Linux
*Python · openai (DeepSeek) · rich · pytest · CI/CD*

Agente de sistema que administra Linux en lenguaje natural, con **diseño seguro por
defecto**: clasifica las acciones, bloquea comandos destructivos y exige confirmación
antes de aplicar cambios reales.

- **Módulo de seguridad propio**: lista negra de comandos peligrosos y detección de
  comandos encadenados (`ls && rm -rf /` no engaña al validador).
- **18 tests** del validador de comandos y la configuración, con CI en GitHub Actions.

🔗 github.com/arulcancela/agente-deepseek

### agente-escritor — Pipeline multi-agente de redacción
*Python · LLM (DeepSeek) · RAG · Streamlit · SQLite*

Sistema que investiga, redacta, revisa y refina documentos técnicos mediante un
**pipeline de fases** (INGEST → RESEARCH → WRITE → REVIEW → REFINE → FINALIZE) con
roles especializados y **RAG**.

- Investigación web profunda, evaluación de calidad automática y exportación a PDF/DOCX.
- Interfaz web (Streamlit) con progreso en tiempo real.

🔗 github.com/arulcancela/agente-escritor

---

## HABILIDADES CLAVE & STACK TECNOLÓGICO

**Orquestación de IA & Entornos Agénticos**
Desarrollo agéntico y workflows asistidos por IA, Prompt Chaining avanzado, AI-Coding
iterativo, APIs de frontera (Gemini, DeepSeek, Claude, OpenAI), RAG
(Retrieval-Augmented Generation), arquitecturas de agentes autónomos.

**Arquitectura Cloud & Entornos Híbridos**
Arquitecturas cloud escalables, coexistencia Office 365 / Google Workspace / GCP (IAM,
BigQuery, Directory Sync), administración avanzada de tenants, DLP y seguridad.
Adaptable a AWS, Azure y Linux.

**Automatización con IA (Vibe Coding)**
GAM (Google Apps Manager) y Python mediante desarrollo asistido por IA con validación
analítica. APIs REST (FastAPI, Flask), web scraping y automatización avanzada. Rápida
asimilación y ejecución de soluciones en cualquier lenguaje o stack guiado por IA.

**Maker Lab, Soporte L4 & Metodología**
LLMs en local vía Ollama, agentes vía API, Raspberry Pi, Home Assistant, Pi-hole.
Escalados críticos L4 con Google (superadmin delegado), SLAs empresariales, Jira.
Inglés C1 profesional.

---

## EXPERIENCIA LABORAL

### Volkswagen Group Services Iberia — Google Workspace Architect & Migration Lead
*Abr 2026 – Oct 2026 · Remoto*

- **Estrategia Cloud:** liderazgo técnico de la estrategia de coexistencia híbrida entre
  Microsoft Office 365 y Google Workspace para la plantilla global corporativa.
- **Gestión del Cambio y Discovery:** dirección de la fase de Discovery, incluyendo auditoría
  de cumplimiento regulatorio (Compliance), definición de políticas de administración del
  tenant y diseño de planes de migración de usuarios.
- **Investigación y análisis acelerado por IA:** uso diario de LLMs (especialmente Gemini)
  como herramienta core para investigar, asimilar conceptos técnicos complejos y generar
  documentación técnica en tiempo récord.
- **Ingeniería de automatización asistida (AI-Coding):** dirección y testeo de la generación
  de código mediante IA para crear scripts y soluciones a medida que facilitan la coexistencia
  de plataformas, optimizando tiempos de despliegue sin requerir un equipo de desarrollo.

### Consultoría Independiente & Automatización — Desarrollador de Automatización y Consultor Cloud (Freelance)
*Sep 2019 – Actualidad · Madrid / Remoto*

- **Alcampo / Sabeco:** desarrollo de una solución a medida para la planificación de turnos a
  nivel nacional mediante plantillas inteligentes y scripts en Google Apps Script (asistidos
  por IA) para automatizar la gestión de personal en supermercados de toda España.
- **ByMotors:** consultoría de optimización de procesos digitales, rediseño de flujos de
  trabajo corporativos y automatización de reporting integral con Google Sheets.

### Inetum — Arquitecto de Soluciones Google Workspace
*Oct 2025 – Abr 2026 · Madrid*

- **Líder de Migración:** gestión integral (end-to-end) de la migración de 2.000 usuarios a
  Google Workspace.
- **Automatización Avanzada:** uso experto de GAM para extracción masiva de datos y scripting
  para automatizar la provisión, superando las limitaciones de la consola nativa.
- **Diseño de Arquitecturas:** modelado de arquitecturas cloud seguras, modulares y escalables
  para clientes Enterprise.

### Devoteam — Team Lead & Ingeniero de Soporte Senior (L4)
*May 2021 – Sep 2025 · Remoto*

- **Gestión Global:** soporte técnico bilingüe a una cartera de más de 200 clientes
  internacionales en entornos corporativos distribuidos.
- **Ingeniería Experta (L4):** gestión directa de escalados críticos con Ingeniería de Google,
  actuando con privilegios de superadmin delegado.
- **Calidad y Herramientas:** optimización de flujos de servicio con Jira Service Desk y
  Freshdesk, manteniendo valoraciones CSAT consistentemente excelentes.
- **Liderazgo:** mentoría y coordinación técnica de un equipo de 10 ingenieros de soporte,
  asegurando cumplimiento de SLAs.

### Nubalia — Ingeniero de Operaciones Senior & Especialista LumApps
*Abr 2019 – May 2021 · Madrid*

- **Gestión del Cambio:** diseño de planes de comunicación y formación técnica para garantizar
  la adopción exitosa de la nube.
- **Consultoría Preventa:** apoyo técnico al equipo comercial para definir alcances y cerrar
  propuestas de valor corporativas.
- **Referente en Intranets:** despliegue de LumApps, gestión de incidencias complejas y
  coordinación técnica directa con el fabricante.

### Intelligence Partner (The Cloud Consulting Company) — Ingeniero de Operaciones & Consultor Preventa
*Nov 2017 – Abr 2019 · Madrid*

- **Migraciones Técnicas:** ejecución de migraciones de datos para grandes cuentas
  corporativas, asegurando integridad total y cero pérdida de información.
- **Consultoría 360º:** gestión integral del ciclo preventa (toma de requisitos) → migración
  → formación → soporte.
- **Formador Técnico:** desplazamientos a sedes de clientes nacionales para impartir
  formación especializada.

### Grupo MASMOVIL — Analista de Datos
*Sep 2017 – Nov 2017 · Madrid*

- Análisis de datos avanzado y modelos de reporting corporativo mediante Excel.

### Accenture España — Consultor IT (Proyecto Internacional)
*Nov 2015 – Mar 2017 · Madrid / Riad, Arabia Saudí*

- **Experiencia Internacional (Riad):** investigación de software global y redacción técnica
  de pliegos y propuestas (RFIs / RFPs).
- **Gestión de PMO:** seguimiento y reporting financiero de proyectos con Office 365.

### Instituto de Cerámica y Vidrio (CSIC) — Técnico de Laboratorio (Prácticas)
*Jun 2014 – Sep 2014 · Madrid*

- Fabricación de materiales compuestos mediante molienda de alta energía, difracción XRD,
  microscopía electrónica SEM y magnetometría VSM.

---

## FORMACIÓN ACADÉMICA

**Grado en Física (Física Aplicada & Computacional)** — Universidad Complutense de Madrid
*2011 – 2015 · Madrid, España*

Base analítica rigurosa en modelización cuantitativa, sistemas dinámicos y resolución
estructurada de problemas complejos.

---

## CERTIFICACIONES

- **Google Cloud Platform:** Big Data and Machine Learning Fundamentals
- **LumApps:** LumApps Deployment Level 1
- **Física Atmosférica:** Formación en Meteorología (Sistemas Caóticos)

---

## IDIOMAS

- **Español:** Nativo
- **Inglés:** C1 profesional
