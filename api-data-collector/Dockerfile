FROM python:3.12-slim
RUN apt-get update && apt-get install -y make curl vim

WORKDIR /

COPY pyproject.toml .
RUN poetry install

CMD [ "bin/bash" ]
