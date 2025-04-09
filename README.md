# Curso de Frontend: Flujo de Trabajo Básico con Git en Grupo

## Descripción del Proyecto

Este proyecto es parte del curso de Frontend y está diseñado para que los estudiantes aprendan a crear la estructura básica de una página web utilizando HTML y CSS. Además, aprenderemos a trabajar colaborativamente utilizando Git y GitHub, adoptando un flujo de trabajo básico que incluye el uso de ramas, commits, push y pull requests.

## Objetivos

- **Crear una Página Web Básica:**  
  Desarrollar una estructura sencilla con HTML y CSS, estableciendo la base para proyectos frontend.

- **Aprender Git y GitHub:**  
  Familiarizarse con las operaciones fundamentales:
  - *Fork* del repositorio
  - Creación de ramas específicas para cada tarea
  - Realización de commits descriptivos
  - Envío de cambios a GitHub (push)
  - Gestión de pull requests para fusionar cambios en la rama principal

- **Colaboración en Equipo:**  
  Practicar un flujo de trabajo en grupo que incluya revisión de código y solución colaborativa de conflictos.

## Estructura del Proyecto

La organización básica del proyecto es la siguiente:

frontend/
├── assets/
│   ├── css/
│   ├── img/
│   └── js/       # (opcional)
├── index.html
└── README.md





## Flujo de Trabajo Básico

1. **Fork:**  
   Cada estudiante debe crear un fork del repositorio original en su cuenta de GitHub.

2. **Clonación y Entorno de Trabajo:**  
   Trabaja directamente en GitHub Codespaces o en el editor web sin necesidad de configuración local.

3. **Creación de Ramas:**  
   - Crea una rama específica para cada tarea, por ejemplo:  
     ```bash
     git checkout -b tarea-html-intro
     ```
   - Esto permite trabajar en paralelo sin afectar la rama principal.

4. **Desarrollo y Commits:**  
   - Realiza los cambios en el proyecto (por ejemplo, editar `index.html` o agregar archivos en `assets/css`).
   - Guarda los cambios con commits claros y descriptivos:
     ```bash
     git add .
     git commit -m "Agrega estructura básica en index.html y carpetas de assets"
     ```

5. **Push y Pull Request:**  
   - Envía tus cambios a GitHub:
     ```bash
     git push origin tarea-html-intro
     ```
   - Crea un pull request en GitHub para que tus cambios sean revisados y fusionados en la rama principal.

6. **Revisión y Merge:**  
   - Participa en la revisión de los pull requests de tus compañeros y aporta sugerencias.
   - Una vez aprobados, se fusionarán los cambios en la rama principal.

## Configuración del Entorno en Visual Studio Code

Aunque trabajamos principalmente en GitHub Codespaces, se recomienda configurar VS Code con algunas extensiones para mejorar la experiencia:

- **Live Server:** Permite ver en tiempo real los cambios en el navegador mientras editas HTML y CSS.
- **Material Icon Theme:** Proporciona iconos modernos para una mejor visualización de la estructura del proyecto.

## Conclusión

Este proyecto es una oportunidad para aprender los fundamentos del desarrollo web y el uso de Git en un entorno colaborativo. Se espera que, a medida que avances en cada tarea, te familiarices con los conceptos esenciales y las buenas prácticas de desarrollo en equipo.

¡Bienvenidos al curso y a esta aventura en el mundo del Frontend y la colaboración con Git!



