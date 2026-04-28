FROM python:3.10-alpine
WORKDIR /app
COPY requirements.txt .
RUN pip install -r requirements.txt
COPY application.py .
COPY index.html .
EXPOSE 8000
CMD ["python", "application.py"]
