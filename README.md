# Introducción a la Inteligencia Artificial Generativa

Este repositorio contiene los notebooks de Jupyter y los archivos de código de apoyo utilizados en el curso "Introducción a la Inteligencia Artificial Generativa" impartido para la Universidad Nacional de Colombia, por el centro de educación continua.

## Estructura del repositorio

```
.env                # Archivo de variables de entorno (NO INCLUIR EN GIT)
sample.env          # Archivo de ejemplo con las variables de entorno
.gitignore          # Archivo que excluye .env de git
README.md           # Este archivo

# Notebooks y scripts organizados por módulo
notebooks/
├── modulo_1/
├── modulo_2/
├── modulo_3/
└── modulo_4/
```

## Ambiente virtual y dependencias

Crea un ambiente virtual para ejecutar el código:

```bash
# Crea un ambiente virtual
python -m venv .venv

# Activa el ambiente virtual
# En Windows:
.\.venv\Scripts\activate

# En macOS y Linux:
source .venv/bin/activate

# Instala las dependencias
pip install -r requirements.txt
```

## Variables de entorno

Para ejecutar el código se requiere una API Key de Google AI Studio o Groq.

1. **Localiza el archivo `sample.env` en la raíz del repositorio**

2. **Copia el contenido del archivo `sample.env` al archivo `.env`**

3. **Agrega tu API Key en el archivo `.env`**:

   ```ini
   GEMINI_API_KEY="your_gemini_api_key_here"
   GOOGLE_API_KEY="your_gemini_api_key_here"
   GROQ_API_KEY="your_groq_api_key_here"
   ```

3. **Obtén tu API Key de Google AI Studio en el siguiente enlace:** [Google AI Studio](https://aistudio.google.com/app/apikey)

4. **Obtén tu API Key de Groq en el siguiente enlace:** [Groq](https://console.groq.com/keys)