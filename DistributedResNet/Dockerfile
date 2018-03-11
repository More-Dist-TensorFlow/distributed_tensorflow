FROM registry.cn-hangzhou.aliyuncs.com/denverdino/tensorflow:latest

RUN mkdir -p /tf/resnet
ADD src /tf/resnet
ENTRYPOINT ["python3","/tf/resnet/tfconfig_wrapper.py"]
