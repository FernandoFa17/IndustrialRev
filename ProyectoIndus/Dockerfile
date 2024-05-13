FROM python:3.12
LABEL authors="ferna"

WORKDIR /ProyectoIndus
COPY requirements.txt .
RUN pip install -r requirements.txt
COPY . .
CMD ["python", "-m", "flask", "run"]
