FROM continuumio/anaconda3:latest

RUN mkdir /notebooks 

COPY jupyter_notebook_config.py /root/.jupyter/jupyter_notebook_config.py

CMD ["/opt/conda/bin/jupyter", "notebook",      \ 
     "--notebook-dir=/notebooks",               \
     "--port=8888", "--ip='*'", "--allow-root",   \
    "--NotebookApp.token=''", "--NotebookApp.password=''" ]

