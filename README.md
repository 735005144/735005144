python train.py --dataset dsb2018_96 --arch NestedUNet --epoch 1
跑训练
python val.py --name dsb2018_96_NestedUNet_woDS
跑验证
python D:\git\HuggingFace-Download-Accelerator-main\hf_download.py --model deepseek-ai/DeepSeek-R1-Distill-Qwen-1.5B --save_dir D:\Desktop\Learn_Transformer\deepseek-aiDeepSeek-R1-Distill-Qwen-1.5B --exclude "*.msgpack *.bin tf_model.h5"  --use_hf_transfer False
从hugging face下载模型
python D:\git\HuggingFace-Download-Accelerator-main\hf_download.py --datasetShengbinYue/DlSC-Law-SFT --save_dir D:\Desktop\Learn_Transformer\dataset --exclude "*,msgpack*.bin tf model.h5"--use_hf_transfer False
从hugging face下载数据集
ollama run deepseek-r1:1.5b
运行ollama
