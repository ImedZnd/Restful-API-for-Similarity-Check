FROM python:3
WORKDIR /usr/src/app
COPY requirement.txt ./
RUN pip install --no-cache-dir -r requirement.txt
COPY . .
RUN pip install ./en_core_web_sm-2.3.1.tar.gz
CMD ["python","app.py"]
