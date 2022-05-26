FROM python:3


WORKDIR /usr/src/app
COPY requirements.txt ./
RUN pip install --no-cache-dir -r requirements
COPY test_my_git.py ./usr/src/app

CMD [ "python", "./test_my_git.py" ]