v2ray
最好用的 V2Ray 一键安装脚本 & 管理脚本 备份复制的233blog大佬的，万分感谢

为了避免由于不可抗拒的原因所造成本人主动删除脚本，所以建议请将本脚本 Fork 一份 备份地址： https://github.com/233boy/v2ray/fork 安装方法，确保你已经 Fork 了脚本，将 233boy 修改成你的 Github 用户名

git clone https://github.com/PainForMe/v2ray 
cd v2ray 
chmod +x install.sh 
./install.sh local

如果提示 curl: command not found ，那是因为你的小鸡没装 Curl ubuntu/debian 系统安装 Curl 方法: apt-get update -y && apt-get install curl -y centos 系统安装 Curlcentos 系统安装 方法: yum update -y && yum install curl -y 安装好 curl 之后就能安装脚本了

如果提示-bash: git: command not found,那是因为你的小鸡没装git ubuntu/debian 系统安装git方法 sudo apt-get install git centos 系统安装git方法 yum install git -y 或 yum install -y git
