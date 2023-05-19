FROM python:3.7-slim
RUN mkdir -p /app
WORKDIR /app
COPY . /app/
RUN pip install -r /app/requirements.txt
RUN chmod -x app.py
EXPOSE 5000
CMD ["python","app.py"]
