# How_to_use_Git
## git init; 建立初始git環境
## git clone <網址>; 將遠端資料庫(github)的資料下載至本地
## git config --global user.name <使用者姓名>; 針對單一儲存庫可以不用加 --global
## git config --global user.email <使用者Email>; 針對單一儲存庫可以不用加 --global
## git status; 檢查所有檔案的狀態
## git add .; 將所有檔案上傳到暫存區
## git add <檔案名稱>; 將檔案上傳至暫存區
## git commit -m ""; 提交檔案 "提交訊息"
## git remote add origin <網址>; 需先執行 git init
## git <當前分支> -M <分支名稱>; 將當前分支改至另一分支
## git push origin <分支名稱>; 將變更上傳到github <> --force 強制上傳
## git pull origin <分支名稱>; 將github下載到本機 <> --force 強制上傳