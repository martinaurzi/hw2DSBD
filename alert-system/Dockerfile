FROM python:3.11-slim

LABEL authors="drusso"

WORKDIR /app

ARG BUILD_DIR
COPY ${BUILD_DIR}/. .

RUN pip install --no-cache-dir confluent-kafka

CMD ["python", "app.py"]

