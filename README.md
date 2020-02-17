# conda-
## 列出当前所有的环境： conda info --envs
## 创建新环境：conda create -n 环境名字
## 激活环境：source activate 环境名字
## 关闭环境：source deactivate
## 删除一个已有的环境：conda remove -n 环境名字 --all
## 列出环境里都安装了什么： 先进入那个环境，然后conda list
## 复制环境：直接使用conda create -n new_env --clone old_env复制既有环境
## 查看cuda版本：nvcc -V或nvcc --version
## python中import某个文件夹import data.data_loader没法import时，可以在文件夹内建立一个__init__.py文件
## 若是要在另一台服务器上复制环境，可以直接copy过去，scp -r -P ld@xxx.xxx.xxx.xxx:home/miniconda3/envs........
