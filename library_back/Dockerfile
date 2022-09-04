FROM python:3
ENV PYTHONDONTWHITEVYTECODE=1
ENV PYTHONNUNBUFFERED=1
WORKDIR /library_back
COPY requirements.txt /library_back
RUN pip install -r requirements.txt
COPY . /library_back