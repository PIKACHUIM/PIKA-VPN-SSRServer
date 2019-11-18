wget --no-check-certificate -O install.sh http://pika-shared-sz.oss-cn-shenzhen.aliyuncs.com/ssr/server/install.sh
chmod +x install.sh
./install.sh 2>&1 | tee shadowsocks.log