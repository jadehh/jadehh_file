# 算法配置客户端
## 算法配置客户端V2.1.6.6 - 2025-02-11 09:25:45
AlgorithmConfiureV2.1.6.6
*  [发布地址](https://github.com/jadehh/AlgorithmConfigUI/releases/tag/V2.1.6.6)
*  [详细地址](https://github.com/jadehh/jadehh_file/releases/tag/AlgorithmConfiureV2.1.6.6)
### 下载地址
* [Windows_lib32.zip](https://github.com/jadehh/jadehh_file/releases/download/AlgorithmConfiureV2.1.6.6/Windows_lib32.zip)
* [Linux_x86_64_lib64.zip](https://github.com/jadehh/jadehh_file/releases/download/AlgorithmConfiureV2.1.6.6/Linux_x86_64_lib64.zip)
* [Linux_aarch64_lib64.zip](https://github.com/jadehh/jadehh_file/releases/download/AlgorithmConfiureV2.1.6.6/Linux_aarch64_lib64.zip)
* [AlgorithmConfiure_setup-Portable-V2.1.6-6.exe](https://github.com/jadehh/jadehh_file/releases/download/AlgorithmConfiureV2.1.6.6/AlgorithmConfiure_setup-Portable-V2.1.6-6.exe)
* [AlgorithmConfiure_setup-V2.1.6-6.exe](https://github.com/jadehh/jadehh_file/releases/download/AlgorithmConfiureV2.1.6.6/AlgorithmConfiure_setup-V2.1.6-6.exe)
* [AlgorithmConfiure-Portable-Linux_x86_64-V2.1.6-6.zip](https://github.com/jadehh/jadehh_file/releases/download/AlgorithmConfiureV2.1.6.6/AlgorithmConfiure-Portable-Linux_x86_64-V2.1.6-6.zip)
* [AlgorithmConfiure-Linux_x86_64-V2.1.6-6.zip](https://github.com/jadehh/jadehh_file/releases/download/AlgorithmConfiureV2.1.6.6/AlgorithmConfiure-Linux_x86_64-V2.1.6-6.zip)
* [AlgorithmConfiure-Portable-Linux_aarch64-V2.1.6-6.zip](https://github.com/jadehh/jadehh_file/releases/download/AlgorithmConfiureV2.1.6.6/AlgorithmConfiure-Portable-Linux_aarch64-V2.1.6-6.zip)
* [AlgorithmConfiure-Linux_aarch64-V2.1.6-6.zip](https://github.com/jadehh/jadehh_file/releases/download/AlgorithmConfiureV2.1.6.6/AlgorithmConfiure-Linux_aarch64-V2.1.6-6.zip)
* [AlgorithmConfiure-Portable-Darwin_x86_64-V2.1.6-6.zip](https://github.com/jadehh/jadehh_file/releases/download/AlgorithmConfiureV2.1.6.6/AlgorithmConfiure-Portable-Darwin_x86_64-V2.1.6-6.zip)
##### 更新日志
###### V2.1.6.6 - 2025-01-20
###### 新增
* 新增线阵相机拼接服务管理界面，
* 新增线阵相机拼接服务配置界面
* 支持线阵相机拼接服务配置和服务的启动功能
* 线阵相机视频服务与视频拼接服务一样，都是与验残平台统一对接，形成视频拼接服务和线阵相机拼接服务的通道
* 验残平台与拼接管理服务对接时，根据相机类型去匹配用视频拼接服务和线阵相机拼接服务
* 新增线阵相机管理工具，支持线阵相机的实时预览和部分参数设置，集成线阵相机SDK
* 线阵相机管理工具支持查找设备功能，查找的设备支持IP地址修改功能,线阵相机支持设备重置功能
* 线阵相机管理工具支持实时预览与软触发抓拍预览，和保存图片功能，解决实时预览中遇到的bug
* 线阵相机管理工具支持参数获取功能，并获取参数的描述，包括最大值与最小值
* 新增验残下发的线阵相机的配置修改界面，支持手动修改相机参数。
* 线阵相机参数修改界面，支持传入默认的参数，修改参数，预览并保存功能。
* 解决由于相机打开失败或打开慢的问题，导致相机顺序出错的bug
* 解决在打包是遇到的环境报错
* 去除代理中不适用的链接地址
###### 修改
* 解决自动打包引用pydalsa的bug
* controller中部分view py文件不存在的bug
* 解决Arm平台无法打包的bug
---
