# Tags 18.04, 20.04 (latest), 20.10
FROM ubuntu 
WORKDIR /tmp
COPY scripts /tmp 
RUN apt update && apt -y install python3 python3-pip git
RUN pip3 install --upgrade pip setuptools
RUN pip3 install --upgrade git+https://github.com/vmware/vsphere-automation-sdk-python.git
