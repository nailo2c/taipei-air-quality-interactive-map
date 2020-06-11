FROM jupyter/datascience-notebook

RUN pip install --upgrade pip \
    && pip install datapackage \
    && pip install folium \
    && pip install --upgrade seaborn \
    && pip install geopandas

# jovyan - an inhabitant of Jupyter
WORKDIR '/home/jovyan/work/bokeh-app/'