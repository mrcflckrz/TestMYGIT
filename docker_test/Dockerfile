FROM python:3.9-alpine3.15
WORKDIR /usr/src/app
COPY requirements.txt ./
RUN pip install --no-cache-dir -r requirements.txt
COPY test_my_docker.py /usr/src/app
CMD [ "python", "test_my_docker.py" ]