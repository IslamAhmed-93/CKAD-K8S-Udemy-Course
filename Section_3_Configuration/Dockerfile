FROM ubuntu

RUN apt-get update
RUN apt-get install python

RUN pip install flask
RUN pip install flask-mysql

COPY . /opt/source-code

ENTRYPOINT FLASK_APP=/opt/source-code/app.py flask run
-------

# docker build Dockerfile -t islamahmed94/my-custom-app
# docker push islamahmed94/my-custom-app
