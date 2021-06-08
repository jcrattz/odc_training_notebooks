ARG BASE_IMG
FROM ${BASE_IMG}
# FROM jcrattzama/cube-in-a-box:odc1.8.3

WORKDIR ${ROOT_DIR}

COPY notebooks notebooks
COPY docs docs
COPY README.ipynb README.ipynb

USER root
RUN chown -R jovyan ${ROOT_DIR}
USER jovyan
