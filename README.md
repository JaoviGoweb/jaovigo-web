# JaoviGo Web — README Oficial

## 🚀 Introducción

JaoviGo Web es la plataforma principal del ecosistema de movilidad, comercio y conciencia JC–FL444. Esta web sirve como puerta de entrada para usuarios, riders, negocios aliados e inversionistas.

Construida con **Vite + React + TypeScript**, está diseñada para ser ultra rápida, escalable y global.

---

## 🌐 Características Principales

* 🔐 Sistema de autenticación (login, registro, recuperación)
* 🌍 Selector de idiomas (33 lenguajes)
* 🛵 Registro de Riders
* 🏪 Registro de Negocios
* 🛒 Tienda Cuántica (productos digitales, pagos múltiples)
* 📰 Sección de noticias
* ☁️ Clima + fecha + hora
* 💼 Portal de Inversionistas (Pitch Deck Access)
* 🎧 Integración con el activador cuántico JC–FL444
* ⚡ UI moderna con Tailwind + Shadcn/UI
* 🔌 Conexión futura a Supabase / Web3

---

## 🧱 Tech Stack

* **Frontend:** React + Vite + TypeScript
* **UI:** TailwindCSS + Shadcn/UI
* **State:** Context API / Zustand
* **i18n:** react-i18next (33 idiomas)
* **Backend recomendado:** Supabase
* **Deploy:** Vercel / Netlify / Cloudflare

---

## 📁 Estructura del Proyecto

```
jaovigo-web/
│   index.html
│   package.json
│   vite.config.ts
│
└───src/
    │   main.tsx
    │   App.tsx
    │
    ├───components/
    ├───pages/
    ├───context/
    ├───hooks/
    ├───services/
    ├───assets/
    └───i18n/
```

---

## ▶️ Instalación y Ejecución

```bash
npm install
npm run dev
```

---

## 🌍 Multi-Idioma (33 idiomas)

Implementación con i18next + JSON files.

```
src/i18n/
   en.json
   es.json
   fr.json
   ...
```

---

## 💼 Portal de Inversionistas

Incluye:

* Pitch Deck (versión pública)
* Documentos clave del proyecto
* Información de alianzas

---

## 🛒 Tienda Cuántica

* Productos digitales
* Activadores
* Audiomensajes
* Pagos: Stripe, Yape, Plin, Crypto (MetaMask / WalletConnect)

---

## 🔌 Backend (Recomendado)

**Supabase:**

* Auth
* Database
* Storage
* Edge functions

Tablas sugeridas:

* users
* riders
* business
* products
* orders
* news
* investors

---

## 🌐 Visión Global

La plataforma JaoviGo simboliza una movilidad con propósito, conectando tecnología, servicio y despertar consciente.

---

## 📘 Glosario JC–ENGL444

* Mobility Platform → Plataforma de movilidad
* Rider Registration → Registro de rider
* Investor Portal → Portal de inversionistas
* Digital Store → Tienda digital
* Scalable Architecture → Arquitectura escalable

---

## 📞 Contacto

Cuenta oficial del repositorio: **[jaovigoapp@gmail.com](mailto:jaovigoapp@gmail.com)**
