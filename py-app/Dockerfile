FROM python:3.8
WORKDIR /app
COPY . .
RUN if [ -f requirements.txt ]; then pip install -r requirements.txt; fi
CMD ["python", "app.py"]

