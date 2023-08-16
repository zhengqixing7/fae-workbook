# 销服工作手册提纲

# 基础知识
## 算能公司介绍
算能 致力于成为全球领先的通用算力提供商
专注于AI、RISC-V CPU等**算力产品**的研发和推广应用，以自研产品为核心打造了覆盖“云、边、端”的全场景应用矩阵 ，为城市大脑、智算中心、智慧安防、智慧交通、安全生产、工业质检、智能终端等应用提供算力产品及整体解决方案 。公司在北京、上海、深圳、青岛、厦门等国内 10 多个城市及美国、新加坡等国家设有研发中心
### [算能官网](https://www.sophgo.com/)

## 算能产品介绍
### [BM1684](#bm1684详情)
### [BM1684X](#bm1684x详情)
### [SE5](#se5详情)
### [SM5](#sm5详情)
### [SE6](#se6详情)
### [SE7](#se7详情)
### [SM7](#sm7详情)
### [SE8](#se8详情)

***

## [计算机基础](./基础知识/计算机基础知识.md)
### [CPU](./基础知识/计算机基础知识.md/#cpu)
### [GPU](./基础知识/计算机基础知识.md/#gpu)
### [NPU](./基础知识/计算机基础知识.md/#npu)
### [TPU](./基础知识/计算机基础知识.md/#tpu)
### [芯片频率](./基础知识/计算机基础知识.md/#芯片频率)

***
## [Linux基础](./Linux基础/Linux基础.md)
## [Docker基础](./Linux基础/Docker.md)

## 网络基础

***

# 产品知识

## BM1684详情

| 芯片型号 | BM1684 |
| :---- | :---- |
|AI算力 | INT8 17.6TOPS<br>FP32 2.2TFLOPS |
|主控CPU | ARM A53 8核 42320 DMIPS 2.3GHz|
|视频编解码能力 | H.264 & H.265:1080P@960fps视频解码能力<br>H.264 & H.265:1080P@50fps视频编码能力 |
| 图片解码能力 | JPEG 480 张/秒@1080P |
| 内存 | 最大16GB |
| 存储 | EMMC:32GB<br>FLASH:16MB |
| 接口 | 1个 PCIE EP X16 Gen3<br>1个 PCIE EPX8<br>Gen3 /1个PCIE RC X8 Gen3<br>10/100/1000 RGMII X2<br>I2C/UART/PWM/SPI/GPIO |
| 工作温度 | -40℃ ~ +105℃ |
| 典型功耗 | 16W |
| 深度学习框架 | TensorFlow /Pytorch / Paddle / Caffe / MxNet / Tengine / DarkNet |


## BM1684X详情

| 芯片型号 | BM1684X |
| :---- | :---- |
| 产品型号 | BM1684X |
| 处理器 | 8xARM A53 2.3GHz |
| 内存 | LPDDR4/LPDDR4x 4266Mbps<br>最大支持 16GB|
| AI算力 | 32 TOPS INT8<br>16 TFLOPS FP16/BF16<br>2 TFLOPS FP32|
| 视频解码 | H.264&H.265:32x1080P@25fps 8x4K@25fps<br>H.265:1x8K@25fps|
| 视频编码 | H.264&H.265: 12x1080P@25fps,3x 4K@25fps ，最大支持 8K|
| 图片编解码| JPEG 1080P@600fps ，最大支持 32768 32768 |
| 视频后处理 | 支持图像 CSC 、 Resize 、 Crop 、 Padding 、 Border 、 Font 、 Contrast Brightness Adjustment|
| 高速接口 | PCIe Gen3 X16 EP \| X8 RC + X8 EP<br>2x10/100/1000Mbps RGMII<br>1x SD/SDIO controller<br>1x eMMC 4.5/5.1|
| 低速接口 | 1xSPI<br>Flash 接口<br>3xUART接口<br>3xI2C接口<br>2xPWM接口<br>2x风扇 转速检测 接口|
| 安全性 | 支持安全启动<br>支持Trustzone<br>支持真随机数产生<br>支持安全密钥存储机制<br>支持AES/DES/SM4/SHA/RSA/ECC 等硬件加速 |
| 典型功耗 | 17W |
| 工作温度 | -40 ℃℃~ +105 |
| 工具链 | PyTorch / ONNX / Paddle / TensorFlow / Caffe / MXNet / Darknet |

***

## CV181X、CV180X详情

***

## SOC模式-BM1684

### SE5详情
#### [刷机操作](./SE5/刷机操作.md)
     

#### [网络连接](./SE5/网络连接.md)

#### 串口连接
#### 修改网络配置
#### 自带工具

