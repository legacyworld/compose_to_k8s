FROM python:slim
USER root
RUN pip3 install flask
WORKDIR /src
ENV PORT=80
ENV PYTHONUNBUFFERED=1
ENTRYPOINT ["python", "-u", "server.py"]