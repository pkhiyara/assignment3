FROM python:2

RUN pip install --upgrade pip
RUN pip install tweepy
RUN pip install --upgrade google-api-python-client
RUN pip install --upgrade oauth2client
RUN pip install python-dateutil

ADD a3.py /a3.py
ADD utils.py /utils.py

CMD python a3.py