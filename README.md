# win10安装Pytorch

#### 参考网页
- win7 64位Anaconda3下安装Pytorch教程 - CSDN博客 [https://blog.csdn.net/u011501388/article/details/78008929](https://blog.csdn.net/u011501388/article/details/78008929)

#### Pytorch下载
- 链接：[https://pan.baidu.com/s/1DoXllDduK5UGvh2lSFqzMw](https://pan.baidu.com/s/1DoXllDduK5UGvh2lSFqzMw) 密码：qkf9


#### 命令
- cmd
- cd xxx (xxx表示Anaconda3的目录)
- conda install --offline pytorch-0.1.12-py36_0.1.12cu80.tar.bz2 (没有提示就安装成功)
- python # 自己测试一下


#### Pytorch更新
- 参考:[https://zhuanlan.zhihu.com/p/26871672](https://zhuanlan.zhihu.com/p/26871672)
- conda config --add channels https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/peterjc123/

- for CPU only packages
-- conda install pytorch-cpu

- for Windows 10 and Windows Server 2016, CUDA 8
-- conda install pytorch

- for Windows 10 and Windows Server 2016, CUDA 9
-- conda install pytorch cuda90

- for Windows 7/8/8.1 and Windows Server 2008/2012, CUDA 8
-- conda install pytorch_legacy

#### Error
- import error:   from torch._C import * ImportError: DLL load failed: The specified module could not be found.
- 参考:[https://blog.csdn.net/manong_wxd/article/details/78583098](https://blog.csdn.net/manong_wxd/article/details/78583098)