### SM5详情

### SE6详情
#### [SE6升级](./SE6/SE6升级)
#### [SE6算法移植](./SE6/SE6算法移植)

## SOC模式-BM1684X

### SE7详情

### SM7详情

### SE8详情

***

## PCIE模式-BM-1684

### SC5

### SC5+

## PCIE模式-BM-1684X

### SC7 HP75

### SC7 FP300

***

## 服务器

### SG6-6-A22

### SG6-6-A32

### SG6-10-B22

***
# 开发环境配置

***
# 算法知识

# 交付

# 售后

# 沟通话术
***
## 沟通表达基本原则
* 注意言语礼貌
* 内容表达清晰、具体
* 明确沟通目的
* 不正面拒绝客户
* 不随意向客户承诺
## 重点话术示例
### 客户支持前
**1. 拜访交流型**
* **向销售了解销售对销服支持的需求**
```
您好，这次与客户交流，您提出需要销服参与，是需要销服做哪方面的支持？
```
* **向销售了解客户信息及已经做过的交流**
```
您好，为届时更好的有针对性的与客户交流，需要提前向您了解一下这个客户的基本情况，主要业务场景，以及咱们已经与客户做过哪些方面的交流？
```
* **向销售了解客户基本诉求**
```
您好，这个客户对咱们公司的基本诉求是怎样的？希望我们提供什么样的产品或者服务？
```
* **向销售了解本次交流的基本目标**
```
您好，本次拜访客户交流，咱们这边希望达成什么目标？预计本次交流后，下一步是有什么计划安排？
```
**2. 产品支持型**
* **向销售了解客户使用的算能产品及应用场景**
```
您好，客户借测（或者采购）我们的什么产品？应用在什么场景下？
```
* **向销售了解目前项目状态**
```
您好，客户项目目前是什么状态？遇到了什么问题？刚拿到设备还是已经使用了一段时间？
```
### 客户支持（拜访）
**1. 面向客户**
* **介绍公司产品及方案**
```
具体参考对应的ppt材料学习
```
* **客户问题支持**

**(1)向客户释放文档资料**
```
以上资料请查收！如果还有其他任何问题，可以随时与我们交流。
```
**(2)客户的问题暂时不会回答**
```
很抱歉，您的这个问题我需要找后端的同事咨询，稍后给您回复！
```
**(3)客户的问题暂时没时间解答**
```
很抱歉，我现在开会，会后我会来回答您的问题。
```
**(4)客户的问题暂时没人回答（微信群）**
```
很抱歉，后端的同事在忙还没看到信息。我已经再次与他们联系，他们看到信息会给您回复。
```
**(5)客户对公司产品提出建议（待优化）**
```
很感谢您的提议，我会将您的建议反馈给公司产品部门。感谢您对我们产品的支持。
```
**(6)客户的需求暂时无法满足**
```
不好意思，稍等我们内部同步一下您这个需求，迟点回复您。
```
（这个情况，话术是一方面，更重要的是要与销售同步客户的需求，确定暂时无法满足，建议由销售来判断如何回应客户，是要求产品给予支持或者是从商务层面引导）
销服层面可以做的替代性方案回复：
```
您这个需求，目前您那边使用的产品（或平台）暂时实现不了。我们还有其他xxx产品（或者平台），可以通过xx方式满足您的要求，您看是否需要使用xxx产品（或者平台）？
```
**(7)远程连接支持**
```
您好，麻烦提供一个todesk远程链接，我们远程过去帮您看一下。因为公司有安全管理规定，禁用向日葵，还望您理解！
```
**2. 面向销售**
* **反馈技术支持进展**
```
您好，目前xxx客户的产品测试已经完成了1、2、3、。。。这些内容；目前遇到的问题是xxxx，已经提交xxxx处理。下一步的计划是xxxx。请知悉！
```
* **反馈客户需求（待商务决策）**
```
您好，xx客户提出希望实现xxx功能，目前我们标准产品（平台）我不包含这部分内容，客户这部分需求需要定制，请您评估决策是否需要在本次为客户实现xxx功能。
```
**3. 面向产品或生态**
* **技术支持需求**
```
您好，这边客户使用xxx产品，遇到xxx问题，需要麻烦您这边看一下，谢谢！
```
* **文档需求**
```
您好，这边客户使用xxx产品，需要xxx文档，我在企业微盘里没有找到，您这边是否有相关文档可以提供？谢谢！
```
* **客户需求或建议反馈**
```
您好，这边客户使用xxx产品，提出如下需求（或者建议），咱们是否可以实现？等您答复，谢谢！
```
