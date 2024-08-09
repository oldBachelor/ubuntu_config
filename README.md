

<H1>解决VMWare虚拟机复制粘贴功能失效问题</h1>
sudo apt-get autoremove open-vm-tools<br>
sudo apt-get install open-vm-tools<br>
sudo apt-get install open-vm-tools-desktop<br>

<H1>解决宿主机无法ssh链接虚拟机</h1>
sudo apt-get install openssh-server<br>
sudo apt-get install ssh<br>
service ssh start<br>

<H1>创建root用户</h1>
sudo passwd root

<H1>解决vi编辑乱码问题</h1>
sudo apt-get remove vim-common<br>
sudo apt-get install vim<br>
sudo passwd root<br>