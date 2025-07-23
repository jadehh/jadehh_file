# 线阵相机拼接服务
## 线阵相机拼接服务V1.0.1.7 - 2025-07-23 06:33:21
ds_stitching_serviceV1.0.1.7
*  [发布地址](https://github.com/jadehh/VideoStitching/releases/tag/ds_stitching_serviceV1.0.1.7)
*  [详细地址](https://github.com/jadehh/jadehh_file/releases/tag/ds_stitching_serviceV1.0.1.7)
### 下载地址
* [ds_stitching_service_lib64.zip](https://gh.ddlc.top/https://github.com/jadehh/jadehh_file/releases/download/ds_stitching_serviceV1.0.1.7/ds_stitching_service_lib64.zip)
* [ds_stitching_service](https://gh.ddlc.top/https://github.com/jadehh/jadehh_file/releases/download/ds_stitching_serviceV1.0.1.7/ds_stitching_service)
### 更新日志
#### ds_stitching_serviceV1.0.1.7 - 2025-07-19
##### 优化
* 优化初始化相机的bug，相机初始化完成时，输出相机的参数，初始化完成才会使用正式数据连接相机
* 优化各种日志输出
##### 新增
* 相机需要分时段刷新相机曝光，解决无车经过时，相机曝光值不变的bug。
* 新增刷新曝光线程，每隔多少时间刷新一次曝光值
* 刷新曝光的次数从3000降低到稳定的值为158，需要抓拍34次
* 刷新曝光的次数从158降低到稳定的值为3000，需要抓拍50次
* 新增刷新曝光次数，初始化的时候根据最大刷新曝光次数为50，刷新曝光的次数参数可配置默认为30
* 自动编译生成可执行文件
#### 待优化
* 待优化的问题，根据现场实际情况，查看半个小时内，刷新曝光需要的次数，看是否可以减少刷新曝光的次数
---
