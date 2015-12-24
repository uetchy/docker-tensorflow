FROM python:3.5.1

RUN  apt-get update \
  && apt-get install -y libblas3 liblapack3 libgfortran3 gfortran

RUN pip install numpy scipy

RUN pip install https://storage.googleapis.com/tensorflow/linux/cpu/tensorflow-0.6.0-cp34-none-linux_x86_64.whl
