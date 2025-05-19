FROM python:3.12-slim

RUN pip install "arkitekt-next[all]>=0.12.1"
RUN pip install "reaktion-next>=0.3.1"

RUN mkdir /app
WORKDIR /app
COPY .arkitekt_next /app/.arkitekt_next
COPY app.py /app/app.py
