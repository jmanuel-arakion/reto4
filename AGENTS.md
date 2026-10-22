# Instrucciones para Codex

## Objetivo y contexto

El usuario quiere trabajar en este repositorio con Codex CLI desde un servidor Linux y conservar aquí las instrucciones útiles de su conversación con Codex en la nube.

- Responde en español.
- Repositorio: `jmanuel-arakion/reto4` en GitHub.
- Al revisar el repositorio el 22 de octubre de 2026, estaba vacío: no había código, commits, dependencias ni pruebas. No se ha elegido todavía el tipo de aplicación que se desarrollará.
- Se comprobó el acceso de lectura a GitHub desde el entorno en la nube. Esto no garantiza acceso desde otro servidor.
- El entorno en la nube y el servidor Linux del usuario son máquinas distintas. No supongas que comparten archivos, procesos, credenciales ni conversaciones.

## Forma de trabajar

1. Revisa el estado actual del repositorio y sus instrucciones antes de actuar; este contexto describe una revisión anterior y puede quedar desactualizado.
2. Usa el checkout existente. No crees un worktree salvo que el usuario lo pida expresamente.
3. Conserva los cambios del usuario y no incluyas contraseñas, tokens ni otros secretos en archivos, commits o mensajes.
4. Para configurar el entorno, sigue la documentación, las versiones fijadas y los archivos de bloqueo que tenga el proyecto. Comprueba la instalación con las pruebas o el arranque real que corresponda.
5. Mientras la tarea sea solo configurar el entorno, conserva el código, las pruebas, los manifiestos y los archivos de bloqueo. Si hacen falta cambios de aplicación, explícalos como una tarea separada.
6. Si aún no existe una aplicación y el usuario pide desarrollarla sin definir su objetivo, solicita la información necesaria antes de inventar requisitos.

## Continuidad entre sesiones

Este archivo comparte instrucciones y contexto; no sincroniza el historial del chat ni establece una conexión entre agentes. Lee también las instrucciones nuevas que dé el usuario en la sesión actual. Actualiza el contexto persistente cuando el usuario lo solicite, sin guardar secretos ni afirmar que se han realizado comprobaciones que no se ejecutaron.
