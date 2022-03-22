# 基于图计算的挖掘推理 软件部署记录
基于图计算的挖掘推理，包括关键路径识别和脆弱子图识别两个模块，部署在搭载麒麟4.0.2系统的服务器上，
软件界面访问网址为（南京）http://10.64.140.40/ （无锡）http://121.248.58.101/。

## Table of Contents
- [软件环境搭建](#软件环境搭建)
  - [anaconda安装](#anaconda安装)
## 软件环境搭建
前端环境为node 17.3.0、create-react-app脚手架 5.0.0、react 17.0.2；  
后端采用anaconda管理虚拟环境，安装python3.7.10，除python基础包外，还配置安装了pandas1.3.4、
numpy1.21.5、paddlepaddle2.2.2 cpu、torch1.8.0、networkx2.6.2、imbalanced-learn0.9.0、fastapi0.75.0等。

### anaconda安装  
  - 进入软件目录下执行如下命令：
 ```markdown
 bash Anaconda3-2021.05-Linux-x86_64.sh
 ```
  - 按回车直到出现如下界面，然后输入yes。
![image](https://github.com/asyouknowme/test/blob/main/%E5%9B%BE%E7%89%87/1.png)
  - 此处按回车则安装到默认路径，或自定义输入路径进行安装。
