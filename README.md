# Descripción General

Arkanoid es un proyecto que recrea el clásico juego arcade, pero con mejoras y un enfoque en la jugabilidad y personalización de la experiencia. Este juego, desarrollado por el grupo 7, combina elementos de entretenimiento y desafío, con modos de juego que se adaptan a las habilidades del jugador. Se caracteriza por un diseño modular y el uso de bases de datos para registrar el progreso de los jugadores.

El objetivo principal del juego es evitar que una pelotita caiga al fondo de la pantalla mientras destruyes bloques en la parte superior. A lo largo de la partida, los jugadores pueden elegir entre diferentes niveles de dificultad y modos de juego, y su progreso se guarda automáticamente en la base de datos del sistema.

## Características Principales

- 🎮 *Modos de Juego*: Incluye modos de juego solitario y multijugador, permitiendo elegir entre diferentes niveles de dificultad.
- 📊 *Registro de Progreso*: Los jugadores ingresan su nombre al iniciar el juego, lo que permite registrar y almacenar su progreso.
- 🔧 *Base de Datos*: El juego se conecta a una base de datos MySQL que almacena usuarios, movimientos y votaciones realizadas durante la partida.
- 🖥️ *Interfaz Intuitiva*: Los controles del juego son simples y fáciles de usar, proporcionando una experiencia accesible para jugadores de diferentes niveles.

## Estructura del Proyecto

Arkanoid/
├── Arkanoid_BDG1_Version01/       # Primera versión del proyecto
├── Arkanoid_BDG1_Version02/       # Segunda versión del proyecto
├── Arkanoid_BDG1_Version03/       # Tercera versión del proyecto
├── Arkanoid_BDG1_Version04/       # Cuarta versión del proyecto
├── Arkanoid_BDG1_Version05/       # Quinta versión del proyecto
├── Arkanoid_BDG1_Version06/       # Sexta versión del proyecto
├── Arkanoid_BDG1_VersionFinal01/  # Primera versión final del proyecto
├── Arkanoid_BDG1_VersionFinal02/  # Segunda versión final del proyecto
├── Arkanoid_BDG1_VersionFinal03/  # Tercera versión final del proyecto
├── Arkanoid_BDG1_VersionFinal04/  # Cuarta versión final del proyecto
├── Imagenes/                      # Carpeta con imágenes del proyecto
├── README.md                      # Archivo de documentación inicial del proyecto
├── procedimientoAlmacenado.txt    # Procedimiento almacenado para la base de datos
├── requirements.txt               # Archivo con las dependencias necesarias
└── main.py                        # Código principal del juego Arkanoid

## Motivación y Contexto

El desarrollo de Arkanoid surgió de la necesidad de aplicar conceptos teóricos en un entorno práctico, específicamente en la creación de un sistema que integre gráficos, control de eventos y gestión de bases de datos. Este proyecto busca ofrecer una experiencia entretenida y personalizable, al mismo tiempo que emplea tecnologías actuales como pygame y MySQL para su implementación.

## Resultados Esperados

Con el proyecto Arkanoid, se espera:

- Crear una experiencia de juego inmersiva con una jugabilidad fluida y adaptable.
- Facilitar el registro del progreso de los jugadores mediante una base de datos.
- Proveer una herramienta entretenida para mejorar las habilidades de programación y diseño de juegos.

## Equipo Actual

| Miembro                           | Rol                | Función Principal                    | Correo                       |
|------------------------------------|--------------------|--------------------------------------|------------------------------|
| *Edwin Junior Jara Bocanegra*    | Desarrollo Técnico | Prototipado, implementación del juego y desarrollo técnico     | edwin.jara@upch.pe           |
| *Rodrigo Alonso Rodríguez Reategui*        | Desarrollo Técnico | Implementación del sistema de juego y desarrollo técnico  | jose.ames@upch.pe            |
| *Bryan Alexander Peñaloza Huamán*| Diseño y Base de Datos | Diseño de la base de datos, desarrollo técnico y modelo del juego | bryan.penaloza@upch.pe       |
| *José Manuel Ames Anapán*| Investigación     | Pruebas y validación del juego       | rodrigo.rodriguez@upch.pe    |
| *Victoria Beatriz Castro Pichihua*| Investigación      | Pruebas, implementación del sistema de juego y documentación              | victoria.castro@upch.pe      |

## Documentación y Recursos

El proyecto cuenta con una carpeta de documentación (docs/) donde se incluyen manuales de usuario, especificaciones del juego y detalles sobre el sistema de base de datos. También se proporcionan guías detalladas sobre la instalación del entorno y cómo ejecutar el juego.