# Some tips for research and coding

## 科研起步必读
- 1.帝国理工博士手册（Doctoral Milestones）
https://www.doc.ic.ac.uk/research/phd/phdmatters/handbook_PhD_2018.pdf
- 2.Karpathy博士经验
http://karpathy.github.io/2016/09/07/phd/ （翻译https://m.sohu.com/a/125259752_465975/?pvid=000115_3w_a）
- 3.陈天奇科研十年
https://zhuanlan.zhihu.com/p/74779853
- 4.王一科研
ideahttps://mp.weixin.qq.com/s/e78zRIgdEtGLKiqYcRJLHQ
- 5.王赟 我的八年博士生涯
https://zhuanlan.zhihu.com/p/50597445
- 6.李沐
博士这五年 - 知乎
https://zhuanlan.zhihu.com/p/25099638
- 7.毕业撒花 https://mp.weixin.qq.com/s/j8EuhusTNlE60m8IC4ftGA


## Github
- 历史
- 创建账号
- 建立Repository
- git init
- git add xxx.txt
- git add -A
- git commit -m "hahahah"
- git push
- git clone https://github.com/account/repository.git
- 如何在网站上修改
- git pull
- git branch

## Screen
- screen -S name 创建screen，并进入
- screen -ls 查看screen列表
- screen -r name 进入screen
- ctrl+A+D 退出当前screen
- screen -d name 关闭screen
- screen -X -S name kill 删除screen

## GPU
nvidia-smi
sudo fuser -v /dev/nvidia*
sudo kill -9 PID

CUDA_VISIBLE_DEVICES=0 python xxx.py
CUDA_VISIBLE_DEVICES=0,1 python xxx.py
CUDA_VISIBLE_DEVICES=“” python xxx.py
python xxx.py > train.log &

