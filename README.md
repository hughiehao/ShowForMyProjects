### 实际工程项目的效果展示

>    测试素材均收集于网络，所有模型可处理尺寸均为1080P以上，为了展示方便进行了压缩。

------

#### 展示内容([英文](https://github.com/hughiehao/ShowForMyProjects/blob/main/README-en.md))

本人研究方向主要集中在视频增强方面，展示内容以老片去划痕、视频去雨雪和视频画质复原为例。

#### 老片去划痕

<div align="center">
  
https://user-images.githubusercontent.com/38458343/216776387-2960fb36-1b2e-48d9-ab63-aa7395b51c37.mp4

</div>

#### 去雪、去雨

https://user-images.githubusercontent.com/38458343/216776436-b5a45bdf-61a0-46c4-8362-439c7cde6e11.mp4

https://user-images.githubusercontent.com/38458343/216776451-d6bc9d71-247a-49a9-ab0d-595253dfa261.mp4

https://user-images.githubusercontent.com/38458343/216776597-e0f3e0d9-4226-4b20-af24-32968e9c5b8d.mp4

https://user-images.githubusercontent.com/38458343/216776620-81a15642-9b77-42c5-99af-f956f1fb90d6.mp4

#### 画质复原

>    复原原理: 利用有限帧数、有限信息量的高画质参考帧对输入的极低画质序列进行画质复原，输出高画质序列

如下动图是输入与输出对比，其中输入序列是原素材经过h.264编码压缩为200k码率的序列。

https://user-images.githubusercontent.com/38458343/216776517-dd196a24-d627-4a7e-b10a-bd42a29b1bd8.mp4

如下是参考帧，只使用了一张高清图片作为背景信息参考，经过处理后输出画质得到明显提高。

<div align="center">
  
![show-recover-bgr-1](https://user-images.githubusercontent.com/38458343/216776748-e1ee2f8e-29de-4c15-8b4a-336b46eed500.jpeg)

</div>

#### 双目视频生成

>    从单目视频生成具有3D效果的双目视频

3D效果很难直接展示，因此使用红蓝模式可视化，算法能够自动区分文字类和视频画面。

<img width="1672" height="942" alt="2dto3d_in" src="https://github.com/user-attachments/assets/12b69829-e2c1-4991-af58-ef17807c49c8" />

<img width="1673" height="942" alt="2dto3d_out" src="https://github.com/user-attachments/assets/45c9ebbf-23a7-4f06-866e-3474c5861f9d" />


#### 包装擦除

>   自动检测字幕、LOGO等包装元素区域并进行擦除，其中LOGO图标支持自定义的非模型训练的特定种类

<div align="center">
  
https://github.com/user-attachments/assets/2e5b2cc8-b5b5-4133-a67c-c45bac4eb40b

</div>


