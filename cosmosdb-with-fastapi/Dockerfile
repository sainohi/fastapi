FROM python:3.8-alpine
COPY . /app
WORKDIR /app
RUN /usr/local/bin/python -m pip install --upgrade pip
RUN pip install -r requirements.txt
EXPOSE 8000
CMD ["uvicorn","main:app", "--reload"]
