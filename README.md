# Mi Proyecto



&nbsp;Clase Git



Este repositorio contiene los ejercicios de la clase de Git y GitHub.  



\## Contenido

\- Ejemplo de uso de Git Bash

\- Creación de repositorios

\- Conexión con GitHub

\- Primeros commits



\## Autor

Julian Alvarez Mendoza



## Configuración inicial
Antes del primer commit configuramos identidad:
- `git config --global user.name "Nombre Usuario"`
- `git config --global user.email "julia.alvarezm@sofka.com.co"`
## Crear un repositorio local
Primeros pasos para iniciar un proyecto desde cero:
1. `mkdir mi_proyecto && cd mi_proyecto`
2. `git init`
3. Crear archivos y confirmar con `git add` + `git commit`.
## Flujo de trabajo básico
- Ver estado: `git status`
- Preparar cambios: `git add <archivo>` o `git add .`
- Confirmar cambios: `git commit -m "mensaje"`
- 'git push'
Recomendacion: hacer commits pequeños y con mensajes claros.
## Crear repositorio en GitHub
1. Ir a GitHub > New repository.
2. Nombrar el repo (recomendado sin espacios).
3. Crear vacío (sin README para evitar conflictos) y copiar la URL HTTPS/SSH.
## Conectar repositorio local con remoto
Vincular el repo local a GitHub:
- `git remote add origin https://github.com/usuario/repositorio.git`
Verificar: `git remote -v`.
## Subir cambios a GitHub
- Asegurar rama principal: `git branch -M main`
- Primer push (crea el upstream): `git push -u origin main`
- Siguientes pushes: `git push`
## Crear Cuenta en GitHub
- ingresar a 'GitHub.com'
- Crear cuenta con tu correo electrónico
- ingresar con julian.alvarezm@sofka.com.co
##  Subir cambios a GitHub
1. Asegurar que estamos en la rama principal:  
   `git branch -M main`
2. Subir cambios al remoto:  
   `git push -u origin main`
3. En los siguientes commits basta con:  
   `git push`
Buenas prácticas con Git
- Hacer commits pequeños y frecuentes.
- Usar mensajes claros y descriptivos.
- Crear ramas para nuevas funcionalidades:  
  `git switch -c nombre-rama`
- Mantener sincronizado el repositorio con:  
  `git pull --rebase` antes de `git push`.
## Creación de ramas
- Rama feature: para nuevas funcionalidades.
- Rama hotfix: para correcciones rápidas en producción.
- Rama develop: para integrar cambios antes de pasar a main.

