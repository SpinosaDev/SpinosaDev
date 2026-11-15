<div align="center">
  <h1>⚡ SpinosaDev</h1>
  <p><strong>Programador Full-Stack & Mobile · Creador de Software de 0 a 100</strong></p>
  
  <p>
    <a href="https://github.com/SpinosaDev">
      <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=15&duration=2600&pause=1000&color=38BDF8&center=true&vCenter=true&width=650&lines=Desarrollo+Full-Stack+%26+Mobile+de+Extremo+a+Extremo;Backend+Robusto+con+FastAPI+%26+Python+3.12;Apps+M%C3%B3viles+Offline-First+con+Kotlin+%26+Jetpack+Compose;Sistemas+Criptogr%C3%A1ficos+E2EE+en+Rust+(vault-core);Gobernanza+Zero-Trust+%26+Cero+Fugas;Automatizaci%C3%B3n+con+Agentes+Aut%C3%B3nomos+e+IA" alt="Typing Status" />
    </a>
  </p>

  <p>
    <a href="https://github.com/SpinosaDev/stockflow-pro-">
      <img src="https://img.shields.io/badge/📦_Proyecto_Principal-StockFlow_Pro-0284C7?style=for-the-badge&logo=fastapi&logoColor=white" alt="StockFlow Pro" />
    </a>
    <img src="https://img.shields.io/badge/🔐_Seguridad-DevVault_Rust_E2EE-7C3AED?style=for-the-badge&logo=rust&logoColor=white" alt="DevVault" />
    <img src="https://img.shields.io/badge/📱_Multiplataforma-Kotlin_Compose-E4405F?style=for-the-badge&logo=kotlin&logoColor=white" alt="Kotlin Multiplatform" />
    <img src="https://img.shields.io/badge/🛡️_Seguridad-Zero--Trust_Architecture-059669?style=for-the-badge" alt="Zero-Trust" />
  </p>
</div>

---

### 🚀 Sobre Mí

Programador full stack enfocado en crear **aplicaciones completas, funcionales y listas para producción de principio a fin**:

* 🏢 **Plataformas SaaS & Gestión Operativa:** Creador de **StockFlow Pro**, plataforma completa para operadoras de telecomunicaciones y despliegues de fibra óptica (FTTH): backend en FastAPI, 27 módulos web protegidos por roles (RBAC), facturación fiscal adaptada a **Veri\*factu (RD 1007/2023)** y control automático de compras (EOQ).
* 📱 **Desarrollo Móvil Nativo & Offline-First:** Desarrollo de aplicaciones Android fluidas y reactivas con **Kotlin** y **Jetpack Compose**, persistencia local con **Room DB** para trabajo en campo sin cobertura, biometría y escaneo de códigos.
* 🔒 **Sistemas & Seguridad Práctica:** Desarrollo con mentalidad **Zero-Trust y Zero-Leak** (cero fugas de credenciales). Creador de **DevVault**, gestor de secretos con núcleo en **Rust (`vault-core`)**, derivación **Argon2id**, cifrado **XChaCha20-Poly1305 / AES-256-GCM**, canales seguros E2EE y limpieza de memoria con `zeroize`.
* 🤖 **Automatización & Ecosistemas IA:** Integración de flujos de desarrollo asistido con agentes autónomos especializados (*backend, UI móvil, seguridad*) y herramientas conectadas mediante protocolos **MCP**.

---

### 🏛️ Estructura del Ecosistema

```
┌─────────────────────────────────────────────────────────────────────────────────────────┐
│                                 SPINOSADEV ARCHITECTURE                                 │
├───────────────────────────────┬───────────────────────────────┬─────────────────────────┤
│       APLICACIONES MÓVILES    │       CRM & PANELES WEB       │   SEGURIDAD & CRYPTO    │
│  - Android Nativo (Compose)   │  - 27 Módulos Aislados (RBAC) │  - DevVault (Rust Core) │
│  - Kotlin Multiplatform (KMP) │  - Modo Oscuro Anti-Flashbang │  - Canales E2EE X25519  │
│  - Offline-First (Room DB)    │  - Facturas Veri*factu        │  - Argon2id / Poly1305  │
│  - Biometría & Escáner QR/Bar │  - Control Stock Auto-PO      │  - Limpieza con Zeroize │
├───────────────────────────────┴───────────────────────────────┴─────────────────────────┤
│                                SERVICIOS REST & BACKEND                                 │
│      FastAPI (Python 3.12) · 16 Routers Modulares · JWT · Rate Limiting · Uvicorn       │
├─────────────────────────────────────────────────────────────────────────────────────────┤
│                             BASE DE DATOS & PERSISTENCIA                                │
│       PostgreSQL / Supabase (RLS Multi-Tenant · 19 Migraciones) · SQLite Local          │
└─────────────────────────────────────────────────────────────────────────────────────────┘
```

---

### 🛠️ Tecnologías & Herramientas

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,fastapi,rust,kotlin,androidstudio,postgres,supabase,sqlite,docker,linux,git,github,bash,postman,tailwind,html,css,js,vscode" alt="Tech Stack" />
</p>

