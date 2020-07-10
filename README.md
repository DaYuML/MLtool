# 欢迎使用MLtool

@(from)[马克飞象|帮助|Markdown]

**小组工具**本项目就是简单记录一些常用的服务器工具或者一写其他有用的工具
 
-------------------

## 目录
> 没有严格的限制，一时兴起，刚开始做这个项目。做的不好，多多谅解，有些是点一下，具体可以百度查查。


### 服务器工具

#### 下载工具
- **工具名字** : aria2c ;
- **实例** : 
```powershell
# 一般
aria2c 链接
# 或者
aria2c -s 2 -x 2 -j 10 -c http://dl_dir.qq.com/qqfile/qq/QQ2011/QQ2011.exe
# 具体的可以自己去查查，不加修改的情况下，默认都是下载到当前目录
```
| 工具介绍 |
| :-------- |
| Aria2 是一个多平台轻量级，支持 HTTP、FTP、BitTorrent 等多协议、多来源的命令行下载工具。Aria2 可以从多个来源、多个协议下载资源，最大的程度上利用了你的带宽。Aria2 有着非常小的资源占用，在关闭磁盘缓存的情况下，物理内存占用通常为 4M（正常 HTTP/FTP 下载的情况下），BitTorrent 下载每秒2.8M/S的情况下，CPU 占有率约为 6%。Aria2 支持 JSON-RPC 和 XML-RPC 接口远程调用。 |

- **工具名字** : wget ;
- **实例** : 
```powershell
# 一般
wget 链接
# 具体的可以自己去查查，不加修改的情况下，默认都是下载到当前目录
```
#### 网速查看工具
- **工具名字** : slurm ;
- **实例** : 
```powershell
slurm -i enp2s0
# slurm -i 网卡号
# 不清楚的可以使用如下命令查看网卡
ifconfig
```

### 其他工具
#### 画图工具
- **工具名字** : echarts ;
- **工具地址** : [链接](https://echarts.apache.org/examples/zh/index.html) 或者 https://echarts.apache.org/examples/zh/index.html ; 
- **工具教程** : [链接](https://www.runoob.com/echarts/echarts-tutorial.html) 或者 https://www.runoob.com/echarts/echarts-tutorial.html ; 

| 工具介绍 |
| :-------- |
| ECharts 是一个使用 JavaScript 实现的开源可视化库，涵盖各行业图表，满足各种需求。ECharts 遵循 Apache-2.0 开源协议，免费商用。ECharts 兼容当前绝大部分浏览器（IE8/9/10/11Chrome Firefox Safari等）及兼容多种设备，可随时随地任性展示。 |


### 
