FROM python:alpine
COPY . /server
WORKDIR /server
RUN pip install -r requirements.txt
EXPOSE 5001
ENTRYPOINT [ "python" ]
CMD [ "server.py" ]
