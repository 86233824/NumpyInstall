# 总结一下我在安装Numpy时遇到的一些小问题
更新pip：

        https://pypi.python.org/pypi/pip 下载最新版本的pip

        python3.5更新pip命令    python3 -m pip install --upgrade pip    （我的Python3.5名字改成了python3）

        python2.7更新pip命令    python -m pip install --upgrade pip          

        更新成功会显示 successfully installed pip-8.1.2

 

下载Numpy的whl文件：

        http://www.lfd.uci.edu/~gohlke/pythonlibs/

 

cmd的目录cd到whl文件夹下输入以下命令：

        python3 -m pip install 文件名.文件格式

                python3 -m pip install numpy-1.11.1+mkl-cp35-cp35m-win_amd64.whl

        python2 同理

                python -m pip install numpy-1.11.1+mkl-cp27-cp27m-win_amd64.whl

        安装成功显示 Successfully installed numpy-1.11.1+mkl
