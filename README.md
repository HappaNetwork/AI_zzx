# So-VITS-SVC 模型

本项目基于 **So-VITS-SVC** 训练 
讲话人:猪猪

## 训练情况
- **主模型 (Main Model)**：训练 **34,400 步**  
- **浅扩散模型 (Shallow Diffusion Model)**：训练 **54,000 步**

## 使用方法
1. 克隆并安装 [So-VITS-SVC](https://github.com/svc-develop-team/so-vits-svc) 环境。  
2. 下载本仓库中的模型文件，并放置到 `logs/44k/` 或对应模型目录下。  
3. 运行推理脚本进行声音转换。

```bash
python inference_main.py -m "模型路径" -c "配置文件路径" -n "输入音频.wav" -t 0