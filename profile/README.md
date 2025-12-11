<div align="center">


  # 👋 ¡Bienvenido al Repositorio de IONOS HUB!

  **El núcleo donde la consultoría, los datos y el código se encuentran.**
  
  [![Internal Only](https://img.shields.io/badge/Access-Internal_Team-red?style=for-the-badge&logo=lock)](https://github.com/orgs/IONOS-HUB/people)
  [![Tech Stack](https://img.shields.io/badge/Stack-Modern-blue?style=for-the-badge&logo=github)](https://github.com/orgs/IONOS-HUB/repositories)
  [![Documentation](https://img.shields.io/badge/Docs-Confluence%2FWiki-green?style=for-the-badge&logo=confluence)](THE_LINK_TO_YOUR_WIKI)

</div>

---

## 🧭 ¿Qué es este lugar?

Este es el repositorio central de **IONOS HUB**. Aquí no solo almacenamos código; construimos los activos digitales de nuestros clientes y nuestras propias herramientas internas.

Este espacio está diseñado para:
1.  **Centralizar el conocimiento:** Evitar silos de información.
2.  **Estandarizar la calidad:** Todos codificamos bajo las mismas reglas.
3.  **Fomentar la colaboración:** El código es de todos, no de una sola persona.

---

## 🗺️ Mapa de Navegación del Ecosistema

Para mantener el orden, nuestros repositorios siguen una nomenclatura estricta. Si vas a crear uno nuevo, asegúrate de que encaje en estas categorías:

| Prefijo | Descripción | Ejemplo |
| :--- | :--- | :--- |
| `client-` | Proyectos facturables para clientes externos. | `client-empresaX-ecommerce` |
| `int-` | Herramientas internas y scripts de automatización. | `int-dashboard-rrhh` |
| `infra-` | Código de infraestructura (Terraform, Ansible, K8s). | `infra-aws-base` |
| `poc-` | Pruebas de concepto y experimentos (Sandbox). | `poc-nuevo-framework-ai` |
| `data-` | Pipelines de datos, ETLs y notebooks. | `data-analisis-ventas` |

---

## ⚔️ Nuestros Mandamientos de Desarrollo (The IONOS Way)

Para mantener la salud mental del equipo y la calidad del código, seguimos estas reglas de oro:

### 1. Flujo de Trabajo (Gitflow Simplificado)
* 🟢 **`main`**: Producción. Sagrado. Intocable sin Review.
* 🟡 **`develop`**: Integración. Donde se unen las features.
* 🔵 **`feature/nombre-tarea`**: Donde trabajas tú.

### 2. Commits Semánticos
¡Nada de _"fix bug"_ o _"cambios"_! Usamos [Conventional Commits](https://www.conventionalcommits.org/):
* `feat:` Nueva funcionalidad.
* `fix:` Corrección de errores.
* `docs:` Cambios en documentación.
* `chore:` Tareas de mantenimiento (builds, herramientas).

### 3. Pull Requests (PR)
Nadie hace merge a `main` o `develop` sin la aprobación de al menos **un compañero**.
> *💡 Tip: Tu PR debe tener una descripción clara, screenshots (si es front) y pasos para testear.*

---

## 🚀 Onboarding para Nuevos Miembros

¿Acabas de aterrizar en IONOS HUB? ¡Genial tenerte aquí! Sigue estos pasos para despegar:

1.  **Configura tu entorno:** Revisa el repo `int-setup-guide` para instalar las herramientas base (Docker, VS Code, VPN).
2.  **Únete a la comunicación:**
    * 💬 **Slack/Discord:** Canal `#dev-general` para dudas técnicas.
    * 📋 **Jira/Trello:** Solicita acceso a tu Project Manager.
3.  **Lee la Wiki:** [Enlace a tu Wiki o Notion interno] para entender la cultura.

---

## 🛠️ Stack Tecnológico Principal

Aunque somos agnósticos según el cliente, estas son nuestras tecnologías "Casa":

<code><img height="30" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/python/python.png"></code>
<code><img height="30" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/javascript/javascript.png"></code>
<code><img height="30" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/docker/docker.png"></code>
<code><img height="30" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/aws/aws.png"></code>

*(Si necesitas usar una tecnología nueva, abre un issue en `int-architecture-review` para discutirlo).*

---

<div align="center">

  ### ¿Necesitas ayuda?
  No sufras en silencio. El equipo está para apoyarte.
  
  [🐛 Reportar un Bug Interno](LINK_A_ISSUES) • [☕ Pedir una sesión de Pair Programming](LINK_A_CALENDARIO)

  _Happy Coding!_ 🚀
  
  **IONOS HUB Team**

</div>
