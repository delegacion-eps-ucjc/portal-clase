# Portal de clase

Portal para los **delegados y subdelegados de clase** de los grados de la Escuela Politécnica Superior de Tecnología y Ciencia de la Universidad Camilo José Cela: Robótica e IA, Informática y Telemática. Lo prepara la delegación de estudiantes de la Escuela.

Es una página estática que se abre en el navegador (también en el móvil, como una app). **No es una página oficial de la Universidad Camilo José Cela.**

## Qué tiene

- **Inicio:** lo urgente de la clase (exámenes de la semana, quejas abiertas, correos sin respuesta, plazos de notas) y el botón **Enviar parte a la delegación**.
- **Horario:** el oficial de cada curso, «¿Dónde está ahora?» y el horario y los huecos libres de cada profesor.
- **Exámenes:** las fechas oficiales del grado, los parciales y entregas que apuntes, el termómetro de carga y el calendario académico con los festivos.
- **Asignaturas:** la guía docente de cada una (carpeta `guias/`), los criterios y la calculadora de notas.
- **Quejas:** el tablero de la clase y el informe.
- **Correos:** plantillas para el profesorado, seguimiento de respuestas y recordatorios.
- **Normativa:** plazos de notas, revisión y reclamación según la normativa de evaluación de la UCJC.

## Privacidad

- **Este repositorio solo contiene el programa y las guías docentes.** No hay ningún dato de nadie.
- **Los datos de cada delegado se quedan en su navegador.** Nadie más los ve: ni la delegación de la Escuela ni la universidad.
- **Contraseña opcional** (AES-256, clave derivada con PBKDF2-SHA256, 600 000 iteraciones) y **copia compartida cifrada** entre delegado y subdelegado en un repositorio privado de GitHub de uno de los dos. GitHub solo ve un archivo cifrado.
- **El parte** solo sale del portal cuando el delegado lo copia o lo descarga, y no lleva nombres.
- La página no se indexa en buscadores y solo puede conectarse a `api.github.com`.
- No subas aquí copias de seguridad (`portal-clase-copia-*.json`): este repositorio es público.

## Actualizar

Sustituye `index.html` y `sw.js` por la nueva versión (y la carpeta `guias/` si cambian las guías docentes). Los datos de los delegados no se tocan: están en sus navegadores, no en el repositorio.

Versión 1 · 26 de octubre de 2026.
