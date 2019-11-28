## git测试

1. ```git init ```：初始化git目录
2. ```git add README.md```：添加文件到暂存区
3. ```git commit -m "这是注释"``` ：提交到本地仓库
4. ```git status```：查看提交状态
5. ```git diff README.md```：查看不同
6. ```git log```：查看提交记录，一行查看 ```git log --pretty=oneline```
7. ```git reset --hard HEAD^```：回退到上一个版本，```git reset --hard HEAD~100```，回退100个版本
8. ```git reflog```：查看版本号
9. ```git reset --hard 6fcfc89```：恢复到某个版本
10. ```git checkout -- README.md```：撤销工作区的修改