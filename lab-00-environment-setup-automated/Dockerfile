FROM gcr.io/deeplearning-platform-release/tf-cpu.1-15:m39
RUN apt-get update -y && apt-get -y install kubectl
RUN pip install -U six==1.12 apache-beam==2.16 pyarrow==0.14.0 tfx-bsl==0.15.1 \
&& pip install -U tfx==0.15 \
&& pip install -U tensorboard \
&& pip install https://storage.googleapis.com/ml-pipeline/release/0.1.36/kfp.tar.gz
