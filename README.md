# Configuración de Entorno - Gemini API

Guía rápida para configurar el entorno de desarrollo.
---

## 1. Configuración Inicial
1. Crear carpeta `gemini-api` en `C:\`.
2. Abrir la carpeta en **VS Code**.
3. Abrir terminal: `Ctrl + ñ`.

## 2. Entorno Virtual (VENV)

Ejecuta el comando según tu sistema para aislar las librerías:

* **Windows:**
    ```bash
    python -m venv venv
    .\venv\Scripts\Activate
    ```
* **macOS / Linux:**
    ```bash
    python3 -m venv venv
    source venv/bin/activate
    ```

> **Nota:** En VS Code, usa `Ctrl + Shift + P` > `Python: Select Interpreter` y elige el que está dentro de la carpeta `venv`.

## 3. Instalación de Dependencias
Con el entorno activo, instala `requests`:
```bash
pip install requests