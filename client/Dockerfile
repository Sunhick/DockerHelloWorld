FROM python:3.7-slim

WORKDIR /app

COPY . /app

RUN pip3 install --trusted-host pypi.python.org -r requirements.txt

EXPOSE 9000

# Run app.py when the container launches
CMD ["python3", "main.py"]
