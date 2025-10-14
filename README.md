# 线阵相机拼接服务
## 线阵相机拼接服务V1.0.2.2 - 2025-10-14 04:58:55
ds_stitching_serviceV1.0.2.2
*  [发布地址](https://github.com/jadehh/VideoStitching/releases/tag/ds_stitching_serviceV1.0.2.2)
*  [详细地址](https://github.com/jadehh/jadehh_file/releases/tag/ds_stitching_serviceV1.0.2.2)
### 下载地址
* [ds_stitching_service_lib64.zip](https://gh.ddlc.top/https://github.com/jadehh/jadehh_file/releases/download/ds_stitching_serviceV1.0.2.2/ds_stitching_service_lib64.zip)
### 更新日志
#### ds_stitching_serviceV1.0.2.2 - 2025-08-19
##### 修复
* 拼接超时后，上一次拼接任务还未完成,认定当前序列号无效，后续永远不会触发，
* 收到拼接超时后，将相机拼接的任务状态设置为完成,重新开始拼接任务
---
#### ds_stitching_serviceV1.0.2.1 - 2025-07-23
##### 优化
* Config优化，去除不必要的配置项
##### 修复
* 修复相机重置后，数字增益设置失败的bug
##### 新增
* 支持图片旋转90度和270操作
---
