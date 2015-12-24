FROM uetchy/tensorflow:0.6.0

RUN mkdir /app
WORKDIR /app

ONBUILD COPY requirements.txt /app
ONBUILD RUN pip install --no-cache-dir -r requirements.txt

ONBUILD COPY . /app
