FROM python:3

ENV PYTHONDONTWRITEBYTECODE=1
ENV PYTHONUNBUFFERED=1

WORKDIR /code
COPY Services/Catalog/requirements.txt requirements.txt
RUN pip install -r requirements.txt
COPY Services/Catalog/ /code/