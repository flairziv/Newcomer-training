# 视觉组培训项目 (Newcomer Training)

欢迎来到视觉组培训项目！本项目旨在为新手提供计算机视觉领域的全面培训材料和指导。

## 📋 项目概述

本培训项目涵盖了计算机视觉领域的多个重要方向，包括环境搭建、相机标定、目标检测等核心技术，为初学者提供从基础环境配置到实际项目应用的完整学习路径。通过VMware虚拟化技术、MATLAB工具箱和深度学习框架的综合运用，帮助大家掌握现代计算机视觉开发的关键技能。

## 📁 项目结构

```
FosuRMTraning/
├── README.md                                    # 本文件
├── VMware_Ubuntu_Visual_Project_Template.pdf    # VMware Ubuntu可视化项目文档
├── MATLAB_Camera_Calibration_Training.pdf       # Matlab相机标定可视化项目文档
├── YOLOv8_RoboMaster_Training.pdf               # YOLOv8 RoboMaster目标检测培训文档
└── .git/                                        # Git版本控制
```

## 📚 培训内容

### 主要模块

1. **VMware Ubuntu环境配置**
   - VMware虚拟机安装与配置
   - Ubuntu系统基础设置
   - 开发环境搭建

2. **可视化项目基础**
   - 项目模板介绍
   - 开发工具配置
   - 基础概念学习

3. **MATLAB相机标定**
   - MATLAB相机标定工具箱使用
   - 相机内参和外参标定
   - 畸变矫正与精度评估
   - 标定数据处理与分析

4. **YOLOv8目标检测与RoboMaster应用**
   - YOLOv8模型架构与原理
   - RoboMaster比赛目标检测任务
   - 模型训练与数据处理
   - 实时检测与性能优化

5. **实践项目**
   - 跟随模板文档进行实际项目开发
   - 问题解决与调试技巧

## 🚀 开始使用

### 前置要求

- VMware Workstation 或 VMware Player
- Ubuntu系统镜像
- MATLAB软件（包含Computer Vision Toolbox）
- Python 3.8+ 环境
- PyTorch深度学习框架
- 相机标定板或标定图案
- 基础的Linux命令行知识

### 学习步骤

1. **阅读培训文档**
   ```
   查看 VMware_Ubuntu_Visual_Project_Template.pdf 文档
   查看 MATLAB_Camera_Calibration_Training.pdf 文档
   查看 YOLOv8_RoboMaster_Training.pdf 文档
   ```

2. **环境准备**
   - 安装VMware虚拟化软件
   - 创建Ubuntu虚拟机
   - 配置开发环境

3. **项目实践**
   - 按照模板文档进行项目开发
   - 完成相关练习和作业

4. **MATLAB相机标定实践**
   - 准备标定图案和相机设备
   - 使用MATLAB相机标定工具箱
   - 完成相机内参外参标定
   - 进行畸变矫正和精度验证

5. **YOLOv8目标检测项目**
   - 阅读YOLOv8_RoboMaster_Training.pdf文档
   - 搭建Python深度学习环境
   - 准备RoboMaster数据集
   - 训练和部署YOLOv8模型

## 📖 学习资源

- [VMware官方文档](https://docs.vmware.com/)
- [Ubuntu官方指南](https://ubuntu.com/tutorials)
- [Git版本控制教程](https://git-scm.com/docs)
- [MATLAB相机标定文档](https://www.mathworks.com/help/vision/ug/single-camera-calibrator-app.html)
- [计算机视觉基础教程](https://www.mathworks.com/help/vision/)
- [YOLOv8官方文档](https://docs.ultralytics.com/models/yolov8/)
- [PyTorch官方教程](https://pytorch.org/tutorials/)
- [RoboMaster官方网站](https://www.robomaster.com/)

## 🛠️ 技术栈

- **虚拟化**: VMware
- **操作系统**: Ubuntu Linux
- **版本控制**: Git
- **开发环境**: MATLAB (Computer Vision Toolbox)
- **相机标定**: MATLAB Camera Calibration Toolbox
- **深度学习**: Python, PyTorch/TensorFlow
- **目标检测**: YOLOv8
- **应用领域**: RoboMaster机器人竞赛
- **可视化工具**: (根据项目需求而定)

## 📝 学习进度追踪

- [ ] 完成VMware环境搭建
- [ ] 成功安装Ubuntu系统
- [ ] 安装并配置MATLAB环境
- [ ] 配置Python深度学习环境
- [ ] 阅读完成项目模板文档
- [ ] 学习MATLAB相机标定工具箱
- [ ] 完成相机标定实践项目
- [ ] 学习YOLOv8目标检测原理
- [ ] 完成RoboMaster目标检测项目
- [ ] 掌握基础调试技能

## 📥 如何从 GitHub Release 下载文件

本项目的大文件（如压缩包、数据集、预编译环境等）不会放在仓库代码区，而是放在 **GitHub Releases** 中，请按照以下步骤下载：

---

### 方法 1：浏览器下载（推荐）
1. 打开本项目的 Releases 页面：  
   [📦 点击这里进入 Releases](https://github.com/flairziv/Newcomer-training/releases)
2. 在列表中找到你需要的版本（例如 `v1.0.0`）
3. 点击附件文件名（`vision-env-v1.zip`）开始下载

---

### 方法 2：克隆仓库并下载大文件
如果你使用 Linux / macOS / WSL，可以通过命令行下载：

#### 安装 Git LFS（首次使用需要）
```bash
sudo apt install git-lfs      # Ubuntu/Debian
git lfs install
```

#### 克隆仓库并下载大文件
```bash
git clone https://github.com/flairziv/Newcomer-training.git
```
Git LFS 会自动下载 Release 中的大文件。

---

### 方法 3：使用 wget 或 curl 直接下载
1. 进入 [Releases 页面](https://github.com/flairziv/Newcomer-training/releases)
2. 右键附件文件，复制下载链接
3. 使用命令行下载：

```bash
wget <文件下载链接>
# 或
curl -L -O <文件下载链接>
```

**示例：**
```bash
# 使用 wget 下载
wget https://github.com/flairziv/Newcomer-training/releases/download/v1.0.0/vision-env-v1.zip

# 使用 curl 下载
curl -L -O https://github.com/flairziv/Newcomer-training/releases/download/v1.0.0/vision-env-v1.zip
```

---

## 🤝 参与贡献

如果您在学习过程中发现问题或有改进建议，欢迎：

1. 提交Issue报告问题
2. 分享学习心得和经验

## 📞 支持与反馈

如果在学习过程中遇到问题，可以通过以下方式获取帮助：

- 查阅项目文档
- 联系培训同学

## 🏷️ 标签

`培训` `新手` `VMware` `Ubuntu` `可视化` `教程` `入门` `MATLAB` `相机标定` `计算机视觉` `YOLOv8` `目标检测` `RoboMaster` `深度学习` `PyTorch`

---

**祝您学习愉快！🎉**

> 如有任何问题，请随时提出。记住，每个专家都曾经是初学者！
