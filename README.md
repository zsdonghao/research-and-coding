# Some tips for research and coding

欢迎大家一起丰富内容～～～😄

## 0. 论文列表
- [arxiv-sanity yearly top](http://www.arxiv-sanity.com/top?timefilter=year&vfilter=all)
- ICLR2020 / [openreview](https://openreview.net/group?id=ICLR.cc/2020/Conference)
- [NIPS各年](https://papers.nips.cc)
- [NIPS2019](https://nips.cc/Conferences/2019/Schedule?type=Poster)
- [ICML2019](https://icml.cc/Conferences/2019/Schedule?type=Poster) / [oral video](https://www.youtube.com/results?search_query=icml+2019+oral)
- [ICLR2019](https://iclr.cc/Conferences/2019/Schedule?type=Poster) / [goodfellow talk](https://www.youtube.com/watch?v=sucqskXRkss) [other talks](https://www.youtube.com/watch?v=Rrf6P9tFxas)
- [ACL2019](http://www.acl2019.org/EN/program.xhtml)
- [AAAI2019](https://aaai.org/Conferences/AAAI-19/wp-content/uploads/2018/11/AAAI-19_Accepted_Papers.pdf)
- [CVPR2019](http://openaccess.thecvf.com/CVPR2019.py) / [oral list](https://github.com/hoya012/CVPR-2019-Paper-Statistics/blob/master/2019_cvpr/cvpr_2019_oral.csv) / [oral app video](https://www.youtube.com/watch?v=ts4ogdJW4_8) [oral dl video](https://www.youtube.com/watch?v=PzALQZOy09c) 网上有很多公开会议视频
- [ICCV2019](http://openaccess.thecvf.com/ICCV2019.py) / [paper分组](http://iccv2019.thecvf.com/program/main_conference)
- [SIGGRAPH2019 Technical Papers Fast Forward](https://www.youtube.com/watch?v=iDUNc5YRtzk)/ [Paper List](http://kesen.realtimerendering.com/sig2019.html)
- [DeepMind Research](https://deepmind.com/research) 看AI都有什么方向
- [NIPS 19 Subject Areas](https://nips.cc/Conferences/2019/PaperInformation/SubjectAreas) 看DL都有什么方向
- [CVPR 19 Program Guide](http://cvpr2019.thecvf.com/files/CVPR_2019_Program_Guide.pdf) 看CV都有什么方向

## 1. 科研起步

### 必读文章
- 1.[Karpathy-博士经验](http://karpathy.github.io/2016/09/07/phd/) [(翻译)](https://m.sohu.com/a/125259752_465975/?pvid=000115_3w_a) 重点
- 2.[陈天奇-科研十年](https://zhuanlan.zhihu.com/p/74779853)
- 3.[王一-科研idea](https://mp.weixin.qq.com/s/e78zRIgdEtGLKiqYcRJLHQ)
- 4.[王赟-我的八年博士生涯](https://zhuanlan.zhihu.com/p/50597445)
- 5.[李沐-博士这五年](https://zhuanlan.zhihu.com/p/25099638)
- 6.[毕业撒花](https://mp.weixin.qq.com/s/j8EuhusTNlE60m8IC4ftGA)
- 7.[帝国理工-博士手册（Doctoral Milestones）](https://www.doc.ic.ac.uk/research/phd/phdmatters/handbook_PhD_2018.pdf)
- 8.[Opinionated guide ML research](http://joschu.net/blog/opinionated-guide-ml-research.html)

### 信息收集
- 1.[Google Scholar 如何查询相关文章](https://scholar.google.co.uk/scholar?hl=en&as_sdt=0%2C5&q=semantic+image+synthesis+via+adversarial+learning&btnG=)
- 2.[Google Scholar 如何follow研究者](https://scholar.google.co.uk/citations?user=xLFL4sMAAAAJ&hl=en)
- 3.[arXiv](https://arxiv.org) 未发表文章共享平台
- 4.[arXiv-sanity](http://www.arxiv-sanity.com) 更好地搜索arXiv
- 5.[sci-hub](https://sci-hub.se) 免费下载所有文章，例如输入这个：https://ieeexplore.ieee.org/document/8070331/
- 6.[Zlibrary](https://b-ok.cc/s/deep%20reinforcement%20learning) 免费下载书
- 7.[mendeley 文章整理APP](https://www.mendeley.com)


### 其他
- 1.[蓝灯](https://github.com/getlantern/forum) 邀请码 Y238YKH (现在不行了，用 摘星 吧)
- 2.[谷歌学术 镜像](http://scholar.hedasudi.com)
- 3.[无license下载paper](https://sci-hub.se)

## 2. Github
- Github历史和目的
- 创建账号
- 建立Repository
- git init 初始化
- 随便添加一个.txt文件
- git diff 查看当前本地修改了什么
- git diff xxx 查看xxx里面修改了什么
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
- **练习：建立自己的个人主页** [我的例子](https://github.com/zsdonghao/zsdonghao.github.io)

## 3. 其他Coding
- [YAPF](https://github.com/google/yapf) 一个Python代码格式自动调整工具
  - yapf xxx.py 显示如何调整一个py文件
  - yapf -i xxx.py 调整一个py文件，并覆盖原文件
  - yapf -i --recursive foldername 调整一个文件夹里的py文件，并覆盖原文件
- [Python命名风格](https://www.jianshu.com/p/a793c0d960fe)
  - 类 HelloClass
  - 函数 hello_function
  - 等
- 清华源, 镜像加速安装包
  - pip install -i https://pypi.tuna.tsinghua.edu.cn/simple some-package
- 其他
  - [吴润迪整理](https://github.com/ChrisWu1997/EfficientResearchWork)
  - [Python Best Practices Guidebook](https://docs.python-guide.org/)

## 4. GPU
- 目的
- nvidia-smi 查看GPU使用情况
- watch -n 1 nvidia-smi：每秒钟刷新GPU使用情况
- sudo fuser -v /dev/nvidia* 查看GPU使用者
- sudo kill -9 PID 杀掉进程
- CUDA_VISIBLE\_DEVICES=0 python xxx.py 指定GPU0
- CUDA_VISIBLE\_DEVICES=0,1 python xxx.py 指定GPU0和1
- CUDA_VISIBLE\_DEVICES=“” python xxx.py 不使用GPU
- python xxx.py > train.log &    把输出放入train.log（>）; 不显示输出（&）
- CPU & GPU
- top
- htop

## 5. Screen
- 目的：关闭当前Terminal/命令窗口，程序依然进行。
- screen -S name 创建screen，并进入
- screen -ls 查看screen列表
- screen -r name 进入screen
- ctrl+A+D 退出当前screen
- screen -d name 关闭screen
- screen -X -S name kill 删除screen

## 6. Virtualenv
- 目的
- [Installation](https://tensorlayer.readthedocs.io/en/latest/user/installation.html)
- pip3 install virtualenv 安装virtualenv
- virtualenv env 新建环境
- source env/bin/activate 进入环境
- deactivate 退出环境

## 7. 文档
- 目的
- [Markdown](https://guides.github.com/features/mastering-markdown/)
- [Readthedoc](https://readthedocs.org)
	- https://github.com/tensorlayer/tensorlayer/tree/master/docs
	- https://tensorlayer.readthedocs.io
- [RST and Sphinx syntax](https://thomas-cokelaer.info/tutorials/sphinx/rest_syntax.html)

## 8. 远程连接
- MacOS - [Cyberduck](https://cyberduck.io)
- Windows - [MobaXterm](https://mobaxterm.mobatek.net)
- [PyCharm](https://www.jetbrains.com/pycharm/)

## 9. TensorLayer
- [Installation](https://tensorlayer.readthedocs.io/en/latest/user/installation.html)
- [Dynamic and Static Models](https://tensorlayer.readthedocs.io/en/latest/user/get_start_model.html)
- [Advanced Features](https://tensorlayer.readthedocs.io/en/latest/user/get_start_advance.html)
- [Data Augmentation](https://tensorlayer.readthedocs.io/en/latest/modules/prepro.html#python-can-be-fast)
- [Basic Tutorials](https://github.com/tensorlayer/tensorlayer/tree/master/examples/basic_tutorials) CIFAR10 has data augmentation
- [A Good Project Template](https://github.com/tensorlayer/srgan)
- RL Tutorials [for Research](https://github.com/tensorlayer/tensorlayer/tree/master/examples/reinforcement_learning) / [for Production](https://github.com/tensorlayer/RLzoo)

## 10. Machine Learning / System / ...
- [zsdonghao/deep-learning-note](https://github.com/zsdonghao/deep-learning-note)
- [Distributed Training](https://blog.skymind.ai/distributed-deep-learning-part-1-an-introduction-to-distributed-training-of-neural-networks/) 
- [机器学习-白板推导系列](https://search.bilibili.com/all?keyword=机器学习-白板推导系列&from_source=nav_search)
- [TingFlow](https://github.com/tqchen/tinyflow) 教学性DL框架
- [papers with code](https://paperswithcode.com/sota)

## 11. Publishing Paper
- [Conference DDL](https://aideadlin.es/?sub=ML,CV,NLP,RO,SP,DM)
- [Grammarly](https://app.grammarly.com) 查语法错误
- [Overleaf](http://overleaf.com) 协同编辑
- LaTeX: [MacTex](http://www.tug.org/mactex/downloading.html) 
- Best tool for using LaTeX locally: [VSCode](https://code.visualstudio.com/) + [LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop)
