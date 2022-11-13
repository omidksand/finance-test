FROM continuumio/miniconda3:4.10.3p1
RUN conda install \
   xarray \ 
   netCDF4 \ 
   bottleneck \
   numpy \
   pandas \
   matplotlib \
   jupyterlab

RUN conda install -c conda-forge ipympl ipywidgets lxml ta-lib

CMD ["jupyter-lab","--ip=0.0.0.0","--port=8888","--no-browser","--notebook-dir=/opt/app/data","--allow-root"]