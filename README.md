# 线阵相机拼接服务
## 线阵相机拼接服务V1.0.0.0 - 2025-01-17 06:47:26
ds_stitching_serviceV1.0.0.0
*  [发布地址](https://github.com/jadehh/VideoStitching/releases/tag/ds_stitching_serviceV1.0.0.0)
*  [详细地址](https://github.com/jadehh/jadehh_file/releases/tag/ds_stitching_serviceV1.0.0.0)
### 下载地址
* [ds_stitching_service_lib64.zip](https://gh.ddlc.top/https://github.com/jadehh/jadehh_file/releases/download/ds_stitching_serviceV1.0.0.0/ds_stitching_service_lib64.zip)
* [ds_stitching_service](https://gh.ddlc.top/https://github.com/jadehh/jadehh_file/releases/download/ds_stitching_serviceV1.0.0.0/ds_stitching_service)
### 更新日志
#### ds_stitching_serviceV1.0.0.0 - 2024-12-27
##### 新增
* 支持使用ip地址打开海康线阵相机
* 新增Windows dll包,pydalsa在Windows环境下使用ip地址打开还海康线阵相机
* 模拟车辆进来信号给软触发信号，保存拼接图片
* 参数配置文件,支持配置曝光，数字增益，宽度，高度和行频等参数
* 抓拍图片支持使用Opencv进行旋转操作，并保存图片
* 支持读取验残平台下发的参数,使用线程进行图像拼接操作
* EIO设备接入,支持参数配置,支持配置EIO线路,获取EIO信号输入信号和输出EIO信号
* 线阵相机配置完参数后,需要校验参数,如果参数有不对的需要重新设置参数
* 线阵相机使用线程打开，支持重连操作,需要一直监听相机,防止由于不稳定，造成的断连现象，支持接受车辆进来信号，进行拼接操作
* EIO设备信号支持参数输入位数配置，和输出位数配置
* 车辆进来信号，开始触发线阵相机的软触发，支持一些相机的异常情况处理
* 使用Socket通信通知视频管理服务单个相机的拼接完成
* 加入自动打包脚本,测试打包出来的可执行文件
* 代码同时兼容Windows环境和Linux环境,完善Windows下DLL包缺失的bug,添加Linux下的so包
* 修改工程名为线阵相机拼接服务
##### 修改
* 相机参数配置区分左右顶相机，相机参数不一定相同
* 线阵相机使用回调函数获取拼接的图片
* 使用进程启动相机，EIO设备接入并入管理服务
* 使用Socket通信，接受管理服务中下发的车辆进来数据
* 本地不在接入EIO设备,与视频管理服务对接,使用Socket通信,通知车辆进来信号
---
