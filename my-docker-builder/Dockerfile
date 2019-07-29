FROM ccr.ccs.tencentyun.com/yuri_namespace/my-vpn

RUN apt install git -y
pip install git+https://github.com/shadowsocks/shadowsocks.git@master

CMD sslocal -c /data/shadowsocks.json