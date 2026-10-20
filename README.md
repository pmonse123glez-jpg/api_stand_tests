# Pruebas Automatizadas de la API - Urban Grocers

Este proyecto contiene un conjunto de pruebas automatizadas con **pytest** para verificar la funcionalidad del endpoint de creación de usuarios en la API de Urban Grocers.

## 🛠️ Tecnologías utilizadas
* Python 3.14
* PyCharm
* Pytest
* Requests

## 🚀 Pruebas incluidas
* **Casos Positivos:** Verificación de nombres válidos (de 2 a 15 caracteres) esperando respuesta HTTP `201`.
* **Casos Negativos:** Verificación de nombres inválidos esperando respuesta HTTP `400` y mensajes de error específicos.

## 📋 Instrucciones de ejecución
1. Asegúrate de tener activo el entorno virtual `.venv`.
2. Ejecuta el comando de pruebas en la terminal:
   ```bash
   pytest create_user_test.py
   
<!-- cambio de prueba -->