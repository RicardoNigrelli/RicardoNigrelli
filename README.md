# 👋 Ricardo Nigrelli · Full Stack Developer & UX/UI Designer

🌐 **[ricardonigrelli.is-a.dev](https://ricardonigrelli.is-a.dev)** · [LinkedIn](https://linkedin.com/in/ricardonigrelli)

## 👤 Sobre mí | About Me

Desarrollador full stack con dos años de experiencia sobre software en producción, y diseñador UX/UI con formación específica y sistemas de diseño propios. Trabajo a diario con **Next.js, React y TypeScript** del lado del cliente y con **PHP y Laravel** del lado del servidor, integrando APIs y lógica de negocio sobre una base de código existente.

Mantengo además software propio en uso real: un sistema de proyección en vivo sincronizado por WebSockets que operan otras personas además de mí.

Actualmente trabajo en **Lisicki Litvin & Asociados** como Desarrollador Web.

---

Full stack developer with two years of experience on production software, and UX/UI designer with formal training and design systems of my own. I work daily with **Next.js, React and TypeScript** on the client and **PHP and Laravel** on the server, integrating APIs and business logic into an existing codebase.

I also maintain my own software in real use: a live projection system synchronised over WebSockets, operated by people other than me.

Currently at **Lisicki Litvin & Asociados** as a Web Developer.

---

## 💻 Tech Stack

### Frontend
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white) ![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white) ![HTML5](https://img.shields.io/badge/HTML5-E34C26?style=flat&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)

### Backend & APIs
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat&logo=php&logoColor=white) ![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=flat&logo=laravel&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white) ![Express](https://img.shields.io/badge/Express-000000?style=flat&logo=express&logoColor=white) ![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat&logo=nestjs&logoColor=white) ![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=flat&logo=socketdotio&logoColor=white)

### Bases de datos | Databases
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat&logo=postgresql&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-00758F?style=flat&logo=mysql&logoColor=white) ![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat&logo=prisma&logoColor=white)

### Cloud y datos | Cloud & Data
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white) ![Google Cloud](https://img.shields.io/badge/Google%20Cloud-4285F4?style=flat&logo=googlecloud&logoColor=white) ![BigQuery](https://img.shields.io/badge/BigQuery-669DF6?style=flat&logo=googlebigquery&logoColor=white) ![Cloud Run](https://img.shields.io/badge/Cloud%20Run-4285F4?style=flat&logo=googlecloud&logoColor=white) ![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat&logo=apacheairflow&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)

### Diseño y herramientas | Design & Tools
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat&logo=figma&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white) ![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat&logo=vercel&logoColor=white) ![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=flat&logo=visualstudiocode&logoColor=white)

---

## 🚀 Proyectos | Projects

> **📌 Nota:** Los proyectos que siguen son desarrollos propios y software sin fines comerciales para la comunidad en la que participo como voluntario.
> **Note:** The projects below are my own work and non-commercial software for the community where I volunteer.

