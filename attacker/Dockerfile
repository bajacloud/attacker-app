FROM python:3.9
WORKDIR /app
COPY . /app
RUN pip install -r requirements.txt
COPY exploit.py /app
RUN chmod +x /app/exploit.py