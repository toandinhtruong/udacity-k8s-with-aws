FROM python:3.10-slim-buster

# create and change dir
WORKDIR /src

# copy source code of the application
COPY * ./

# install all dependencies
RUN pip install --upgrade pip && \
    pip install -r requirements.txt
#ENV APP_PORT=5153
#ENV DB_USERNAME=myuser
#ENV DB_PASSWORD=mypassword
#ENV DB_HOST=127.0.0.1
#ENV DB_PORT=5433
#ENV DB_NAME=mydatabase
ENTRYPOINT [ "python", "app.py" ]