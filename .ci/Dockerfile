From  python:2.7-slim  # 设置基础镜像为python:2.7-slim

WORKDIR  /app

ADD .  /app    #ADD命令复制本地文件到镜像路径（ADD /path/to/本地文件  /path/to/容器）

RUN pip  install -r  requirements.txt       #pip安装reqirements.txt文件中的模块

EXPOSE 80                         # 暴露容器的80端口

ENV  NAME World                #  设置环境变量 NAME='World'

CMD["python","app.py"]          # 运行命令 python app.py
