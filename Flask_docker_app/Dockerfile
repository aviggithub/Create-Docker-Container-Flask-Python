FROM python:3.8
RUN mkdir /app
WORKDIR /app
ADD requirements.txt /app
ADD app_main.py /app
RUN pip3 install -r requirements.txt
CMD python3 app_main.py