Example 3:

1. 先執行以下指令, 會準備好 ncyu-2021-ex3 資料夾

```
cd $HOME
bash <(curl -s https://raw.githubusercontent.com/jrjang/ncyu-2021/ex3/scripts/ex3-pre.sh) GITHUB_ACCOUNT
```

2. 切到 ncyu-2021-ex3 
2.1 編輯 ex3.txt. 將 return 1; 改成 return -1;
2.2 暫存修改部份 (提示: git stash)
2.3 請從origin/ex3 Checkout至ex3 branch(提示: git checkout) ---修改過
2.4 編輯 ex3.txt, 讓 main function 可以印出 Hello World
2.5 將修改加入 Git tree (提示: git add, git commit)


3. 完成並commit後, 在 ncyu-2021-ex3 資料夾下, 執行以下指令

```
bash <(curl -s https://raw.githubusercontent.com/jrjang/ncyu-2021/ex3/scripts/ex3-test.sh) GITHUB_ACCOUNT
```
