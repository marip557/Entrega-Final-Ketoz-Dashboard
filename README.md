# 📦 Ketoz Logística - Ecosistema Integral & Business Intelligence

Este repositorio contiene la entrega final para la **Clase 12: Dashboard (Proyecto Final)**. Representa el ecosistema tecnológico End-to-End para la gestión, clasificación y análisis de envíos B2B de repuestos de motocicletas.

## 🏗️ Arquitectura del Proyecto
El sistema está dividido en cuatro capas funcionales:

1. **Frontend (`app_envios.py`):** Interfaz gráfica en Tkinter con procesamiento de imágenes (Pillow) y validación estricta de reglas de negocio.
2. **Backend (`logistica.py` & `database.py`):** Lógica orientada a objetos para el cálculo de fletes y categorización de carga.
3. **Base de Datos (`ketoz_logistica.db`):** Motor SQLite que garantiza la persistencia segura de los manifiestos generados.
4. **Inteligencia de Negocios (`Ketoz_MVP_Final.pbix`):** Dashboard en Power BI construido bajo un **Modelo Estrella**, con integración de una Tabla Calendario y medidas DAX avanzadas (Inteligencia de Tiempo, CALCULATE, DIVIDE) para responder a preguntas clave del negocio.

## 👥 Integrantes del Grupo
* **Matías Mondragón** (Líder de Proyecto)
* **Arianne Amorocho**
* **Mariana Peña**

## 🚀 Instrucciones de Ejecución (Python)
1. Instalar dependencias necesarias: `pip install Pillow`
2. Ejecutar el orquestador principal: `python main.py`
