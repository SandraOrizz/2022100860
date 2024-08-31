FROM python:3.9

WORKDIR /app

COPY requirements.txt .
RUN pip install --no-cache-did -r requirements.txt

COPY . .

CMD [ "python", "main.py" ]