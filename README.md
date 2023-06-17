## Git 指令
    - git version : 查詢版本號

    - 全域資訊
        - git config --global user.name (username) : 設定使用者名稱
        - git config --global user.email (email)   : 設定使用者信箱
        - git config --list : 設定資訊

    - 區域資訊
        - git config user.name (name)
        - git config user.email (email)

    - git init : 開始GIT程式庫

    - cat .git/config : 本地資料夾git config 資訊

    - git add (filename) : 加入檔案至倉庫區
        - git add . : 將全部U狀態的檔案-> Added

    - git checkout (filename) : 回復修改 A->M
        - git checkout . : 全部檔案回復修改(確認修改 git add .)

    - git restore (filename) : 將檔案狀態 A->U
        - 檔案刪除後也可以用git restore (filename) 回復檔案

    - git status : 查看git 狀態
        - git檔案模式: U->Unstage A->Added M->Modified

    - tree .git : 樹狀圖查看.git

    - git ls-files : 顯示git 檔案
        - git ls-files -s : 顯示git 檔案 & SHA-1編碼

    - git commit -m "(commit name)" : 提交並設定紀錄點
        - git commit --amend : 修改最後一次的commit
            - esc : normal/insert 模式
            - :w 寫入=儲存
            - :q 離開程式
            - :! 強制執行
            - :q! 回到上一個動作
            - i insert模式
            - a append
            - o new line

    - git log : 顯示commit 紀錄
        - git log --oneline : 單行顯示紀錄
        - git log --stat : 顯示詳細修改資訊
        - git log --graph : 樹狀圖顯示log 紀錄
        - git shortlog : 只顯示commit 名稱

    - 
    

