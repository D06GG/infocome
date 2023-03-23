# infocome
基于python的信息收集工具

# 环境要求：
Python 3.8版本以上
执行下述命令安装环境

pip install requests  
pip install python_whois  
pip install python_nmap  
pip install tqdm  
最新库即可

# 使用说明：
## 执行功能
### 获得目标域名基本信息
infocome.py -u [目标域名]  
infocome.py -u [目标IP]
### 对目标域名（IP）进行端口扫描
infocome.py -u [目标域名] -p  
### 对多个目标域名实现批量扫描
infocome.py -r [包含域名的文本]（要在源码目录下）  
### 目标是否使用CDN加速服务判断
infocome.py -u [目标域名] -n  
### 对目标域名进行目录扫描
infocome.py -u [目标域名] -d  
### 对目标域名进行子域名扫描
infocome.py -u [目标域名] -s  
### 对目标域名进行全功能使用
infocome.py -u [目标域名] -a  
### 将信息收集工具收集到的信息导出到日志
infocome.py -u [目标域名] -o 123.log  

由于传播、利用此文所提供的信息而造成的任何直接或者间接的后果及损失，均由使用者本人负责。
