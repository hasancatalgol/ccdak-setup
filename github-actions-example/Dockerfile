FROM python:3.14-rc-slim-bookworm
  
COPY requirements.txt /tmp/requirements.txt
RUN pip3 install -U -r /tmp/requirements.txt

COPY src/*.py /usr/bin/.
COPY schemas/* /etc/.
