<!--
 * @Descripttion:
 * @version:
 * @Author: xudajie
 * @Date: 2022-01-20 15:25:52
 * @LastEditors: xudajie
 * @LastEditTime: 2022-01-20 16:37:33
-->

git init 初始化仓库
git status 查看仓库中文件的状态，untracked（未跟踪，没上传到 git），unmodify（修改）， modified（修改）， staged（暂存区）
git status -s （简写）
git add xx.html 跟踪文件
git commit -m "提交添加文字描述"
git checkout -- xx.html 撤销对 xx.html 文件的修改，谨慎使用
git add . 暂存多个文件
git reset HEAD index.html 移除上次跟踪的文件（git add index.html）
