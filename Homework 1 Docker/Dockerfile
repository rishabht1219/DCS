FROM python:3

WORKDIR /HW1

COPY . .

RUN pip install --no-cache-dir -r requirements.txt

EXPOSE 5500

CMD ["python", "./flask_app.py"]
