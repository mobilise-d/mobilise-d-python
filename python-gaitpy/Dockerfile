FROM continuumio/miniconda3:4.6.14

COPY requirements.txt /tmp/requirements.txt
RUN conda install numpy==1.13.3
RUN pip install -r /tmp/requirements.txt --upgrade
