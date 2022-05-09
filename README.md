vps更新系统

yum update -y  #CentOS系统命令

apt update -y  #Debian系统命令

安装工具组件

yum install -y wget  #CentOS系统命令


apt install -y wget  #Debian系统命令




执行Xray一键安装脚本



wget -P /root -N --no-check-certificate "https://raw.githubusercontent.com/mack-a/v2ray-agent/master/install.sh" && chmod 700 /root/install.sh && /root/install.sh



该脚本运行一次以后，以后想调出该脚本使用，只需要在 VPS 命令行输入 vasma 即可。

