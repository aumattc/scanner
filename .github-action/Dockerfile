FROM python:3.11-slim

WORKDIR /action

COPY requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt

COPY scanner.py /action/scanner.py

ENTRYPOINT ["python", "/action/scanner.py"]