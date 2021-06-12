Example 2:

1. 先執行以下指令, 會準備好 ncyu-2021-ex2 資料夾

```
cd $HOME
bash <(curl -s https://raw.githubusercontent.com/jrjang/ncyu-2021/ex2/scripts/ex2-pre.sh) GITHUB_ACCOUNT
```

2. 切到 ncyu-2021-ex2 資料夾下. 依據 data/0001-ex2.patch 做相對應的修改

```
cd ncyu-2021-ex2
cd data
vim 0001-ex2.patch
```
[補充] 可以利用Tab鍵少打很多字
[補充] 當你使用vim時,如果要修改要先按"Insert"鍵
       如果修改完畢或者沒有要修改,可以按"Esc"鍵加上":wq",就能離開vim

3. 完成並commit後, 在 ncyu-2021-ex2 資料夾下, 執行以下指令

```
bash <(curl -s https://raw.githubusercontent.com/jrjang/ncyu-2021/ex2/scripts/ex2-test.sh) GITHUB_ACCOUNT
```
