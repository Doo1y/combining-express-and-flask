FROM python:3.9-slim

WORKDIR /app

EXPOSE 5000

COPY ./requirements.txt .

COPY ./entrypoint.sh .

RUN chmod +x /app/entrypoint.sh

ENTRYPOINT ["/app/entrypoint.sh"]