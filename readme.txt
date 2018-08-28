$mkdir learngit           	创建learngit文件夹
$cd  learngit                            转到learngit文件夹目录
$pwd 			显示当前目录
$git init 			使当前目录受控git，变为git可以管理的仓库（存在.git文件夹）

$git add readme.txt		将readme.txt文件提交到stage(暂存区)（并没有提交到仓库的分支master，该分支由git自动创建）
$git commit -m ''xxxx''	将stage中的改动文件提交到仓库分支master，-m是本次改动的说明
$git status 		查看仓库当前状态
$git diff 			查看文件修改内容
$git diff HEAD -- readme.txt	查看工作区和版本库里最新版本readme.txt的区别
                                                      
$git log			查看提交日志
$git log --pretty=oneline	行显示日志
$git reflog		查看历史日志
$git reset --hard HEAD^	回退到上一版本
$git reset --hard HEAD^^	回退到上上一版本
$git reset --hard HEAD~100 	回退到前100个版本
$git reset --hard 1094a	回退到1094a版本

$cat readme.txt		查看readme.txt内容
$git checkout -- readme.txt	撤销工作区中readme.txt文件的修改,其实就是用版本库的替换工作区的
$git reset HEAD readme.txt	将暂存区readme.txt的修改撤销掉

$rm readme.txt		删除工作区的readmen.txt
$git rm readme.txt	$git commit -m "remove readme.txt"	删除版本库中的readme.txt

$git remote add origin git@github.com:wojiaozhupengfei/My_LearnGit 将本地仓库与github的远程仓库关联，origin是远程库的默认名字（可以修改，一般不改）,关联wojiaozhupengfei这个github账户中的My_LearnGit这个远程仓库
$git push -u origin master 	将本地仓库的所有内容推送到远程仓库(master分支推送到github)



