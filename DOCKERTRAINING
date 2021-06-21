FROM python:3.5-slim
COPY . /MLOps
WORKDIR /MLOps
RUN pip install --upgrade pip
RUN pip install -r requirements.txt
CMD [ "python", "./model.py" ]
