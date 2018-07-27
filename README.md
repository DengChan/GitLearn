# GitLearn
<p>
<b>本地建立仓库</b></br>

$ git init</br>

<b>连接远程仓库</b></br>

$ git remote add ml git@github.com:DengChan/MLStudy.git</br>

<b>克隆到本地(ml 为连接名)</b></br>

$ git pull ml master</br>

<b>建立分支</b></br>

$ git branch feature</br>

<b>三部曲</b></br>

$ git add xxxx.xx</br>
$ git commit -m 'message'</br>
$ git push -u ml feature </br>

<b>更换分支</b>

$ git checkout feature</br>
  
<b>合并分支</b></br>

$ git merge feature</br>

<b>删除分支</b></br>

$ git branch -d feature</br>

<b>撤销add</b></br>
$ git reset head   #撤销上一次的所有add</br>
$ git reset head [文件名] #撤销指定文件add</br>
</p>
