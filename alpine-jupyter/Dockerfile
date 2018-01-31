# Created date: 2018-01-31
# Updated date: 2018-01-31
FROM alpine:3.7
RUN ["apk", "update"]
RUN ["apk", "add", "python3", "python2", "py2-pip"]
RUN ["apk", "add", "gcc", "g++", "musl-dev", "python3-dev", "python2-dev"]
RUN ["python3", "-m", "pip", "install", "jupyter"]
RUN ["python", "-m", "pip", "install", "jupyter"]
RUN ["ipython3", "kernel", "install"]
LABEL version="0.0.1" maintainer="Daye Lee<tosony@163.com>"
WORKDIR /root/
ENTRYPOINT ["jupyter", "notebook", "--no-browser", "--ip=0.0.0.0", "--allow-root"]
CMD ["--NotebookApp.password='sha1:bb9ea858e58e:0c502a42c7e476af2eff7fb60c7273f1ce09acdb'"]
EXPOSE 8888
