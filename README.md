# Dashboard de Gestión de Citas Médicas

Laboratorio 13 de Business Intelligence and Big Data. Dataset sintético de 5000 citas médicas, generado con Python, Faker y NumPy, y visualizado con Streamlit, Pandas y Plotly.

## Archivos
- `app.py`: aplicación con gráficos de citas por especialidad, estado y mes.
- `citas_medicas.csv`: dataset sintético de 5000 registros.
- `requirements.txt`: dependencias para Streamlit Community Cloud.

## Ejecutar localmente

```bash
python -m pip install -r requirements.txt
python -m streamlit run app.py
```

Abre la dirección que muestre la terminal (habitualmente http://localhost:8501).

## Publicar
1. Subir los cuatro archivos a un repositorio público de GitHub llamado `dashboard-citas-medicas`.
2. En https://share.streamlit.io/, crear una app a partir de un repositorio existente.
3. Seleccionar tu propio repositorio, rama `main`, ruta principal `app.py` y elegir `Deploy`.
4. Copiar la URL asignada realmente por Streamlit, que termina en `.streamlit.app`.

**Nota:** el dataset es sintético y el proyecto no está publicado hasta completar la configuración en tu cuenta.
