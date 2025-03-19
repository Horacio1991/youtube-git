# Git y GitHub

## ¿Qué es Git?

Git es un sistema de control de versiones distribuido que permite a los desarrolladores rastrear cambios en el código fuente, colaborar en proyectos y mantener un historial completo de modificaciones. Es una herramienta esencial para el desarrollo de software moderno.

### Características principales de Git:

- **Control de versiones**: Permite gestionar cambios en el código de manera eficiente.
- **Ramas**: Facilita el trabajo en paralelo mediante ramas independientes.
- **Distribuido**: Cada desarrollador tiene una copia completa del repositorio.

## ¿Qué es GitHub?

GitHub es una plataforma basada en la nube que utiliza Git para alojar repositorios de código. Además, ofrece herramientas para la colaboración, la revisión de código, la gestión de proyectos y la integración continua.

### Beneficios de GitHub:

- **Colaboración**: Permite a equipos trabajar juntos en proyectos de manera eficiente.
- **Repositorios públicos y privados**: Ofrece opciones para compartir código o mantenerlo privado.
- **Integraciones**: Compatible con herramientas como CI/CD, seguimiento de problemas y más.

### Comandos básicos de Git:

```bash
# Clonar un repositorio
git clone <url-del-repositorio>

# Ver el estado del repositorio
git status

# Agregar cambios al área de preparación
git add <archivo>

# Confirmar cambios
git commit -m "Mensaje del commit"

# Enviar cambios al repositorio remoto
git push
```

### Comandos avanzados y colaborativos de Git:

```bash
# Crear y cambiar a una nueva rama
git checkout -b <nombre-de-la-rama>

# Cambiar a una rama existente
git checkout <nombre-de-la-rama>

# Fusionar una rama con la rama actual
git merge <nombre-de-la-rama>

# Actualizar el repositorio local con los cambios del remoto
git pull

# Ver el historial de commits
git log

# Ver las diferencias entre el área de trabajo y el área de preparación
git diff

# Resolver conflictos de fusión
# Edita los archivos con conflictos, luego:
git add <archivo-resuelto>
git commit -m "Conflictos resueltos"

# Eliminar una rama local
git branch -d <nombre-de-la-rama>

# Eliminar una rama remota
git push origin --delete <nombre-de-la-rama>

# Revertir un commit específico
git revert <id-del-commit>

# Restablecer el área de trabajo a un estado anterior
git reset --hard <id-del-commit>

# Etiquetar un commit
git tag -a <nombre-de-la-etiqueta> -m "Mensaje de la etiqueta"

# Subir etiquetas al repositorio remoto
git push origin --tags
```

Estos comandos son esenciales para trabajar en equipo, gestionar ramas, resolver conflictos y mantener un flujo de trabajo eficiente.
¡Comienza a usar Git y GitHub para gestionar tus proyectos de manera eficiente!
