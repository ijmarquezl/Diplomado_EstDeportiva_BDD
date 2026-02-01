# Diplomado Estadística Deportiva

Este repositorio contiene los cuadernos Jupyter para el Diplomado en Estadística Deportiva.

## 🚀 Cómo abrir en Google Colab

Para abrir estos cuadernos directamente en Google Colab:

1.  Instala la extensión de Chrome **[Open in Colab](https://chrome.google.com/webstore/detail/open-in-colab/iogfkhleblhcpcekbiedikdehleodpjo)** (Opcional pero recomendado).
2.  O cambia manualmente la URL del archivo en GitHub:
    *   Cambia `github.com` por `colab.research.google.com/github`.
    *   Ejemplo: `https://github.com/tu_usuario/Diplomado_EstDeportiva_BDD/blob/main/clase1.ipynb` -> `https://colab.research.google.com/github/tu_usuario/Diplomado_EstDeportiva_BDD/blob/main/clase1.ipynb`.

## 🔑 Configuración de Kaggle

Para descargar los datasets necesarios en los cuadernos, necesitarás una cuenta de Kaggle y configurar tu API Key.

### 1. Crear cuenta
Si no tienes una, regístrate en [kaggle.com](https://www.kaggle.com/).

### 2. Generar "Legacy API Key"
Esta es la forma más sencilla de obtener el archivo de configuración:

1.  Ve a la configuración de tu cuenta: Haz clic en tu foto de perfil (arriba a la derecha) -> **Settings**.
2.  Desplázate hacia abajo hasta la sección **API**.
3.  Si ya tienes un token antiguo y no lo recuerdas, haz clic en **"Expire Legacy API Key"**.
4.  Haz clic en el botón **"Create Legacy API Key"**.
5.  Esto descargará automáticamente un archivo llamado `kaggle.json`.

### 3. Usar en Colab
Cuando ejecutes los cuadernos en Colab, usualmente se te pedirá subir este archivo `kaggle.json` para autenticarte y descargar los datos.

> **⚠️ IMPORTANTE:** Nunca compartas tu archivo `kaggle.json` ni lo subas a repositorios públicos. Contiene tus credenciales privadas.
