# image-code
图像分析论文作业代码  
1.  
conda create --name ep1 python=3.8  
2.  
conda activate ep1  
3.  
pip install -r requirements.txt  
4.  
cd .\图像代码_包含预处理后的实验数据集\UPCOL_all_false_128_128_128\UPCOL_TEst\UPCoL-main\codes  
5.  
sudo chmod 777  ./train.sh  
6.  
./train.sh  
默认unlab_batch_size为2，在gpu 0上训练。在这个情况下gpu0需要30GB显存。  
如果不足可以在train.py将unlab_batch_size改为1。  
