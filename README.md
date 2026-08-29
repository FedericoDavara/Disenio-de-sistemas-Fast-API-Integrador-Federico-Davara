# FastAPI Backend - Diseño de Sistemas

Este proyecto contiene el backend desarrollado con FastAPI. Sigue los pasos a continuación para configurar tu entorno local y ejecutar la aplicación.

## Requisitos Previos

Asegúrate de tener instalado Python 3.10 o superior en tu sistema.

## Configuración del Proyecto

### 1. Clonar el repositorio

### 2. Crear el entorno virtual
Crea un entorno virtual aislado llamado `.venv` dentro de la carpeta raíz del proyecto:

* **En Linux / macOS:**
  ```bash
  python3 -m venv .venv
  ```
* **En Windows:**
  ```bash
  python -m venv .venv
  ```

### 3. Activar el entorno virtual
Antes de instalar dependencias o ejecutar el código, debes activar el entorno:

* **En Linux / macOS:**
  ```bash
  source .venv/bin/activate
  ```
* **En Windows (PowerShell):**
  ```powershell
  .venv\Scripts\Activate.ps1
  ```
* **En Windows (CMD):**
  ```cmd
  .venv\Scripts\activate.bat
  ```

### 4. Instalar las dependencias
Una vez activado el entorno, instala los paquetes necesarios:

```bash
pip install -r requirements.txt
```

---

## Ejecución de la Aplicación

Para iniciar el servidor ingresar hasta la carpete que contiene el archivo main en la consola y ejecutar el programa principal (`main`), asegúrate de tener el entorno virtual activo y ejecuta el siguiente comando:

```bash
python -m fastapi dev main.py
```


El servidor se iniciará en [http://127.0.0.1:8000](http://127.0.0.1:8000). Puedes acceder a la documentación interactiva de la API en `/docs`.
