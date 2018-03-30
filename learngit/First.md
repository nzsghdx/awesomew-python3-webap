这东西也没必要死记吧，什么时候忘了搜一下就好了，但是什么都不懂连搜都不知道怎么搜，有必要了解一下。

设置本地账户：

- git config --global user.name 'github的名字'
- git config --global user.email 'github的注册邮箱'
  >绑定了多个邮箱的话，不知道是不是使用其他的邮箱也行，没试过。

本地生成秘钥：

- ssh-keygen -t rsa -C 'Email Address'

测试是否连接成功：

- ssh -T git@github.com

关联本地仓库和远程仓库：

- git remote add origin Address

第一次推送：

- git push -u origin master
  >人家说加上`-u`参数会自动关联
