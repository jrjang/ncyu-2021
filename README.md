Example 3:

1. 先執行以下指令, 會準備好 ncyu-2021-ex3 資料夾

```
cd $HOME
bash <(curl -s https://raw.githubusercontent.com/jrjang/ncyu-2021/ex3/scripts/ex3-pre.sh) GITHUB_ACCOUNT
```

2. 切到 ncyu-2021-ex3 資料夾下

3. 編輯 ex3.txt , 將 `return 1` ; 改成 `return -1` ;

4. 暫存修改部份
   提示 : 使用 `git stash` 指令

5. 切換至 ex3 branch , 基於 origin/ex3.
   提示 : 使用 `git checkout` 指令

6. 編輯 ex3.txt, 讓 main function 可以印出 `Hello World`

7. 將修改加入 Git tree
   提示 : 使用 `git add`, `git commit` 指令

8. 完成並 commit 後, 在 ncyu-2021-ex3 資料夾下, 執行以下指令

```
bash <(curl -s https://raw.githubusercontent.com/jrjang/ncyu-2021/ex3/scripts/ex3-test.sh) GITHUB_ACCOUNT
```
