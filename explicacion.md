# Sistema de Selección e Inscripción de Cursos con Tau Prolog

Este proyecto es una pequeña aplicación web que permite a alumnos y tutores:

- Consultar el progreso académico de un alumno (cursos aprobados, disponibles y bloqueados).  
- Verificar si un alumno puede inscribirse en un curso específico.  
- Identificar los prerrequisitos faltantes** si un curso no es elegible.

La lógica está implementada en Prolog y la interfaz en JavaScript y HTML usando la biblioteca Tau Prolog.  
Todos los archivos necesarios permiten que la aplicación funcione sin conexión a Internet.

---

## Estructura del proyecto

- `tau-prolog.js`: Permite el funcionamiento offline de la aplicación.  
- `pro.html`: Interfaz principal.  
- `explicacion.md`: Explicación del proyecto.  

---

## Requisitos

- Navegador web moderno (Chrome, Firefox, Edge, etc.).  
- No requiere servidor ni base de datos.  
- Funciona completamente **offline** gracias a los archivos locales de Tau Prolog. 

## Instalación

1. **Clonar o descargar el proyecto**:

   abrit git bash
   # Inicializar git en la carpeta
   git init

   # Cambiar el nombre de la rama principal a main
   git branch -m main

   # Agregar un remoto con la dirección del repositorio
   git remote add origin https://github.com/JuanG1504/progr-martes-y-jueves-1-3-pm

   # Descargar el proyecto
   git pull origin main 

También puedes descargar el proyecto como ZIP

## Uso

1.-Seleccionar alumno:
    En el primer menú desplegable elige un alumno de la lista.

2.-Verificar inscripción:

   En la tarjeta amarilla selecciona un curso específico.
   Pulsa el botón "Verificar inscripción".
   
 
3.Consultar estado académico:
    Pulsa el botón "Consultar estado académico" para ver tres listas:

    -Cursos aprobados.

    -Cursos que puede inscribir.

    -Cursos con requisitos faltantes.

El sistema mostrará:
    -Si el curso ya está completado.

    -Si cumple con todos los requisitos para inscribirlo.

    -Si no cumple los requisitos y qué cursos le faltan.


