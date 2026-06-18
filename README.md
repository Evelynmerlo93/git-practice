

Apuntes de Git y GitHub
Git vs. GitHub
Git es un sistema de control de versiones distribuido que realiza un seguimiento de los cambios en el código fuente.

GitHub es una plataforma en la nube que aloja repositorios de Git y facilita la colaboración.

Por qué es importante el control de versiones
Mantiene un historial de cambios.

Facilita el trabajo en equipo.

Permite revertir errores.

Ayuda a gestionar diferentes versiones de un proyecto.

Conceptos principales
Repositorio (Repository)
Un repositorio almacena los archivos del proyecto y su historial de cambios.

Commit
Una captura o instantánea del proyecto en un momento específico.

Rama (Branch)
Una línea independiente de desarrollo.

Fusión (Merge)
Combina los cambios de una rama dentro de otra.

Clonar (Clone)
Crea una copia local de un repositorio remoto.

Comandos comunes de Git
Bash
git init
git add .
git commit -m "mensaje"
git status
git log
git push
git pull
git branch
git checkout
git merge
Estrategia de ramificación (Branching Strategy)
Flujo de trabajo común:

Plaintext
main
 ├── feature/login
 ├── feature/navbar
 └── feature/dashboard
main contiene el código estable.

Las ramas feature/ se utilizan para nuevas funcionalidades.

Pull Requests (Solicitudes de extracción)
Un Pull Request propone cambios de una rama a otra y permite revisar el código antes de realizar la fusión (merge).

Fork (Bifurcación)
Un fork es una copia del repositorio de otro usuario dentro de tu propia cuenta de GitHub.

GitHub Actions
GitHub Actions automatiza tareas como:

Ejecutar pruebas (tests).

Compilar aplicaciones.

Desplegar software (deployment).

Git Hooks
Los Git Hooks son scripts que se ejecutan automáticamente antes o después de que ocurran eventos específicos de Git.
Ejemplos:

pre-commit

post-commit

Issues (Incidencias / Tareas)
Los Issues se utilizan para reportar errores (bugs), proponer tareas o sugerir mejoras.

Milestones (Hitos)
Los Milestones agrupan issues y tareas relacionadas para hacer un seguimiento del progreso hacia un objetivo común.

Projects (Proyectos)
Los Projects ayudan a organizar el trabajo utilizando tableros visuales similares a Kanban.

Conclusión
Git y GitHub son herramientas esenciales para el desarrollo de software, ya que permiten el control de versiones, la colaboración, la revisión de código y la gestión de proyectos.