# CS336-Stanford
斯坦福计算机课程CS336

这里是codespace：🚀 “在云端运行的 VS Code + Linux + Git 环境”。
只提供CPU，没有GPU，环境最多保持30天。
可以将所需要点环境都写进requirements.txt。
（对于mac用户很友好）

### 检查codespace环境
刚进来用的是初始的global环境，并不是conda里的python环境

激活conda，配置shell
conda init | source ~/.bashrc 用户名前出现"(bash)"

python --version
conda env list *所在就是当前环境

1. 安装 Jupyter 与内核支持
pip install ipykernel jupyter

2. 将当前 Python 注册成一个可选内核
python -m ipykernel install --user --name cs336 --display-name "Python (cs336)"