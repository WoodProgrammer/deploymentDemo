FROM python:latest
COPY api/. /api/.
WORKDIR /api/.
RUN pip3 install -r req.txt
EXPOSE 5000
ENTRYPOINT python3 api.py
