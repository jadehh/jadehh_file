# 算法配置客户端
## 算法配置客户端V2.1.8.0 - 2025-06-27 09:26:49
AlgorithmConfiureV2.1.8.0
*  [发布地址](https://github.com/jadehh/AlgorithmConfigUI/releases/tag/V2.1.8.0)
*  [详细地址](https://github.com/jadehh/jadehh_file/releases/tag/AlgorithmConfiureV2.1.8.0)
### 下载地址
* [Windows_lib32.zip](https://github.com/jadehh/jadehh_file/releases/download/AlgorithmConfiureV2.1.8.0/Windows_lib32.zip)
* [Linux_x86_64_lib64.zip](https://github.com/jadehh/jadehh_file/releases/download/AlgorithmConfiureV2.1.8.0/Linux_x86_64_lib64.zip)
* [Linux_aarch64_lib64.zip](https://github.com/jadehh/jadehh_file/releases/download/AlgorithmConfiureV2.1.8.0/Linux_aarch64_lib64.zip)
* [AlgorithmConfiure_setup-Portable-V2.1.8-0.exe](https://github.com/jadehh/jadehh_file/releases/download/AlgorithmConfiureV2.1.8.0/AlgorithmConfiure_setup-Portable-V2.1.8-0.exe)
* [AlgorithmConfiure_setup-V2.1.8-0.exe](https://github.com/jadehh/jadehh_file/releases/download/AlgorithmConfiureV2.1.8.0/AlgorithmConfiure_setup-V2.1.8-0.exe)
* [AlgorithmConfiure-Portable-Linux_x86_64-V2.1.8-0.zip](https://github.com/jadehh/jadehh_file/releases/download/AlgorithmConfiureV2.1.8.0/AlgorithmConfiure-Portable-Linux_x86_64-V2.1.8-0.zip)
* [AlgorithmConfiure-Linux_x86_64-V2.1.8-0.zip](https://github.com/jadehh/jadehh_file/releases/download/AlgorithmConfiureV2.1.8.0/AlgorithmConfiure-Linux_x86_64-V2.1.8-0.zip)
* [AlgorithmConfiure-Portable-Linux_aarch64-V2.1.8-0.zip](https://github.com/jadehh/jadehh_file/releases/download/AlgorithmConfiureV2.1.8.0/AlgorithmConfiure-Portable-Linux_aarch64-V2.1.8-0.zip)
* [AlgorithmConfiure-Linux_aarch64-V2.1.8-0.zip](https://github.com/jadehh/jadehh_file/releases/download/AlgorithmConfiureV2.1.8.0/AlgorithmConfiure-Linux_aarch64-V2.1.8-0.zip)
* [AlgorithmConfiure-Portable-Darwin_x86_64-V2.1.8-0.zip](https://github.com/jadehh/jadehh_file/releases/download/AlgorithmConfiureV2.1.8.0/AlgorithmConfiure-Portable-Darwin_x86_64-V2.1.8-0.zip)
##### 更新日志
###### V2.1.8.0 - 2025-05-25
###### 新增
* 新增算法箱门识别，支持箱门识别服务的算法配置，算法更新，以及算法服务的启动
* 箱号识别服务支持箱门识别服务的配置，支持与箱门识别服务的对接
* 过卡详情界面支持箱门识别的结果查看
* 支持Tensorrt 箱门识别服务的启动
###### 修改
* Docker镜像修改只分成5个版本分别是
* samples_ocrV2.4 兼容箱号识别服务的老版本，不支持30系列以上的显卡
* jadehh/algorithm:v1.2  兼容所有算法服务cuda11版本， 显卡版本:cuda10的时候用
* jadehh/algorithm:v1.1  兼容所有算法服务cuda10版本， 显卡版本:cuda高于10的时候用
* jadehh_algorithm_onnx-arch-7.5-runtime-py3.8 兼容除了线阵相机算法服务的版本, 显卡版本:cuda10的时候用
* jadehh_algorithm_onnx-arch-8.6-runtime-py3.8 兼容除了线阵相机算法服务的版本, 显卡版本:cuda高于10的时候用
* 还有一个规则就是判断显卡的计算能力，如果计算能力大于7.5,只能使用jadehh/algorithm:v1.2这个版本的镜像，其他的都优先使用algorithm:v1.1
* 低版本的显卡，在升级了显卡驱动后，这两个镜像是都可以使用的
* 30系列后的显卡，计算能力大于8，最低的cuda支持11以上，整理下规则
* 显卡计算能力大于7.5,使用jadehh/algorithm:v1.2镜像
* 显卡计算能力小于7.5,使用jadehh/algorithm:v1.1镜像,如果jadehh/algorithm:v1.2镜像存在，也可以使用，但是要确保显卡驱动版本是cuda10以上的
* 镜像启动前，需要先查看当前系统已安装的镜像，优先使用本地的镜像。
* jadehh/algorithm:v1.2 理论上适配所有的显卡，但是要确保显卡驱动版本是cuda11以上的，但是显存占用会更高
* ----
