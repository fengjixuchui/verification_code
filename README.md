# verification_code
验证码研究破解心得记录。包含网易易盾，阿里云验证码，极验验证码等主流验证码破解。已更新极验验证码、点选验证码、语序验证码、企业公示网采集心得。



:boom:请保证本项目仅用于研究学习，谢谢:boom:




![](https://img.shields.io/badge/Python-%3E%3D3.6-orange?style=social) ![](https://img.shields.io/github/license/huaiyukeji/verification_code) 



---



## 待更新内容

如果对您有用，请给个star:star::star::star:谢谢。

刚建了个群，随缘加加！不能分享的代码在群里交流！群号：:rocket:`1040784971`:rocket:

许多内容待整理。

### 极验的JS破解流程以及点选验证码识别模型

极验分为三个部分，1. 破解了前端，获取validate参数；2. 文字类的验证码；3. 滑动验证码。验证码部分结合机器学习在本地打码。

- [极验验证码前端JS破解思路](./doc/jiyan_gt_challenge.md)

	极验js方面，获取validate就完结了。

  - [x] gt、challenge
  - [x] [获取gt和challenge的demo](./doc/jiyan_gt_challenge_demo.ipynb)
  - [ ] validate
  - [ ] 获取validate的demo

- 点选验证码汉字识别模型

  这部分极验和易盾是通用的，数据集改改就好了。如果有数据集可以和我共享，我收集完统一标注然后共享出来。数据集完备后更新一波`一步识别`的模型出来。

  - [x] [Ubuntu环境安装](./doc/Ubuntu18.04%20install%20darknet%20yolo-v3%7Ccuda%7Ccudnn%7Copencv%7Canaconda.md)
  	- NVIDIA-SMI|CUDA|cuDNN|OpenCV|Anacoda
  - [x] [汉字定位（目标检测）](./hanzi_detection/README.md)
  - [x] [汉字识别](./hanzi_detection/readme_classify.md)
  - [x] [定位模型训练手册（含数据）](./doc/detector_train_handbook.md)
  - [x] [识别模型训练手册（含数据）](./doc/classifier_train_handbook.md)
  - [ ] 定位+识别的结合
  - [ ] Python中使用模型
  - [ ] 模型速度优化

- 滑动3.0和机器学习

  - [ ] 滑动轨迹

### 瑞数JS




## 联系方式
欢迎技术交流：`huaiyukeji@gmail.com`

QQ群：1040784971

商务合作VX：`Hunter_--_`

或者扫一扫加我微信，请备注GitHub，谢谢。
<p align="center">
	<img src="./IMG_1766.JPG" alt="Sample"  width="160" height="250">
</p>