| Área | Tecnologías | Uso Principal |
| :--- | :--- | :--- |
| **Backend & APIs** | `Python 3.12` · `FastAPI` · `Pydantic` · `Uvicorn` · `Ktor` | APIs REST asíncronas, autenticación JWT, lógica de negocio y servicios |
| **Móvil Android & Multiplataforma** | `Kotlin 2.0` · `Jetpack Compose` · `Compose Multiplatform` · `Room` | Apps de campo, arquitectura MVVM/MVI, WorkManager, escáner y biometría |
| **Sistemas & Criptografía** | `Rust` · `Argon2id` · `XChaCha20-Poly1305` · `AES-256-GCM` | Núcleo `vault-core`, derivación segura de contraseñas, canales E2EE y `zeroize` |
| **Bases de Datos** | `PostgreSQL` · `Supabase (RLS)` · `SQLite (Room)` | Modelado de datos, consultas optimizadas, RLS multi-tenant y migraciones SQL |
| **Frontend & Web** | `HTML5` · `Tailwind CSS` · `JavaScript Vanilla` | Dashboards interactivos, diseño responsive, temas claro/oscuro y componentes modulares |
| **Seguridad & Testing** | `Zero-Trust` · `Pytest (213+ tests)` · `Nuclei` · `JWT` | Auditoría de vulnerabilidades, pruebas automáticas de seguridad y lógica |
| **Herramientas & Entorno** | `Docker` · `Linux / Bash` · `Git / GitHub` · `Android Studio` | Control de versiones, contenedores, pruebas y despliegue |

---

### 📦 Proyectos Destacados

#### 🌐 1. [StockFlow Pro](https://github.com/SpinosaDev/stockflow-pro-)
> **Plataforma Integral SaaS para Operadoras de Telecomunicaciones y Despliegues de Fibra Óptica (FTTH).**

* **Backend FastAPI:** Estructura modular con 16 routers REST, control de acceso basado en roles (RBAC) y aislamiento estricto de clientes en base de datos.
* **CRM Web (27 Páginas Independientes):** Paneles administrativos y operativos para despacho de órdenes de trabajo (OTs), inventario, gestión de cuadrillas y tickets con SLAs.
* **Motor Fiscal Veri\*factu (RD 1007/2023):** Generación de facturas PDF 1.4 inmutables con encadenamiento criptográfico SHA-256 y códigos QR de verificación fiscal.
* **Reaprovisionamiento Inteligente (Auto-PO & EOQ):** Cálculo automático de pedidos de compra preventivos según stock mínimo.
* **App Móvil Android para Técnicos de Campo:** Solución nativa con sincronización offline-first, firma digital de partes, evidencias fotográficas y control de bobinas de fibra.
* **Pruebas Automatizadas:** Más de **213 tests automatizados** cubriendo lógica de negocio, endpoints y seguridad.

```
FastAPI 0.109  ·  Python 3.12  ·  Jetpack Compose  ·  Kotlin 2.0  ·  Supabase RLS  ·  Veri*factu
```

---

#### 🔐 2. DevVault — Zero-Knowledge Secrets & Cryptographic Bridge
> **Gestor de Contraseñas y Secretos Local con Núcleo en Rust y Cliente Compose Multiplatform.**

* **Núcleo Criptográfico en Rust (`vault-core`):** Desarrollado con foco en seguridad de memoria, derivación `Argon2id`, cifrado autenticado `XChaCha20-Poly1305` y limpieza garantizada de buffers sensibles en RAM (`zeroize`).
* **Canal E2EE en Tránsito:** Bridge criptográfico (`X25519-HKDF-AES256GCM`) para sincronización segura entre servidores locales/remotos y la bóveda física sin exponer texto plano.
* **Cliente Compose Multiplatform (CMP):** Interfaz unificada para Android, Desktop (JVM), Web (Wasm/JS) e iOS, con servidor Ktor ligero.
* **Filosofía Zero-Leak:** Cero exposición de credenciales en logs, trazas o almacenamiento temporal.

```
Rust  ·  Kotlin Multiplatform  ·  Compose Multiplatform  ·  Argon2id  ·  XChaCha20-Poly1305  ·  Ktor
```

---

#### 🤖 3. Automatización con Agentes & Herramientas MCP
> **Flujos de Trabajo Autónomos para Acelerar el Desarrollo.**

* Uso y orquestación de agentes especializados para tareas concretas:
  * ⚙️ **Backend:** Diseño de APIs asíncronas, migraciones de base de datos y esquemas de sincronización.
  * 🎨 **Frontend & Móvil:** Componentes en Jetpack Compose, diseño responsive y temas visuales.
  * 🛡️ **Seguridad:** Revisión de dependencias, auditoría de vulnerabilidades y buenas prácticas.
* Integración con servidores MCP para análisis de código y automatización en paralelo.

---

### 📊 Actividad en GitHub

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=SpinosaDev&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=38BDF8&icon_color=06B6D4&text_color=94A3B8" height="155" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=SpinosaDev&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=38BDF8&text_color=94A3B8" height="155" alt="Top Languages" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=SpinosaDev&theme=tokyonight&hide_border=true&background=0D1117&ring=38BDF8&fire=06B6D4&currStreakLabel=38BDF8" height="150" alt="GitHub Streak" />
</p>

---

### 📬 Contacto & Repositorios

<p align="center">
  <a href="https://github.com/SpinosaDev">
    <img src="https://img.shields.io/badge/GitHub-SpinosaDev-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
  <a href="https://github.com/SpinosaDev/stockflow-pro-">
    <img src="https://img.shields.io/badge/Repositorio-StockFlow_Pro-0284C7?style=for-the-badge&logo=git&logoColor=white" alt="StockFlow Pro" />
  </a>
</p>

<p align="center">
  <sub><em>"Construyendo soluciones funcionales, seguras y efectivas de principio a fin."</em></sub>
</p>
