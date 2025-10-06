# 🛍️ PayPhone E-commerce - Integración completa con Next.js + NestJS

**PayPhone E-commerce** es una solución moderna y modular para integrar **pagos con PayPhone** en tiendas en línea.  
El proyecto está dividido en dos partes: un **frontend** en **Next.js** y un **backend API** en **NestJS**, ambos diseñados para escalar fácilmente y usarse por separado o en conjunto.

---

## 🚀 Tecnologías principales

- **Frontend:** [Next.js](https://nextjs.org/) + [shadcn/ui](https://ui.shadcn.com/)
- **Backend:** [NestJS](https://nestjs.com/)
- **Pagos:** [PayPhone API](https://payphone.app/)
- **Autenticación:** JWT
- **Despliegue:** Vercel, Docker, AWS o Render
- **Lenguaje:** TypeScript

---

## 📦 Estructura del proyecto

Este repositorio actúa como un **monorepo** con submódulos para cada servicio:

| Módulo | Descripción | Ruta local | Repositorio |
|---|---|---|---|
| **Backend (API)** | API REST con NestJS, conectada a PayPhone | `api-payphone-ecomerce` | [https://github.com/fasterydev/api-payphone-ecomerce](https://github.com/fasterydev/api-payphone-ecomerce) |
| **Frontend (Web)** | Tienda online y panel de administración en Next.js | `web-payphone-ecomerce` | [https://github.com/fasterydev/web-payphone-ecomerce](https://github.com/fasterydev/web-payphone-ecomerce) |

El archivo `.gitmodules` gestiona estos módulos automáticamente.

---

## ⚙️ Instalación

Clona el repositorio y descarga los submódulos:

```bash
git clone https://github.com/fasterydev/payphone-ecomerce.git
cd payphone-ecomerce
git submodule update --init --recursive
