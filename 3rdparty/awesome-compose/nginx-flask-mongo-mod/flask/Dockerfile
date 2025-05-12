FROM python:3.12.10

WORKDIR /src
COPY . .
RUN pip install -r requirements.txt --no-cache-dir

CMD ["./server.py"]
