FROM python:3.12-slim-bookworm
COPY ./requirements.txt /app/requirements.txt
WORKDIR /app
RUN pip install -r requirements.txt
#RUN apt-get update && apt-get install -y git
COPY . /app
EXPOSE 5000
CMD ["python", "app.py" ]