FROM python:3.8.3-buster

COPY * /app/
RUN ls -la /app/

# UPGRADE pip3
RUN pip3 install --upgrade pip
RUN pip install --upgrade -r /app/requirements.txt

WORKDIR /app/

CMD ["python", "app.py", "8080"]
