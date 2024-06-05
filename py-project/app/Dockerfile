FROM python:3.8

WORKDIR /app
COPY requirments.txt /app/requirments.txt

RUN pip install --no-cache-dir --upgrade -r /app/requirments.txt

COPY . /app

CMD bash -c "while true; do sleep 1; done"