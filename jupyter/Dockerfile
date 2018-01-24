# Version: 0.0.1
# Created Date: 2018-01-22
# Updated Date: 2018-01-22
FROM debian
MAINTAINER Daye Lee 'tosony@163.com'
RUN ["apt-get", "update"]
RUN ["apt-get", "install", "python", "python-pip", "python3", "python3-pip", "-y"]
RUN ["python", "-m", "pip", "install", "--upgrade", "pip"]
RUN ["python", "-m", "pip", "install", "jupyter"]
RUN ["python3", "-m", "pip", "install", "--upgrade", "pip"]
RUN ["python3", "-m", "pip", "install", "jupyter"]
EXPOSE 8888
