# 如何将本地的项目推送到GitHub上
***
* ## 首先在本地创建ssh key
   $ ssh-keygen -t rsa -C "yetohello@163.com"  

* ### 验证是否成功，在git bash下输入  

    $ ssh -T git@github.com

* ## 克隆github库到本地：

     $ git clone git@github.com:yetohelo/test.git  

* ### 禁止转换字符  （CRLF FL 错误）：  
      $ git config --gobal core.autocrlf false  
      $ git config core.autocrlf false  
      
* ## 添加 到缓存区：

   $ git add .
   $ git commit -m "content"

* ## 推送到GitHub库：

    $ git push origin master  

* ## 其他参考代码：
       进行代码合并
       $ git pull --rebase origin master  
       连接到git库
       $ git remote add origin git@github.com:yetohello/yetohello.io.git  
       第一次提交，全部上传
       $ git push -u origin master  
    
