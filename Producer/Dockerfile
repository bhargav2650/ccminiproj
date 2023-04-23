FROM python:latest
WORKDIR /app
COPY rope.py .
copy requirements.txt .
Workdir /app/templates
copy templates/create.html .
workdir /app
# RUN pip install --no-cache-dir -r requirements.txt
# RUN apt update
# ENV MY_NETWORK_IP=172.18.0.2
# RUN pip3 install flask
# RUN pip3 install pika
# RUN pip3 install uuid
RUN pip3 install --no-cache-dir -r requirements.txt
EXPOSE 5000
# RUN pip install json
# RUN python3 rope.py
CMD ["python", "rope.py"]