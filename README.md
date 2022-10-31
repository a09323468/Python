Practice and learn 
Resourse： https://github.com/jackfrued/Python-100-Days/tree/master/Day01-15 

### Step1：
       download git, create a file, git bash here

### Step2：
        git init >>初始化
       echo "Hello!" > hello.txt  >>(建立一個檔案)
       vim hello.txt(開啟舊檔), i(insert), esc(escape), :wq(store and quit)  >>hello.txt裡面輸入文字，git status(查看裡面多了哪些資料)
       
### Step3：
       connect with github  >>本地端與遠端github連結
       git remote add track(別名) https://github.com/a09323468/Tooling_Track_Tstar.git(HTTPS)
       git remote -v >>查看遠端連結有哪些
       
### Step4：
       git add hello.txt >>加到暫存區
       git config --global user.email "you@example.com"
       git config --global user.name "Your Name" >>set your account's default identity
       git commit -m "first commit test" >>將被追蹤的檔案提交至儲存庫 
       git push -u track master >>將 master 分支推送到 track 伺服器上
       
### Step5：上傳本地修改後的檔案到github
       git status
       git add hello.txt >>把修改的檔案提交到版本庫放入暫存
       git commit -m "modify" >>再把暫存區的提交到本地的版本庫
       git pull track master  >>git pull將遠端伺服器 track 的 master 分支拉取過來，與本地的 master 分支合併。
       git push -u track master >>將本地的修改後的內容提交到遠端倉庫
