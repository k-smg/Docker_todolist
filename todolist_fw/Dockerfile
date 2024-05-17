FROM python:3.12.3

ENV PYTHONUMBUFFERED 1
ENV PYTHONDONTWRITEBYTECODE 1

WORKDIR /todolist_fw

COPY requirements.txt /todolist_fw/

RUN pip install --no-cache-dir -r requirements.txt

COPY . /todolist_fw/

CMD ["python","manage.py","runserver","0.0.0.0:8000"]

