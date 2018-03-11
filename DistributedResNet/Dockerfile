FROM registry.cn-hangzhou.aliyuncs.com/denverdino/tensorflow:latest

RUN apt update && apt install -y python3-pip && echo y | pip3 install tensorflow

RUN mkdir -p /tf/resnet
ADD src /tf/resnet
ENTRYPOINT ["python3","/tf/resnet/tfconfig_wrapper.py"]
