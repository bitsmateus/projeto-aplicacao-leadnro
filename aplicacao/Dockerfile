FROM python:3.12-slim
WORKDIR /app
COPY app/requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt
COPY app/todo_project/ .
EXPOSE 8080
CMD ["python", "run.py"]
