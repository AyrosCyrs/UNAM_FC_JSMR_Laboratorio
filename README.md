# Laboratorio de Inteligencia Artificial 🤖

[![Python Version](https://img.shields.io/badge/python-3.8%2B-blue)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 📖 Descripción
Prácticas del laboratorio de Inteligencia Artificial (Facultad de Ciencias, UNAM). Incluye un módulo de regresión lineal simple y estimaciones masivas, con código limpio, manejo de excepciones y logging, además de los notebooks de Colab de cada práctica.

## 🚀 Características
- **Cálculo de regresión:** intercepto ($a$) y pendiente ($b$) mediante mínimos cuadrados.
- **Validación automática:** manejo de errores para dimensiones incompatibles o varianza cero.
- **Logging integrado:** registro de eventos para auditoría de modelos.
- **Type hinting:** código tipado para una mejor experiencia de desarrollo.

## 📁 Estructura del proyecto
```text
UNAM_FC_JSMR_Laboratorio/
├── app_Streamlit/        # App visual (dashboard)
├── notebooks/            # Notebooks de las prácticas (Colab)
├── src/unam_fc_ai/       # Modelos (models/) y utilidades (utils/)
├── tests/                # Pruebas del modelo
├── requirements.txt      # Dependencias de PROD
├── requirements-stage.txt
├── requirements-dev.txt
└── setup.py
```

## 🛠️ Instalación (Windows)
```bash
git clone https://github.com/AyrosCyrs/UNAM_FC_JSMR_Laboratorio.git
cd UNAM_FC_JSMR_Laboratorio
python -m venv venv-dev
venv-dev\Scripts\activate
pip install -r requirements-dev.txt
```

## 🧪 Entornos
| Entorno | Archivo de dependencias | Para qué sirve |
|---|---|---|
| DEV | `requirements-dev.txt` | Desarrollo y experimentación (incluye pytest, black, flake8, jupyter) |
| STAGE | `requirements-stage.txt` | Validación previa a producción |
| PROD | `requirements.txt` | Solo lo esencial para ejecutar |

## ▶️ Uso
```bash
pytest                                  # correr las pruebas
streamlit run app_Streamlit/Home.py     # abrir el dashboard
```

## ⚖️ Licencia
Este proyecto está bajo la Licencia MIT. Consulta el archivo [LICENSE](LICENSE) para más detalles.

## ✍️ Autora
Claudia Yarinet Osorio López, Facultad de Ciencias, UNAM.