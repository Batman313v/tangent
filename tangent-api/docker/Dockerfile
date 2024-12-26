FROM Python:3.10

WORKDIR /app

COPY ./tangent-api/requirements.txt .

RUN pip install --no-cache-dir -r requirements.txt

COPY ./tangent-api/src/ .

CMD ["python", "./app.py"]