### 1. Urban Proyecta · Sistema de proyección en vivo
- **Código | Code:** [live-worship-projection](https://github.com/RicardoNigrelli/live-worship-projection)
- **Stack:** Next.js 14 (App Router) · TypeScript · Zustand · Node + Express · Socket.IO · Prisma · PostgreSQL · Cloudinary

Un panel de operador controla letras, placas y multimedia, y las pantallas conectadas se sincronizan en tiempo real, con aislamiento por sala para servicios simultáneos. Separé el operador de la pantalla, de modo que la proyección se controla desde cualquier dispositivo sin estar sentado en la máquina del proyector.

**En uso real desde mayo de 2026, operado por tres personas.**

---

### 2. Urban Songbook · Cancionero para equipos de música
- **Stack:** Next.js · TypeScript · Drizzle ORM · PostgreSQL (Neon) · Web Push · Zod

Canciones con acordes, transposición de tonalidad y capo personal; setlists con convocatoria y confirmación de asistencia; atril para el músico con acceso autenticado o por enlace público; y permisos diferenciados por rol entre líder, editor y miembro. Documento y ejecuto una ronda de QA de extremo a extremo por cada versión, cubriendo cada flujo con los tres roles.

**En uso por un equipo de cinco personas.** La instancia pública es la productiva, con datos de personas reales, así que **la demo está pendiente**; puedo mostrarla en vivo en una llamada. | *The public instance is the production one, with real people's data, so **a demo is pending**; I can walk through it live on a call.*

---

### 3. Facturación electrónica ARCA/AFIP · Backend
- **Stack:** NestJS · TypeScript · TypeORM · BullMQ + Redis · PostgreSQL · Swagger

API de facturación electrónica que emite comprobantes fiscales a partir de operaciones de un sistema transaccional. Emisión asincrónica con colas y reintentos, idempotencia en dos niveles (constraint único en base y verificación previa contra el organismo) y persistencia completa de cada request y response para auditoría.

**La copia pública corre siempre contra un AFIP simulado, forzado en código y no por variable de entorno.**

---

### 4. Falsa Boda · Landing de evento con preinscripción
- **En línea | Live:** [falsaboda.urbanbuenosaires.org](https://falsaboda.urbanbuenosaires.org/)
- **Stack:** Next.js · TypeScript · Tailwind CSS · Prisma · PostgreSQL (Neon) · Resend

Landing e inscripción automática para un evento experiencial: formulario validado, confirmación por email, panel de administración y seguimiento de inscripciones.

---

### 5. Citas Seguras · Investigación UX y diseño de producto
- **Caso | Case study:** [presentación](https://docs.google.com/presentation/d/1por20vgzmDIxu-0HylNDiSlD3v0UgIRO/edit)
- **Herramientas | Tools:** Figma · UX research · Benchmarking · Entrevistas · Prototipado

Investigación UX sobre la categoría de apps de citas, con foco en seguridad, autenticidad y encuentros presenciales. Incluye análisis competitivo, entrevistas, wireframes, diseño de interfaz y prototipo interactivo.

---

### 6. ELPLAC · Proyecto final de bootcamp (equipo)
- **Frontend:** [elplacfrontend-deploy.vercel.app](https://elplacfrontend-deploy.vercel.app/)
- **Video:** [presentación en YouTube](https://www.youtube.com/watch?v=m5Fa3KSSaPo)
- **Stack:** Next.js · React · NestJS · TypeORM · PostgreSQL · Socket.IO · Mercado Pago

Plataforma de ferias virtuales y presenciales con perfiles de comprador, vendedor y administración. Equipo de 7 personas, 4 semanas. **Mi rol: desarrollo frontend.**

---

## 🎓 Formación | Education

| Programa | Institución | Duración | Estado |
|---|---|---|---|
| **Google Cloud Computing Foundations** | Google Skills / Talento Tech | Desde Sep 2026 | ▶️ En curso |
| **Licenciatura en Psicología** | Universidad Abierta Interamericana | 2021 - 2027 | ▶️ En curso |
| **IBM SkillsBuild: Fundamentos de IA** | IBM | Sep - Dic 2025 | ✅ Completado |
| **UI Design Avanzado** | Talento Tech | Mar - Jul 2025 | ✅ Completado |
| **UX/UI Design** | Talento Tech | Sep - Dic 2024 | ✅ Completado |
| **Full Stack Developer** | Henry | Mar - Ago 2024 | ✅ Completado |
| **English Certificate B2** | EF SET | 2024 | ✅ Certificado |

---

## 💼 Experiencia | Experience

### Desarrollador Web Semi Senior — Lisicki Litvin & Asociados
**Sep 2025 - Presente**
- Módulos y aplicaciones web para los equipos internos de una organización de ~600 personas, integrados con los servicios, APIs y lógica de negocio existentes
- Ciclo completo de cada módulo, del diseño de la interfaz a su implementación
- **Azure:** capa de integración para un cliente que pasó de intercambiar archivos por FTP a exponer una API. Data Factory converge las llamadas contra una Function App, sin paso por Blob Storage, con pipelines por dominio de datos; en la Function App queda el control de cada etapa del ETL, los stored procedures y las tablas de cada nivel
- **Google Cloud:** diseñé y construí la automatización de un proceso que un cliente resolvía a mano en Excel y PowerPoint — integración con IBM Planning Analytics, ETL sobre BigQuery, cálculos en un servicio en Cloud Run y agendamiento con un DAG en Cloud Composer. Separé las etapas para escalar: el resultado queda en una tabla que hoy consume Power BI y que puede consumir cualquier aplicación

### Desarrollador Web Junior — Lisicki Litvin & Asociados
**Sep 2024 - Ago 2025**
- Resolución de incidencias sobre una base de código en producción en PHP/Laravel y JavaScript
- Trabajo sobre funcionalidades ya en uso, dentro de un equipo de cinco desarrolladores

### Desarrollos propios y voluntariado
**Jun 2024 - Presente**
- Software propio en uso real: proyección en vivo sincronizada por WebSockets
- UX research, benchmarking y análisis competitivo
- Diseño de interfaz y sistemas de diseño en Figma
- Frontend en React y Next.js; backend en Node, Express y NestJS
- Despliegue y mantenimiento

### Ventas y relación con clientes
**PepsiCo, Distribuidora Ronaldo e In-Store | 2018 - 2024**
- Cartera de clientes en CABA, capacitación de vendedores nuevos y manejo de presupuesto en puntos de venta
- Habilidades transferibles: pensamiento centrado en el usuario, perspectiva de negocio, comunicación

### Voluntariado — ABUA
**2019 - 2024**
- Liderazgo de grupos y acompañamiento a adolescentes y jóvenes

---

## 📍 Ubicación y disponibilidad

📌 **Buenos Aires, Argentina** (UTC-3)
🌍 Abierto a equipos remotos

---

## 📬 Contacto | Get in Touch

| [LinkedIn](https://linkedin.com/in/ricardonigrelli) | [Portafolio](https://portafolio-rn-beta.vercel.app) | [Email](mailto:ricanigrelli996@gmail.com) |
|:---:|:---:|:---:|
