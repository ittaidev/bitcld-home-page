# ☁️ bitCLD — Plataforma Autogestionada de Servicios en la Nube

> **Simple. Secure. Self-hosted.**

**bitCLD** es una plataforma autogestionada de servicios en la nube desarrollada sobre **Ubuntu Server** y basada en **contenedores Docker**.  
Su objetivo es ofrecer una infraestructura **segura, escalable y privada**, orientada a entornos personales o profesionales que buscan independencia de proveedores externos.

---

## 🚀 Descripción general

bitCLD integra distintos servicios de productividad, monitorización, seguridad y administración, todos gestionados de forma modular mediante Docker Compose y Dockge.  
La infraestructura se ejecuta en un servidor local, pero se expone de manera segura a través de **Cloudflare Tunnel** y **Cloudflare Access**, eliminando la necesidad de abrir puertos al exterior.

La arquitectura combina:
- 🐋 Contenedores **Docker** para cada servicio.
- 🔐 Acceso remoto protegido con **Tailscale VPN**.
- 🌐 Reverse proxy interno con **Caddy**.
- 🧠 Integraciones con **APIs y modelos de IA locales**.
- 📧 Correo profesional con dominio propio.
- 📊 Monitorización y gestión centralizada.

---

## 🧩 Servicios principales

| Categoría | Servicio | Función principal |
|------------|-----------|------------------|
| Infraestructura | **Docker** / **Dockge** | Despliegue y gestión de contenedores. |
| Acceso seguro | **Cloudflare Tunnel**, **Cloudflare Access** | Exposición segura de servicios sin abrir puertos. |
| Red privada | **Tailscale VPN** | Conexión remota por SSH y gestión fuera de la red local. |
| DNS y control local | **AdGuard Home** | DNS, bloqueador y redirecciones locales `.lan`. |
| Monitorización | **Uptime Kuma**, **Netdata** | Supervisión de servicios y métricas del sistema. |
| Almacenamiento y productividad | **Nextcloud** | Nube personal con sincronización y colaboración. |
| Seguridad y contraseñas | **Vaultwarden** | Gestor de contraseñas autoalojado compatible con Bitwarden. |
| Correo | **Zoho Mail** | Gestión de correo profesional con dominio propio. |

---


Los servicios se comunican internamente mediante una red Docker y se acceden externamente solo a través de Cloudflare o Tailscale.

---

## 🔒 Principios del proyecto

- **Privacidad:** todos los datos permanecen bajo control del usuario.  
- **Seguridad:** sin puertos abiertos, conexiones cifradas extremo a extremo.  
- **Autogestión:** cada servicio es independiente y fácilmente reemplazable.  
- **Escalabilidad:** arquitectura modular preparada para crecer.  
- **Simplicidad:** administración unificada y documentación clara.

---

## ⚙️ Tecnologías utilizadas

- **Sistema base:** Ubuntu Server 22.04 LTS  
- **Contenedores:** Docker, Docker Compose, Dockge  
- **VPN:** Tailscale  
- **Proxy / Certificados:** Caddy  
- **DNS local:** AdGuard Home  
- **Exposición externa:** Cloudflare Tunnel + Access  
- **Monitorización:** Uptime Kuma, Netdata  
- **Productividad:** Nextcloud  
- **Gestor de contraseñas:** Vaultwarden  
- **Correo:** Zoho Mail  
- **Documentación:** MkDocs Material

---

## 📖 Documentación

La documentación completa se encuentra en  
👉 [**bitcld.com/docs**](https://bitcld.com/docs) *(o en este mismo repositorio si se trata de la versión pública de documentación)*

Incluye:
- Instalación paso a paso  
- Configuración de cada servicio  
- Diagrama de red y arquitectura  
- Ejemplos de despliegue con Dockge  

---

## 🧠 Sobre el proyecto

Desarrollado por **Ittai Rivero** *([@ittaidev](https://github.com/ittaidev))* como proyecto técnico de infraestructura y ciberseguridad dentro de su formación en **Administración de Sistemas Informáticos en Red (ASIR)**.  

El propósito de **bitCLD** es servir como una **implementación práctica de una nube privada moderna**, integrando seguridad, automatización y autogestión.

---

### 🌐 Sitio web oficial

**[bitcld.com](https://bitcld.com)**  
> Infraestructura Segura, Escalable y Monitorizada
