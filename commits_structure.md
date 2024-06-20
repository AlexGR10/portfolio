# Estructura Commits:

Tipo [ámbito opcional]: <descripción> [cuerpo opcional] [nota de pie opcional]

## Componentes:

### Tipo: Describe el tipo de cambio que se realiza en el commit. Algunos tipos comunes son:

* feat: Introduce una nueva característica.
* fix: Arregla un error.
* docs: Actualiza la documentación.
* style: Cambios de formato, sin afectar la funcionalidad.
* refactor: Refactorización del código sin cambios de funcionalidad.
* perf: Mejora el rendimiento del código.
* test: Añade o modifica tests.
* chore: Cambios en la configuración, herramientas o tareas de desarrollo.
* build: Cambios en el sistema de build o despliegue.
* ci: Cambios en la configuración de integración continua.
* others: Otros tipos de cambios no categorizados en los anteriores.
* Ámbito (opcional): Describe la parte del proyecto afectada por el cambio. Se separa del tipo con dos puntos (:).

#### Ejemplo: feat: components/button.


### Descripción: Describe brevemente el cambio realizado. Debe ser claro, conciso y descriptivo.

* Ejemplo: Implementa el botón de acción principal.
* Cuerpo (opcional): Proporciona información adicional sobre el cambio, como detalles técnicos, contexto o razones del cambio. Se separa de la descripción con un salto de línea.
* Nota de pie (opcional): Se utiliza para información adicional que no sea directamente relevante para el cambio en sí, como enlaces a issues, referencias a otras commits o advertencias. Se separa del cuerpo con un salto de línea y se inicia con "BREAKING CHANGE:".

### Ejemplos:

* feat: Implementa el botón de acción principal
* feat: components/button: Añade la propiedad `disabled`
* fix: Corrige el error de carga de datos en la página de inicio
* docs: Actualiza la guía de usuario para la nueva API
* style: Aplica formato consistente a los títulos de sección
* refactor: Renombra la variable `oldName` a `newName`
* perf: Optimiza la consulta de base de datos para mejorar el rendimiento
* test: Añade tests unitarios para la nueva función de validación
* chore: Actualiza las dependencias de desarrollo
* build: Cambia el sistema de build a Webpack 5
* ci: Configura la integración continua con GitHub Actions
* others: Implementa la integración con Google Analytics
* BREAKING CHANGE: Se elimina la API `legacy`


## Beneficios de usar la convención de commits convencionales:

* Mejora la legibilidad: Los mensajes de commit son más fáciles de entender y permiten una rápida comprensión del tipo de cambio realizado.
* Facilita la búsqueda: Permite buscar commits por tipo, ámbito o descripción.
* Promueve la colaboración: Ayuda a los miembros del equipo a comprender mejor los cambios realizados por otros.
* Automatiza tareas: Herramientas como GitHub Actions pueden automatizar tareas basándose en el tipo de commit.
