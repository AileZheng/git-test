terminal 指令:
ls:顯示其他檔案
cd:可以移動到指定資料夾 (cd src)
cd..:回到前一個資料夾 (cd..)


git:可以看到 git 的相關指令
git config --global user.name:查詢指令
git config --global user.email:查詢指令
git init:進行初始化
git status:檔案狀態
git add:將某個檔案加入 git 管理(也可以用檔案旁邊的工具 "+")
git add .:將全部的檔案加入 git 管理
git commit:儲存，進入 vim 介面(很不友善，shift+: q 跳出去)
git commit -m "要記錄的訊息":這一次 git commit 的訊息
git log:查看紀錄(如果紀錄很多可以按 q 跳出去)

ls -a:看到隱藏的檔案
git remote add origin https://github.com/AileZheng/git-test.git
git remote
:加入到這個位置

git push origin main:
git push -u origin main:
git branch:查我們現在所在的分支(主分支:main/master)
