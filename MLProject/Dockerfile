FROM python:3.10

WORKDIR /app

COPY . /app

RUN pip install mlflow pandas scikit-learn

CMD ["python", "modelling.py"]