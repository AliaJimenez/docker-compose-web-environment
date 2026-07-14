# Dockerized Web Environment with Docker Compose 🐳

Este repositorio contiene el desarrollo de la **Práctica 6** de la materia **Electiva II: DevOps**. El objetivo principal de este laboratorio es implementar la **contenedorización** de aplicaciones para aislar el entorno de ejecución, asegurando el principio fundamental de DevOps: *"si funciona en mi máquina, funciona en cualquier entorno"*.

El proyecto utiliza **Docker Compose** para definir, configurar y levantar la infraestructura del contenedor web de forma local con un solo comando.

---

## 🛠️ Conceptos de DevOps Implementados

*   **Contenedorización (Containerization):** Empaquetado de la aplicación junto a sus variables y dependencias en una unidad aislada y portable.
*   **Orquestación Local Simplificada:** Uso de configuraciones declarativas para gestionar el ciclo de vida, los volúmenes, los puertos y el comportamiento del contenedor.
*   **Infraestructura como Código (IaC) Básica:** Definición de los requerimientos del entorno mediante un archivo de configuración versionable (`docker-compose.yml`).

---

## 📁 Estructura del Repositorio

*   **`src/index.html`**: El código fuente del sitio web o aplicación estática que sirve como artefacto principal para ser renderizado por el servidor web dentro del contenedor.
*   **`docker-compose.yml`**: Archivo de configuración que define los servicios, imágenes base (como Nginx o Apache), asignación de puertos (ej. redirección al puerto local) y el montaje de volúmenes para enlazar el directorio `src/` en tiempo real.

---

## 🧰 Tecnologías y Herramientas Utilizadas

*   **Tecnología de Contenedores:** Docker
*   **Herramienta de Orquestación:** Docker Compose
*   **Lenguajes:** HTML5 / YAML (para la estructura de orquestación)

---

## 🚀 Instrucciones de Ejecución

### Requisitos Previos:
Asegúrate de tener instalado **Docker** y **Docker Compose** en tu sistema operativo local.

### Levantar el Entorno Contenedorizado:
1. Clona este repositorio:
   ```bash
   git clone https://github.com/AliaJimenez/docker-compose-web-environment 
