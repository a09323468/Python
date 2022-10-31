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
       git remote add origin(別名) https://github.com/a09323468/filename.git(HTTPS)
       git remote -v >>查看遠端連結有哪些
       (git remote add XXname [url]) >>添加新的需要跟踪的遠程倉庫
       (git remote rm XXname) >>删除該倉庫
       (git fetch XXname) >>在本地倉庫獲取遠程倉庫的訊息
       
### Step4：
       git add hello.txt >>加到暫存區
       git config --global user.email "your@gmail.com"
       git config --global user.name "Your Name" >>set your account's default identity
       git commit -m "first commit test" >>將被追蹤的檔案提交至儲存庫 
       git push -u origin main >>將 main 分支推送到 origin 伺服器上(add > commit > push)
       
### Step5：上傳本地修改後的檔案到github
       git status
       git add hello.txt >>把修改的檔案提交到版本庫放入暫存
       git commit -m "modify" >>再把暫存區的提交到本地的版本庫
       git pull origin main  >>git pull將遠端伺服器 origin 的 main 分支拉取過來，與本地的 main 分支合併。
       git push -u origin main >>將本地的修改後的內容提交到遠端倉庫
       
### Step6：上傳超過100MB檔案到github
       Reference From ： https://blog.csdn.net/AshleyXM/article/details/104766893
       git lfs install
