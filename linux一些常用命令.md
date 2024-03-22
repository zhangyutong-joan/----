```
conda update -n base conda #update最新版本的conda
conda activate xxxx #开启xxxx环境
conda deactivate  #关闭环境
conda remove -n xxxx --all  #删除xxxx环境
conda env list #显示所有的虚拟环境
conda info --envs #显示所有的虚拟环境

conda list         #查看已经安装的文件包
conda list -n xxxx       #指定查看xxxx虚拟环境下安装的package
conda update xxxx   #更新xxxx文件包
conda uninstall xxxx   #卸载xxxx文件包
```
- 使用python36或者zytjoan环境

- 开启jupyter直接在终端输入```jupyter notebook```然后复制http://localhost:8888/ 到浏览器就可以了。

查看gpu是否空闲：```nvidia-smi```