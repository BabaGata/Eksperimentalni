FROM python:3.10

WORKDIR /eksperimentalni/Producer

COPY producer.py .
COPY requirements.txt .

RUN pip install -r requirements.txt

CMD ["python3","producer.py"]