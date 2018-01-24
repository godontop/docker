# 支持Python 2 和Python 3的jupyter notebook Dockerfile

docker run -d -p 8888:8888 --name jupyter dayelee/jupyter-notebook /bin/sh -c "jupyter notebook --no-browser --ip=0.0.0.0 --allow-root --NotebookApp.password='sha1:bb9ea858e58e:0c502a42c7e476af2eff7fb60c7273f1ce09acdb'"

默认密码: jupyter  
NotebookApp.password参数后面是通过IPython.lib.passwd()函数得到的密码的哈希值。

jupyter notebook当前的工作目录是系统根目录（/），下个版本增加一个WORKDIR指令，将工作目录指定为其它目录。