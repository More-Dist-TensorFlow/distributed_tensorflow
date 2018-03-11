FROM registry.cn-hangzhou.aliyuncs.com/denverdino/tensorflow:latest

RUN apt update && apt install -y python3-pip && echo y | pip3 install tensorflow

RUN mkdir -p /tf/lenet
ADD src /tf/lenet
ENTRYPOINT ["python3","/tf/lenet/tfconfig_wrapper.py"]
