# Ecordia_PrivacyInfoProtect_System

## 一、Anaconda3 安装

1. ###### Anaconda安装-超详细版(2023)：https://blog.csdn.net/qq_45281589/article/details/134597810

2. ###### 手把手教你安装Anaconda,绝对保姆级：https://blog.csdn.net/m0_59164304/article/details/131683487

## 二、Python3（Python 3.8.19） 安装

1. ###### 在Anaconda3中，通过命令安装：anaconda安装python 3.8环境：https://blog.csdn.net/Flychuer/article/details/138124262

2. ###### Anaconda 通过界面安装python

    Anaconda提供了一个图形用户界面(GUI)，您可以使用它来安装不同版本的Python。以下是安装Python的步骤：
    
        a. 打开Anaconda Navigator。
        b. 在主界面中，点击“Environments”选项卡。
        c. 在右侧的界面中，点击“Create”按钮。
        d. 在“Name”字段中，输入您的环境名称。
        e. 在“Search Packages”字段中，搜索Python并选择您想要安装的版本。
        f. 点击“Create”按钮开始安装。
    
    注意：Anaconda通常用于管理包和环境，而不是直接安装Python解释器。在Anaconda中创建新环境时，可以指定Python版本，Anaconda会自动安装指定版本的Python。
    
    由于Anaconda已经内置了Python，所以通常不需要通过界面来“安装”Python。如果您只是想要安装一个独立的Python版本，可以直接从Python官网下载安装程序或使用系统的包管理器（如Windows上的Chocolatey，Linux上的apt-get或yum）。

## 三、Python 配置安装源

    在Python中切换pip源通常是为了提高下载速度，因为默认的源在国外。清华大学提供了一个国内的pip源，速度很快。以下是如何将pip源切换到清华源的步骤：

1. ###### 临时使用清华源：

   在pip安装时，可以通过`-i`参数指定源。例如，安装flask时，可以这样操作：

   `pip install -i https://pypi.tuna.tsinghua.edu.cn/simple flask`

2. ###### 永久切换源：

   创建或修改配置文件`pip.conf`（Linux系统位于`~/.config/pip/pip.conf`，Windows系统位于`%HOME%\pip\pip.ini`），添加以下内容：

   `[global]index-url = https://pypi.tuna.tsinghua.edu.cn/simple`

   以上步骤完成后，你就可以使用pip从清华源安装Python包了，并且会得到更快的速度。

3. ###### 通过命令永久切换切换：

    pip config set global.index-url https://pypi.tuna.tsinghua.edu.cn/simple
    pip config set global.trusted-host https://pypi.tuna.tsinghua.edu.cn
    
    如果报错，先更新pip
    pip install --upgrade pip

## 四、Python 工具包安装

          certifi                           2024.2.2
          charset-normalizer                3.3.2
          colorama                          0.4.6
          contourpy                         1.1.1
          cycler                            0.12.1
          Cython                            3.0.10
          filelock                          3.14.0
          fonttools                         4.51.0
          fsspec                            2024.3.1
          idna                              3.7
          importlib_resources               6.4.0
          intel-openmp                      2021.4.0
          Jinja2                            3.1.3
          kiwisolver                        1.4.5
          lap                               0.4.0
          lapx                              0.5.8
          logzero                           1.7.0
          MarkupSafe                        2.1.5
          matplotlib                        3.7.5
          mkl                               2021.4.0
          mpmath                            1.3.0
          networkx                          3.1
          numpy                             1.24.4
          opencv-python                     4.9.0.80
          packaging                         24.0
          pandas                            2.0.3
          pillow                            10.3.0
          pip                               23.3.1
          psutil                            5.9.8
          py-cpuinfo                        9.0.0
          pyparsing                         3.1.2
          PyQt5                             5.15.10
          PyQt5-Qt5                         5.15.2
          PyQt5-sip                         12.13.0
          python-dateutil                   2.9.0.post0
          pytz                              2024.1
          PyYAML                            6.0.1
          requests                          2.31.0
          scipy                             1.10.1
          seaborn                           0.13.2
          setuptools                        68.2.2
          shapely                           2.0.4
          six                               1.16.0
          sympy                             1.12
          tbb                               2021.12.0
          tflite-runtime                    2.5.0
          thop                              0.1.1.post2209072238
          torch                             2.3.0
          torchaudio                        2.3.0
          torchvision                       0.18.0
          tqdm                              4.66.2
          typing_extensions                 4.11.0
          tzdata                            2024.1
          ultralytics                       8.2.5
          urllib3                           2.2.1
          wheel                             0.41.2
          zipp                              3.18.1

## 五、Pytorch 安装

    【注】如果显卡支持CUDA加速，请另行安装。
    
    下述命令安装CPU版，未利用GPU加速。参考Pytorch官网：https://pytorch.org/
    pip install torch torchvision torchaudio

## 六、Pycharm 安装

    PyCharm 官网：https://www.jetbrains.com/pycharm/
    PyCharm 下载地址：https://www.jetbrains.com/pycharm/download/ 选择Community版本即可。
    Pycharm 配置Conda中的Python环境：https://blog.csdn.net/qq_44886601/article/details/136006225

## 七、Tool use helper
    https://ecordiatest.github.io/Ecordia_PrivacyInfoProtect_Helper.html
