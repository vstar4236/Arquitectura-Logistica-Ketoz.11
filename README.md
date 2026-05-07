# 📦 Ketoz Logística - MVP Frontend & Backend

Este repositorio contiene la arquitectura completa de la aplicación de escritorio para la gestión y clasificación de envíos B2B de la empresa familiar Ketoz, desarrollada para la Clase 11: Interfaces Gráficas, Eventos y Excepciones.

## 🏗️ Arquitectura del Proyecto
La aplicación sigue una estructura modular para garantizar la escalabilidad y el mantenimiento del software:

* **Frontend/ (`app_envios.py`):** Interfaz gráfica de usuario (GUI) desarrollada con `Tkinter`. Implementa procesamiento de imágenes con `Pillow` y un sistema de validación robusto con alertas interactivas mediante `messagebox`.
* **Backend/ (`logistica.py` & `database.py`):** Capa lógica que procesa las reglas de negocio (clasificación por peso y cálculo de costos) y gestiona la persistencia de datos.
* **Base de Datos (`ketoz_logistica.db`):** Motor `SQLite` encargado del almacenamiento seguro de los manifiestos de envío generados.
* **Orquestador (`main.py`):** Archivo raíz encargado de inicializar el sistema y conectar ambas capas.

## 👥 Integrantes del Grupo
* **Matías Mondragón**
* **Arianne Amorocho**
* **Mariana Peña**

## 🚀 Instrucciones de Instalación y Ejecución
1. **Requisitos previos:** Asegurarse de tener Python instalado.
2. **Instalar dependencias:** Ejecutar en la terminal el comando `pip install Pillow`.
3. **Ejecución:** Iniciar el sistema desde la raíz del proyecto con el comando `python main.py`.

## 🛠️ Tecnologías Utilizadas
* **Lenguaje:** Python 3.x
* **GUI:** Tkinter
* **Imágenes:** Pillow (PIL)
* **Persistencia:** SQLite3
* **Analítica:** Power BI

---
*Proyecto académico desarrollado para el Tercer Corte - Universidad de La Sabana (2026).*
