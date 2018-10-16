# Description: This dockerfile uses the python image
# Version：    V1.0
# Author：     LiLe
# Contact:     836217653@qq.com

FROM python:2.7

#为后续的命令指定工作目录
WORKDIR /code

#将指定的src复制到容器的dest，其中src可以是Dockerfile所在目录的一个相对路径；也可以是一个URL，还可以是一个tar文件，会自动解压为目录；这里的.是Dockerfile所在的目录
ADD . /code

#Docker服务端暴露的端口号，在容器启动时需要使用-P指定
EXPOSE 80


CMD python index.py
