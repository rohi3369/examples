FROM python:3.14.0rc3

WORKDIR /src
COPY . .
RUN pip install -r requirements.txt --no-cache-dir

CMD ["./server.py"]
