FROM python:3-alpine

RUN mkdir /data

ADD vrf.py /

RUN pip3 install requests paho-mqtt

CMD ["python3","./vrf.py"]