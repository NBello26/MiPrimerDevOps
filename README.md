# MiPrimerDevOps

Este es un proyecto inicial que sigue buenas prácticas de DevOps. Fue creado como parte de una actividad educativa para aprender sobre control de versiones, automatización de flujos de trabajo y colaboración en equipos de desarrollo.


## 📌 Objetivo del Proyecto

Aprender a:
- Utilizar Git y GitHub de manera profesional.
- Trabajar con ramas y commits significativos.
- Configurar flujos de trabajo con GitHub Actions.
- Mantener una documentación clara y útil.
- Aplicar buenas prácticas de colaboración en proyectos de software.

## 🛠️ Estructura del Repositorio

MiPrimerDevOps/
│
├── .github/
│ └── workflows/
│ └── markdown-lint.yml # Workflow de validación Markdown
│
├── README.md # Descripción general del proyecto
├── CONTRIBUTING.md # Reglas para contribuir al proyecto
├── CHANGELOG.md # Registro de cambios
├── LICENSE.md # Licencia del proyecto
└── .markdownlint.json # Reglas de validación Markdown


## Automatización (CI/CD)

Este repositorio cuenta con un workflow de GitHub Actions que:
- Se activa en cada `push` o `pull request`.
- Ejecuta la acción `DavidAnson/markdownlint-cli2-action@v20`.
- Valida todos los archivos `.md` según las reglas definidas en `.markdownlint.json`.
- Falla si algún archivo no cumple con las reglas.

Puedes ver los resultados en la pestaña [Actions](https://github.com/NBello26/MiPrimerDevOps/actions).

## Flujo de trabajo con ramas

Usamos el siguiente flujo de ramas:
- `main`: Rama principal, estable.
- `feature/changelog-doc`: Para documentación de CHANGELOG.md.
- `feature/contributing-doc`: Para documentación de CONTRIBUTING.md.
- `feature/workflow-markdown`: Para creación de workflow que permite verificar correcto formato de archivos md.

## ¿Cómo contribuir?

Lee el archivo [CONTRIBUTING.md](./CONTRIBUTING.md) para conocer las reglas de colaboración.

## Historial de cambios

Puedes revisar el archivo [CHANGELOG.md](./CHANGELOG.md) para ver los cambios más relevantes por versión.

## Licencia

Este proyecto está licenciado bajo la [MIT License](./LICENSE.md).

---

¡Gracias por visitar el proyecto! ✨
