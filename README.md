# Some tips for research and coding

欢迎大家一起丰富内容～～～😄

## 1. 科研起步

### 必读文章
- 1.[Karpathy-博士经验](http://karpathy.github.io/2016/09/07/phd/) [(翻译)](https://m.sohu.com/a/125259752_465975/?pvid=000115_3w_a) 重点
- 2.[陈天奇-科研十年](https://zhuanlan.zhihu.com/p/74779853)
- 3.[王一-科研idea](https://mp.weixin.qq.com/s/e78zRIgdEtGLKiqYcRJLHQ)
- 4.[王赟-我的八年博士生涯](https://zhuanlan.zhihu.com/p/50597445)
- 5.[李沐-博士这五年](https://zhuanlan.zhihu.com/p/25099638)
- 6.[毕业撒花](https://mp.weixin.qq.com/s/j8EuhusTNlE60m8IC4ftGA)
- 7.[帝国理工-博士手册（Doctoral Milestones）](https://www.doc.ic.ac.uk/research/phd/phdmatters/handbook_PhD_2018.pdf)

### 信息收集
- 1.[Google Scholar 如何查询相关文章](https://scholar.google.co.uk/scholar?hl=en&as_sdt=0%2C5&q=semantic+image+synthesis+via+adversarial+learning&btnG=)
- 2.[Google Scholar 如何follow研究者](https://scholar.google.co.uk/citations?user=xLFL4sMAAAAJ&hl=en)
- 3.[arXiv](https://arxiv.org)
- 4.[arXiv-sanity](http://www.arxiv-sanity.com)
- 5.[sci-hub](https://sci-hub.se) 例如输入这个：https://ieeexplore.ieee.org/document/8070331/
- 6.[mendeley 文章整理APP](https://www.mendeley.com)

### 其他
- 1.[蓝灯](https://github.com/getlantern/forum) 邀请码 Y238YKH
- 2.[旋风 APP](https://www.lcdhgy.com)

## 2. Github
- Github历史和目的
- 创建账号
- 建立Repository
- git init 初始化
- git add xxx.txt 添加xxx.txt到git
- git add -A 添加所有文件到git
- git commit -m "hahahah" 添加注释
- git push 上传更新
- git clone https://github.com/account/repository.git
- git status 查询状态
- 如何在网站上修改
- git pull 与Github同步
- git branch 查看branch
- git branch -a 查看所有branch
- git branch new 创建branch名为new
- git checkout new 进入new branch
- git checkout master 返回主branch
- git checkout -b new2 创建并进入branch名为new2
- 修改branch后，commit到Github上，如何在github上发起Push Request
- .gitignore 自定义不能被添加的文件
- 添加collaborator
- 新建organization
- **练习：建立自己的个人主页**

## 3. GPU
- 目的
- nvidia-smi 查看GPU使用情况
- sudo fuser -v /dev/nvidia* 查看GPU使用者
- sudo kill -9 PID 杀掉进程
- CUDA_VISIBLE\_DEVICES=0 python xxx.py 指定GPU0
- CUDA_VISIBLE\_DEVICES=0,1 python xxx.py 指定GPU0和1
- CUDA_VISIBLE\_DEVICES=“” python xxx.py 不使用GPU
- python xxx.py > train.log &    把输出放入train.log（>）; 不显示输出（&）
- CPU & GPU
- top
- htop

## 4. Screen
- 目的：关闭当前Terminal/命令窗口，程序依然进行。
- screen -S name 创建screen，并进入
- screen -ls 查看screen列表
- screen -r name 进入screen
- ctrl+A+D 退出当前screen
- screen -d name 关闭screen
- screen -X -S name kill 删除screen

## 5. Virtualenv
- 目的
- [Installation](https://tensorlayer.readthedocs.io/en/latest/user/installation.html)
- pip3 install virtualenv 安装virtualenv
- virtualenv env 新建环境
- source env/bin/activate 进入环境
- deactivate 退出环境

## 6. 文档
- 目的
- [Markdown](https://guides.github.com/features/mastering-markdown/)
- [Readthedoc](https://readthedocs.org)
	- https://github.com/tensorlayer/tensorlayer/tree/master/docs
	- https://tensorlayer.readthedocs.io
- [RST and Sphinx syntax](https://thomas-cokelaer.info/tutorials/sphinx/rest_syntax.html)

## 7. 远程连接
- MacOS - [Cyberduck](https://cyberduck.io)
- Windows - [MobaXterm](https://mobaxterm.mobatek.net)
- [PyCharm](https://www.jetbrains.com/pycharm/)

## 8. TensorLayer
- [Installation](https://tensorlayer.readthedocs.io/en/latest/user/installation.html)
- [Dynamic and Static Models](https://tensorlayer.readthedocs.io/en/latest/user/get_start_model.html)
- [Advanced Features](https://tensorlayer.readthedocs.io/en/latest/user/get_start_advance.html)
- [Data Augmentation](https://tensorlayer.readthedocs.io/en/latest/modules/prepro.html#python-can-be-fast)
- [Basic Tutorials](https://github.com/tensorlayer/tensorlayer/tree/master/examples/basic_tutorials) CIFAR10 has data augmentation
- [A Good Project Template](https://github.com/tensorlayer/srgan)

## 9. Deep Learning 等
- [NIPS 19 Subject Areas](https://nips.cc/Conferences/2019/PaperInformation/SubjectAreas)
- [CVPR 19 Program Guide](http://cvpr2019.thecvf.com/files/CVPR_2019_Program_Guide.pdf)
- [CVPR 19 Paper list](http://openaccess.thecvf.com/CVPR2019.py) / [oral list](https://github.com/hoya012/CVPR-2019-Paper-Statistics/blob/master/2019_cvpr/cvpr_2019_oral.csv)
- [SIGGRAPH 19 Technical Papers Fast Forward](https://www.youtube.com/watch?v=iDUNc5YRtzk)/ [Paper List](http://kesen.realtimerendering.com/sig2019.html)
- [zsdonghao/deep-learning-note](https://github.com/zsdonghao/deep-learning-note)
- [Distributed Training](https://blog.skymind.ai/distributed-deep-learning-part-1-an-introduction-to-distributed-training-of-neural-networks/)
- [TingFlow](https://github.com/tqchen/tinyflow) 教学性DL框架

## 10. Publishing Paper
- [Conference DDL](https://aideadlin.es/?sub=ML,CV,NLP,RO,SP,DM)
- [Grammarly](https://app.grammarly.com) 查语法错误
- [Overleaf](http://overleaf.com) 协同编辑
- LaTeX: [MacTex](http://www.tug.org/mactex/downloading.html) 
- Best tool for using LaTeX locally: [VSCode](https://code.visualstudio.com/) + [LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop)
