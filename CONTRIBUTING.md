# Cómo trabajamos en RutaBahía
 
## Flujo de trabajo (GitHub Flow)
1. Tome una historia del tablero y muévala a **En curso**.
2. Actualice `main`: `git switch main` y `git pull`.
3. Cree su rama: `git switch -c feature/HU04-reservar`.
4. Haga commits pequeños con mensajes convencionales.
5. Suba la rama: `git push -u origin feature/HU04-reservar`.
6. Abra un pull request con la plantilla, enlace la historia con `Closes #n` y pida revisión.
7. Atienda los comentarios. Cuando lo aprueben, fusione y borre la rama.
 
## Nombres de ramas
| Tipo | Ejemplo |
|---|---|
| Funcionalidad | `feature/HU04-reservar` |
| Corrección | `fix/HU04-total-ninos` |
| Documentación | `docs/readme-instalacion` |
| Mantenimiento | `chore/proyecto-base` |
 
## Mensajes de commit
`tipo: qué cambió`, en presente y en minúscula.
 
| Tipo | Cuándo |
|---|---|
| `feat` | Funcionalidad nueva |
| `fix` | Corrección de un error |
| `docs` | Solo documentación |
| `refactor` | Mejora del código sin cambiar lo que hace |
| `chore` | Configuración, dependencias, archivos del proyecto |
 
## Definición de terminado
- Compila y se ejecuta sin errores.
- Cumple los criterios de aceptación de la historia.
- Respeta las capas: controlador → servicio → repositorio.
- No hay contraseñas ni datos sensibles en el repositorio.
- Tiene un pull request revisado y aprobado por un compañero.
- El tablero está actualizado.
 
## Revisión de código
- Revise que cumpla los criterios, que respete las capas y que los nombres se entiendan.
- Comente el código, no a la persona. Pregunte y sugiera.
- Aprobar es decir: «yo también respondo por este código».