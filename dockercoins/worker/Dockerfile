FROM python:3-alpine3.18
RUN pip install redis
RUN pip install requests
COPY worker.py /
CMD ["python", "worker.py"]
