# 计算机视觉技术作业

## 简介

根据YOLOv7目标检测模型完成计算机视觉课程任务，这个任务旨YOLOv7训练自己的数据集。

## 下载链接

权重：https://github.com/WongKinYiu/yolov7/releases/download/v0.1/yolov7.pt

yolov7：[WongKinYiu/yolov7: Implementation of paper - YOLOv7: Trainable bag-of-freebies sets new state-of-the-art for real-time object detectors (github.com)](https://github.com/WongKinYiu/yolov7)

## 使用说明

1. 直接从网上下载 YOLOv7 代码，上传到 autodl 云端；
2. 创建datasets文件夹，将自己创建的数据集放入；
3. 下载权重放到总目录下；
4. 安装依赖包：在终端输入指令：pip install -r requirements.txt；
5. 创建 coco128.yaml ：打开data文件夹，复制coco.yaml文件到主目录下，重命名为：coco128.yaml ；
6. 修改 coco128.yaml 配置文件中的内容，将修改 train 训练集和 val 验证集地址为在datasets 中所对应的位置；
7. 打开 train.py 文件，翻到大约530行，修改权重和data所对应的地址；
8. 打开终端，输入：python train.py 运行；
9. 训练完成后，训练结果放在生成的runs文件夹下。