# Informe de Ejecución del Pipeline

## Resumen

Este informe describe los pasos realizados para configurar y ejecutar el pipeline de CI/CD para la empresa TechFlow.

## Pasos

1. **Inicialización del proyecto**
   - Se inicializó un proyecto en Node
   - Se configuro el archivo app.js con lo básico para una API


2. **Gestión del Repositorio Git**  
     
   - Se inicializó un repositorio local y se conectó a GitHub
   - Se hizo commit de una versión inicial de los archivos


3. **Configuración de Jenkins**  
     
   - Se configuró Jenkins para automatizar el proceso de construcción, prueba y despliegue
   - Se usó opción "Pipeline script from SCM"
   - Se usó nombre del Branch: main


## Problemas Encontrados

- Tuve problemas al ejecutar el pipeline, esto debido a que mi equipo funciona con windows y tuve que realizar los cambios de los scritps de sh a bat 

