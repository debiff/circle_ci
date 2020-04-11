FROM python:3.7-slim-buster
COPY ./circle_ci /app
WORKDIR /app
EXPOSE 8000
CMD [ "python", "-m", "http.server" ]
