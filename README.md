# hello_world
[English](./README.md) | 简体中文

# 功能介绍

该功能包通过同时接收赛道识别节点与障碍物识别节点的消息，控制小车巡线与避障

# 使用方法

## 准备工作



## 安装功能包

**1.安装功能包**


```bash
sudo apt update
sudo apt install -y hello_world
```

**2.运行

```shell
source /opt/tros/local_setup.bash

ros2 hello_world hello_world
```


# 接口说明

## 话题

### Pub话题

| 名称                          | 消息类型                                                     | 说明                                                   |
| ----------------------------- | ------------------------------------------------------------ | ------------------------------------------------------ |
| /cmd_vel    | geometry_msgs/msg/Twist             | 发布小车控制消息                 |

### Sub话题