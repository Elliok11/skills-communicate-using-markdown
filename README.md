# AI 目标检测与大模型本地部署实践

> 人工智能协会创智部二面实战任务记录

## 📖 项目简介
本项目从零开始搭建 AI 开发环境，完成了 YOLOv8 目标检测模型的本地部署与推理测试，具体的内容是将几张要检测的图片放在根目录的文件夹""images""内，后运行程序，即可识别图片中一些常见的生活用品的数量和种类，并且输出各图片经过圈画处理的结果

## 🛠️ 环境依赖
- Python 3.11.5
- ultralytics (YOLOv8)
- 操作系统：Win10
- 硬件：CPU 推理（当前阶段）

## 🚀 快速开始

### 克隆项目到本地
```bash
git clone https://github.com/Elliok11/skills-communicate-using-markdown
.git
cd skills-communicate-using-markdown
python -m venv venv
# Windows 激活命令
venv\Scripts\activate
pip install ultralytics # 环境依赖
yolo detect predict model=yolov8n.pt source=images # 将图片放在根目录，然后复制这行运行，检测结果将保存在 runs/detect/predict 目录。




