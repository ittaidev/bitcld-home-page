# BitCLD — Ecosistema Autoalojado de Servicios en la Nube

**Simple. Seguro. Autoalojado.**

<p align="center">
  <img src="https://raw.githubusercontent.com/ittaidev/bitcld-homepage/main/images/logorecortenb.png" alt="bitCLD Banner" width="60%"/>
</p>

**BitCLD** es un ecosistema autoalojado de servicios en la nube diseñado para ofrecer una infraestructura segura, modular y privada, totalmente bajo el control del usuario.  
Combina contenedores Docker, redes seguras, monitorización y servicios de productividad en un entorno unificado, sin depender de proveedores externos.

---

## Descripción general

BitCLD integra distintos servicios orientados a la administración, la productividad y la ciberseguridad, todos gestionados de forma modular mediante Docker Compose y Dockge.  
La infraestructura se ejecuta en un servidor local, pero se expone de manera segura a través de **Cloudflare Tunnel** y **Cloudflare Access**, eliminando la necesidad de abrir puertos al exterior.

El proyecto está construido sobre los principios de privacidad, simplicidad operativa y autonomía tecnológica.

---

## Servicios principales

| Categoría | Servicio | Función principal |
|------------|-----------|------------------|
| Infraestructura | Docker / Dockge | Despliegue y gestión de contenedores. |
| Acceso seguro | Cloudflare Tunnel / Access | Exposición segura de servicios sin abrir puertos. |
| Red privada | Tailscale VPN | Conexión remota por SSH y gestión fuera de la red local. |
| DNS y control local | AdGuard Home | DNS, bloqueador y redirecciones locales `.lan`. |
| Monitorización | Uptime Kuma / Netdata | Supervisión de servicios y métricas del sistema. |
| Productividad | Nextcloud | Nube personal con sincronización y colaboración. |
| Seguridad y contraseñas | Vaultwarden | Gestor de contraseñas autoalojado compatible con Bitwarden. |
| Correo | Zoho Mail | Gestión de correo profesional con dominio propio. |

---

Los servicios se comunican internamente mediante una red Docker y se acceden externamente solo a través de Cloudflare o Tailscale.

---

## Principios del proyecto
 
- **Seguridad:** sin puertos abiertos, conexiones cifradas extremo a extremo.
- **Simplicidad:** administración unificada y documentación clara.
- **Autohospedado:** ecosistema totalmente independiente y autoalojado.
- **Privacidad:** todos los datos permanecen bajo control del usuario. 
- **Escalabilidad:** arquitectura modular preparada para crecer.  


---

## Tecnologías utilizadas

- Sistema base: **Ubuntu Server 22.04 LTS**  
- Contenedores: **Docker**, **Docker Compose**, **Dockge**  
- VPN: **Tailscale**  
- Proxy / Certificados: **Caddy**  
- DNS local: **AdGuard Home**  
- Exposición externa: **Cloudflare Tunnel** + **Access**  
- Monitorización: **Uptime Kuma**, **Netdata**  
- Productividad: **Nextcloud**  
- Gestor de contraseñas: **Vaultwarden**  
- Correo: **Zoho Mail**
- Publicación web: **GitHub pages y Cloudflare pages**  
- Documentación: **MkDocs Material**

---

## Documentación

La documentación completa se encuentra en  
[**docs.bitcld.com**](https://docs.bitcld.com)

Incluye:
- Instalación paso a paso  
- Configuración de cada servicio  
- Diagrama de red y arquitectura  
- Ejemplos de despliegue con Dockge  

---

## Sobre el proyecto

Desarrollado por **Ittai Rivero** ([ittaidev](https://github.com/ittaidev)) como proyecto técnico de infraestructura y ciberseguridad dentro de mi formación en **Administración de Sistemas Informáticos en Red (ASIR)**.  

El propósito de **bitCLD** es servir como una implementación práctica de una nube privada moderna, integrando seguridad, automatización y autogestión.

---


### Sitio web oficial

[**bitcld.com**](https://bitcld.com)  
_Ecosistema Autoalojado de Servicios en la Nube_



