# Proyecto de Análisis del Arbolado Público – CABA

## Este repositorio contiene el código, los notebooks y los datos necesarios para ejecutar el análisis exploratorio y estadístico del arbolado lineal público de la Ciudad de Buenos Aires.
Pasos:

1. **Clonar el repositorio**
git clone https://github.com/LautaroBarraza/TP-Ciencia-De-Datos-Grupo14
cd nombre-del-repo

2. **Crear y activar un entorno virtual**
Linux / macOS
python3 -m venv .venv
source .venv/bin/activate

Windows (PowerShell)
python -m venv .venv
.venv\Scripts\activate

3. **Instalar dependencias**

**El repositorio incluye un archivo requirements.txt con todas las dependencias necesarias para ejecutar los notebooks.**

pip install --upgrade pip
pip install -r requirements.txt

4. Estructura del proyecto
├── data/                # Archivos de datos utilizados por los notebooks
├── notebooks/           # Notebooks de análisis
├── src/                 # Código fuente utilitario (si corresponde)
├── requirements.txt
└── README.md


**Los datos deben ubicarse en la carpeta data/. Por defecto, los notebooks asumen esa ruta.**

5. **Ejecutar el notebook**

Una vez instalado el entorno y las dependencias:

jupyter notebook

Luego abrir el archivo ubicado en:

notebooks/analisis_arbolado.ipynb


o el notebook correspondiente al análisis.

En caso de tener visual estudio code podras ejecturarlas ahi mismo.

6. **Notas adicionales**

Verificá que el kernel de Jupyter esté asociado al entorno virtual creado. Para instalarlo:

python -m ipykernel install --user --name arbolado-env --display-name "Arbolado Env"


Luego seleccionarlo en Jupyter Notebook.
