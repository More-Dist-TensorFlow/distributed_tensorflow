FROM registry.cn-hangzhou.aliyuncs.com/denverdino/tensorflow:latest

RUN mkdir -p /tf/lenet
ADD src /tf/lenet
ENTRYPOINT ["python3","/tf/lenet/tfconfig_wrapper.py"]
