FROM ccr.ccs.tencentyun.com/yuri_namespace/my-python:master

RUN apt install git -y
RUN pip3 install git+https://github.com/shadowsocks/shadowsocks.git@master

CMD sslocal -c /data/shadowsocks.json