

jkg 接著將剛剛建立檔案，新增add 進你想 提交commit（或儲存）的修改。

$ git add readme.txt

最後，將那些修改 提交commit 到 程式庫repository 的歷史紀錄當中，並隨附上一個簡短的異動說明。

$ git commit -m "<your commit message>"

步驟：進行更多修改

現在在多寫一行文字到 readme.txt 之中並存檔。

在終端機裡你可以查看有那些 差異diff 存在於現在的檔案以及上次你所 提交commit 的檔案之間。

$ git diff
