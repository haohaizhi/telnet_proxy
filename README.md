编译：gcc $PWD/libtelnet.c $PWD/telnet-proxy.c -o telnet-proxy

拷贝：cp ./telnet-proxy /usr/sbin/

使用：telnet-proxy 10.10.10.252 23 23

	  连接到服务器10.10.10.252端口23上并在本地端口23上侦听

来源：https://github.com/osmocom/libtelnet
								