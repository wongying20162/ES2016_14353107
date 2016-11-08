# 安装ROS

### 配置Ubuntu软件库（已配好）

### 设置源列表

sudo sh -c 'echo "deb http://packages.ros.org/ros/ubuntu $(lsb_release -sc) main" > /etc/apt/sources.list.d/ros-latest.list'

### 设置keys

sudo apt-key adv --keyserver hkp://ha.pool.sks-keyservers.net:80 --recv-key 0xB01FA116

### 安装

1.更新

sudo apt-get update

2.选择Desktop-Full Install

sudo apt-get install ros-jade-desktop-full

### 初始化rosdep

sudo rosdep init
rosdep update

### 安装环境

echo "source /opt/ros/jade/setup.bash" >> ~/.bashrc
source ~/.bashrc

source /opt/ros/jade/setup.bash

### 获得ros安装

sudo apt-get install python-rosinstall

### 从安装包里获得代码

$ apt-get source ros-jade-laser-pipeline

