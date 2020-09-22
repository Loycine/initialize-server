# initialize-server
initialize-server是配置Linux服务器的部分深度学习环境的脚本管理工具，如安装miniconda，配置conda mirror，配置pip mirror，配置git-config等。

## Overview
initserv为入口程序。每一项环境安装任务抽象成一个target，由initserv程序的参数指定target文件。

## Usage
Clone this repository, and do the following commands.

```
cd initialize-server
./initserv user/default
```