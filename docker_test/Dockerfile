FROM python:3


WORKDIR /usr/src/app
COPY requirements.txt ./
RUN pip install --no-cache-dir -r requirements
COPY . /usr/src/app

CMD [ "python", "./test_my_git.py" ]