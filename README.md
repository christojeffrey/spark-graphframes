- tambahin ini di bashrc
  export PYSPARK_DRIVER_PYTHON=jupyter
  export PYSPARK_DRIVER_PYTHON_OPTS='notebook --allow-root'

- restart source
- jalanin pake ini
  pyspark --packages graphframes:graphframes:0.8.2-spark3.2-s_2.12
