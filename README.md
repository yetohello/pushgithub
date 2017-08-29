首先在本地创建ssh key

$ ssh-keygen -t rsa -C "yetohello@163.com"

# github_teach
克隆github库到本地：

   $ git clone git@github.com:yetohelo/test.git

   禁止转换字符  （CRLF FL 错误）：
      $ git config --gobal core.autocrlf false 
      $ git config core.autocrlf false
      
添加 到缓存区：

   $ git add .
   $ git commit -m "content"

推送到GitHub库：

    $ git push origin master

其他参考代码：
     $ git pull --rebase origin master
     $ git push -u origin master
     $ git remote add origin git@github.com:yetohello/yetohello.io.git
