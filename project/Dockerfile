FROM python:3.7.16-slim-buster
RUN apt update \
  && apt install libpq-dev gcc -y \
  && pip install Flask Psycopg2 ConfigParser
ENTRYPOINT /srv/app/web.py
