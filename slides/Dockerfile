FROM alpine:3.18.4
RUN apk add --no-cache entr py3-pip git zip
COPY requirements.txt .
RUN pip3 install -r requirements.txt
