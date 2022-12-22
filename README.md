# FFmpeglive
ffmpeg实现24小时不间断推流

需要配合screen运行：

yum -y install screen

开个新窗口：

screen -S stream

查看进程：

screen -ls

开启后台运行进程：

screen -d 进程名

关闭后台运行进程：

screen -X -s 进程名 quit

执行FF_Live：

bash <(curl -Ls https://raw.githubusercontent.com/TikTok365/FFmpeglive/main/start.sh)
