# PayPhone Ecomerce

> Plataforma modular para e-commerce compuesta por frontend y backend, organizada como submódulos.

---

## 📂 Estructura del proyecto

Este repositorio raíz agrupa dos submódulos:

| Submódulo | Ruta local | Repositorio remoto |
|---|---|---|
| `web-payphone-ecomerce` | `web-payphone-ecomerce` | https://github.com/fasterydev/web-payphone-ecomerce.git |
| `api-payphone-ecomerce` | `api-payphone-ecomerce` | https://github.com/fasterydev/api-payphone-ecomerce.git |

El archivo `.gitmodules` contiene esta configuración:

```ini
[submodule "web-payphone-ecomerce"]
    path = web-payphone-ecomerce
    url = https://github.com/fasterydev/web-payphone-ecomerce.git
[submodule "api-payphone-ecomerce"]
    path = api-payphone-ecomerce
    url = https://github.com/fasterydev/api-payphone-ecomerce.git
