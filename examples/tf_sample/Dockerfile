FROM gcr.io/tensorflow/tensorflow:1.3.0-rc2
RUN mkdir -p /opt/mlkube
COPY tf_sample/tf_smoke.py /opt/mlkube/
ENTRYPOINT ["python", "/opt/mlkube/tf_smoke.py"]
