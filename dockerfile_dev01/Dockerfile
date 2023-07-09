# This Dockerfile creates an image based on pyspark-notebook to include mysqlclient, plotly, and natural language toolkit
# To create image, input the following in a terminal pointing to this directory:
# docker build -t dev:01 .
FROM jupyter/pyspark-notebook:2023-06-26

RUN conda install -y -c conda-forge mysqlclient
RUN conda install -y -c plotly plotly
RUN conda install -y -c anaconda nltk