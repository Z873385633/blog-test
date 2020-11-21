# 这是我写的第一篇GitHub博客

我的爱好有
* 听音乐
* 看电影
* 游泳
* 散步
* 写代码（新的爱好hahaha）

### 最常听到的一句话是：比你优秀的人都在学习，你还有什么理由不努力

## git入门学习经历

这个错误
```
### git push -u origin master
error: src refspec main does not match any
error: failed to push some refs to 'github.com:Z873385633/git-demo1.git'
```

多次尝试后
```
### git branch -M main
### git push -u origin main
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 6 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (6/6), 728 bytes | 242.00 KiB/s, done.
Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
To github.com:Z873385633/git-demo1.git
 * [new branch]      main -> main
Branch 'main' set up to track remote branch 'main' from 'origin'.
```
原来是官网更新了，需要Copy两行代码，并且master需要改为main.
