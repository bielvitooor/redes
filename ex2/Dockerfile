FROM ubuntu:latest
RUN apt update
RUN apt install python3 -y
COPY ./hello.py .
RUN chmod +x hello.py
CMD ["python3","hello.py"]

