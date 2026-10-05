# tarea_actions_1.2

## Datos del Alumno
* **Nombre:** David Rodríguez Pozo


---

## Capturas

Este bloque recoge la configuración de flujos de trabajo (workflows) para la integración continua (CI) mediante GitHub Actions, automatizando las pruebas y validaciones del proyecto Node.js.

### 1. Configuración del Workflow y Errores de Sintaxis
* **Descripción:** Creación del archivo de configuración en .github/workflows/ci.yml definiendo los trabajos en paralelo (test y lint). Corrección de errores de tabulación y palabras clave como steps: esenciales para la lectura del archivo YAML.
* **Evidencia Visual:**
  ![Configuración del Workflow](tarea_actions_1.2/img/actions_2_1.png)

### 2. Corrección del Entorno y Estructura JSON
* **Descripción:** Resolución de fallos en el ciclo de vida de la ejecución derivados de una sintaxis incorrecta en el archivo package.json (falta de comas de separación). Configuración del script de pruebas automatizadas mediante comandos nativos de Node.
* **Evidencia Visual:**
  ![Corrección de package.json](tarea_actions_1.2/img/actions_2_2.png)

### 3. Ejecución Correcta e Integración Continua (CI)
* **Descripción:** Validación final del flujo de trabajo en los servidores de GitHub. Los trabajos independientes se ejecutan de manera satisfactoria (código de salida 0), mostrando el indicador en verde (Build Success) en la pestaña Actions.
* **Evidencia Visual:**
  ![Éxito en GitHub Actions](tarea_actions_1.2/img/actions_2_3.png)


