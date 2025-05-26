# 📊 Análisis de Compras Recurrentes Mer Analytics

Este proyecto permite analizar compras recurrentes utilizando Python y Jupyter Notebooks. Incluye herramientas de análisis de datos, visualización y machine learning.

## 🚀 Inicio rápido

1. **Clona el repositorio:**
   ```sh
   git clone https://github.com/Tatiana12o6/okuo-compras-recurrentesmer-analytics
   cd okuo-custoanalisis-compras-recurrentesmer-analytics
   ```

2. **Crea y activa un entorno virtual:**
   ```sh
   python3 -m venv .venv
   source .venv/bin/activate
   ```

3. **Instala las dependencias:**
   ```sh
   pip install --upgrade pip
   pip install -r requirements.txt
   ```

4. **Inicia JupyterLab o Jupyter Notebook:**
   ```sh
   jupyter lab
   # o
   jupyter notebook
   ```

## 📁 Estructura del proyecto

- `requirements.txt`: Dependencias del proyecto.
- `.gitignore`: Archivos y carpetas ignorados por git.
- `notebooks/`: Notebooks de análisis y experimentos.
- `src/`: Código fuente principal.

## 🐍 Requisitos

- Python 3.12.1 o superior
- Pip 25.1.1

## 🔑 Variables de entorno

Para acceder a los datos en S3 necesitas definir tus credenciales de AWS en un archivo `.env` en la raíz del proyecto. Crea el archivo `.env` con el siguiente contenido:

```
ACCESS_KEY=tu_access_key
SECRET_KEY=tu_secret_key
```

Asegúrate de no compartir este archivo ni subirlo al repositorio.

## ⚡ Descarga automática de datos

El notebook [`notebooks/okuo-assest.ipynb`](notebooks/okuo-assest.ipynb) descarga automáticamente los datos desde S3 usando las variables de entorno configuradas. Antes de ejecutar el notebook, verifica que el archivo `.env` esté correctamente configurado y que las dependencias estén instaladas.
