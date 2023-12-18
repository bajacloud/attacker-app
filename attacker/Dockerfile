FROM python:3.9
WORKDIR /app
COPY . /app
RUN pip install -r requirements.txt
RUN apt-get update && apt-get install -y nmap
COPY exploit.py /app
RUN chmod +x /app/exploit.py
CMD ["sleep", "infinity"]