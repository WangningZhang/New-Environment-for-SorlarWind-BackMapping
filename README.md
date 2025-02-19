# New-Environment-for-SorlarWind-BackMapping
This is a approach to run my BackMapping code. The general procedure involves first installing a Linux subsystem on your computer and then creating a standard environment using conda. The following are the detailed steps:

## 1. Install sub-Linux system

打开 控制面板 --> 程序 --> 启用或关闭Windows功能 勾选 适用于Linux的Windows子系统 ，如下图所示

![image](https://github.com/user-attachments/assets/49b7feb4-13e9-4784-8afa-c0f8e17e47e6)

点击 确定 等待系统设置完毕后，选择 立即重新启动 即可。

以管理员权限打开终端，并输入 'wsl --install'，等待安装完成即可。

打开 Microsoft Store 搜索 Ubuntu 点击下载（随便哪个版本都可以），下载完成后点击Ubuntu图标运行 按照提示为Linux系统设置用户名及密码。
注：在后续步骤中注意区分 win系统终端 和 Ubuntu系统终端，win系统终端用 win+R 输入cmd后运行，Ubuntu系统终端直接点击刚刚下载好的Ubunbtu图标即可

上述步骤完成安装Linux子系统，如果哪里报错了可以先去必应查查。大部分电脑会在第一次打开Ubuntu时报错，将报错代码问问GPT怎么解决就好啦！

## 2. Configuring the environment with miniconda
在Ubuntu系统中安装miniconda，在Ubuntu系统终端中分别输入：

wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
bash ~/Miniconda3-latest-Linux-x86_64.sh

输入

`conda --version`


详情可参考'https://docs.anaconda.com/miniconda/install/#quick-command-line-install'

将miniconda安装后，下载 environment.yml 文件到本地，在保存 yml 文件的目录下打开 Ubuntu 系统终端输入：



## 3. Install VScode app and setting it
安装 VScode，在左侧应用商店中下载 WSL

## 4. Description of the code and data format
