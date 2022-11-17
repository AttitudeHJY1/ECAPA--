# ECAPA初步
 翁师兄的代码

# 注意：

1.`os.chdir("D:\Pytorch_train");`里面的字符串改为ECAPA--的文件夹下即可

2.创建新的模型（运行前），在experiments文件夹下创建新的文件夹（格式参考原有），并且把变量version的字符串改成相对应的文件夹名

3.(optional)可以在ananconda prompt窗口（以管理员身份打开） ，conda activate 对应虚拟环境（自己已经创建的）cd命令到ECAPA--的文件夹下，再进行requirement.txt直接安装，示例为：

```
conda activate pytorch
cd /d D:\Git_Document\Voice_classfication\ECAPA--
pip install pipreqs
```

失败原因：1.科学上网了，把科学上网软件关掉

​					2.安装包无法放到对应的LIb库，把第三行改成

`pip install --target=D:\Anaconda\envs\pytorch\Lib pipreqs`

”D:\Anaconda\envs\pytorch\Lib“指的是ananconda虚拟环境下LIb库所在位置，请自行查找
