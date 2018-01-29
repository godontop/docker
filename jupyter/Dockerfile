# Created Date: 2018-01-22
# Updated Date: 2018-01-29
FROM debian
LABEL version="0.0.2" maintainer="Daye Yee<tosony@163.com>"
RUN ["apt-get", "update"]
RUN ["apt-get", "install", "python", "python-pip", "python3", "python3-pip", "-y"]
RUN ["python", "-m", "pip", "install", "--upgrade", "pip"]
RUN ["python", "-m", "pip", "install", "jupyter"]
RUN ["python3", "-m", "pip", "install", "--upgrade", "pip"]
RUN ["python3", "-m", "pip", "install", "jupyter"]
WORKDIR /root/
EXPOSE 8888
