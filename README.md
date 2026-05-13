# Kebab Simulator


<p align="left">
  <img src="https://skillicons.dev/icons?i=unity,cs" alt="Unity y C#" />
</p>
<p align="left">
  <img src="https://img.shields.io/badge/Autodesk_3ds_Max-00A8E1?style=for-the-badge&logo=autodesk&logoColor=white" alt="3ds Max" />
  <img src="https://img.shields.io/badge/Adobe_Audition-9999FF?style=for-the-badge&logo=adobe-audition&logoColor=white" alt="Adobe Audition" />
</p>
  <img src="https://img.shields.io/badge/Estado-Completado-success?style=for-the-badge" alt="Estado" />

<p align="center">
  <img src="[URL_DE_TU_IMAGEN_O_GIF]" alt="Gameplay de Kebab Simulator" width="600"/>
</p>

## 📝 Sobre el Proyecto

**Kebab Simulator** es un videojuego de gestión de un local de comida desarrollado como proyecto para la asignatura de Aplicaciones Multimedia Interactivas del Grado en Tecnologías Interactivas de la Universitat Politècnica de València (UPV). En este título, el jugador asume el rol del dueño de un restaurante de kebabs. El objetivo principal es gestionar los pedidos rápidamente, mantener la felicidad de los clientes y utilizar los beneficios obtenidos para reabastecer ingredientes o adquirir mejoras para el local, con la meta de convertirse en el mejor kebab del mundo.


## ✨ Funcionalidades Principales

* **Ciclo de Gestión:** El jugador atiende a los clientes durante el día bajo presión de tiempo y, al finalizar la jornada, accede a una pantalla de resumen para gestionar las ganancias, reponer ingredientes en el almacén y comprar mejoras, como nuevas mesas.
* **Sistema de Reputación y Progresión:** El local cuenta con una barra de reputación (nivel) que sube al entregar pedidos precisos y rápidos, y baja si se cometen errores graves (como dar carne a un vegetariano) o si el tiempo de espera expira. Si la reputación cae a cero estando en el nivel 1, se pierde la partida.
* **Inteligencia y Estados de NPCs:** Los clientes cuentan con medidores de paciencia y estados emocionales (Feliz, Impaciente, Enfado). Se dividen en tres tipos con lógicas de validación de pedidos distintas:
    * **Carnívoros:** Sus pedidos exigen carne (pollo en jaula o ternera) y rechazan verduras.
    * **Vegetarianos:** Solo aceptan ingredientes vegetales (lechuga, tomate, cebolla blanca).
    * **Omnívoros:** Pueden pedir cualquier combinación de ingredientes de las estaciones.

## 🛠️ Stack Tecnológico

* **Motor de Videojuego:** Unity.
* **Scripting:** C#.
* **Modelado 3D:** Autodesk 3ds Max.
* **Edición de Sonido y Música:** Adobe Audition (incluye música de tienda, resúmenes diarios y efectos ambientales del local).

## ⚙️ Metodología y Arquitectura

El proyecto fue desarrollado por el equipo **9Studios**, compuesto por un grupo de seis integrantes. Se gestionó empleando la metodología ágil **SCRUM**, organizando el trabajo a lo largo de todo el cuatrimestre para integrar iterativamente el diseño de mecánicas, el modelado 3D, la programación orientada a objetos en C# y los apartados sonoros.

## 🚀 Instalación y Despliegue

1. Clona el repositorio en tu máquina local:
   ```bash
   git clone [URL_DE_TU_REPOSITORIO]
Abre el proyecto utilizando Unity Hub.

Asegúrate de abrirlo con la versión correspondiente de Unity utilizada en el desarrollo.

Navega hasta la escena principal (habitualmente en la carpeta Assets/Scenes), ábrela y presiona el botón de Play en el editor.
