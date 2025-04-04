### 烂代码
- **跑训练**：
python train.py --dataset dsb2018_96 --arch NestedUNet --epoch 1
- **跑验证**：
python val.py --name dsb2018_96_NestedUNet_woDS
- **从hugging face下载模型**：
python D:\git\HuggingFace-Download-Accelerator-main\hf_download.py --model deepseek-ai/DeepSeek-R1-Distill-Qwen-1.5B --save_dir D:\Desktop\Learn_Transformer\deepseek-aiDeepSeek-R1-Distill-Qwen-1.5B --exclude "*.msgpack *.bin tf_model.h5"  --use_hf_transfer False*
- **从hugging face下载数据集**：
python D:\git\HuggingFace-Download-Accelerator-main\hf_download.py --datasetShengbinYue/DlSC-Law-SFT --save_dir D:\Desktop\Learn_Transformer\dataset --exclude "*,msgpack*.bin tf model.h5"--use_hf_transfer False
- **运行ollama**：
ollama run deepseek-r1:1.5b


### 环境管理
- **创建新环境**：
  conda create --name myenv
  创建一个名为 "myenv" 的新环境。
- **创建指定版本的环境**：
  conda create --name myenv python=3.8
  创建一个名为 "myenv" 的新环境，并指定 Python 版本为 3.8。
- **激活环境**：
  conda activate myenv
  激活名为 "myenv" 的环境。
- **退出当前环境**：
  deactivate
  退出当前环境。
- **查看所有环境**：
  conda env list
  查看所有已创建的环境。
- **复制环境**：
  conda create --name myclone --clone myenv
  通过克隆已有环境创建新环境。
- **删除环境**：
  conda env remove --name myenv
  删除名为 "myenv" 的环境。
