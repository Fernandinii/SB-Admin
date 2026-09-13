# SB Admin - Dashboard Template Replica

Este repositorio contiene la réplica y maquetación del panel de administración basado en la plantilla oficial de [SB Admin (Start Bootstrap)](https://startbootstrap.com/previews/sb-admin).

El proyecto fue desarrollado de forma colaborativa utilizando **Git** y **GitHub**, aplicando un flujo de trabajo ramificado para dividir responsabilidades entre desarrolladores.

---

## Colaboradores y Roles

* **Developer 1:** Estructura semántica, maquetación HTML base (`index.html`, `tables.html`, etc.) y arquitectura de directorios.(elavorado por DIEGO FERNANDO DOMÍNGUEZ SÁNCHEZ)
* **Developer 2:** Hojas de estilo personalizadas (CSS), diseño visual, responsividad y componentes visuales.(elavorado por CARLOS EDUARDO DOMÍNGUEZ HERNANDEZ)

---

## Flujo de Trabajo en Git

Para garantizar un desarrollo ordenado e independiente, se establecieron las siguientes ramas:

* `main`: Rama de producción estable que contiene el código integrado y final.
* `developer1`: Rama de trabajo para la maquetación del esqueleto HTML.
* `developer2`: Rama de trabajo para los estilos CSS y apariencia visual.

### Ciclo de Integración:
1. Cada desarrollador realizó sus cambios en su respectiva rama (`developer1` / `developer2`).
2. Se subieron los cambios a GitHub mediante `git push origin <rama>`.
3. Se integraron las ramas hacia `main` a través de **Pull Requests / Merge**.

---

##  Estructura del Proyecto

```text
sbadmin/
├── assets/         # Recursos gráficos, iconos e imágenes
├── js/             # Scripts de interactividad y plugins
├── index.html      # Vista principal del panel de administración
├── tables.html     # Vista de tablas y datos estructurados
└── README.md       # Documentación del proyecto
