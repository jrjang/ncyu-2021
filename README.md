Example 5:

1. 先執行以下指令, 會將環境準備好

```
cd $HOME
bash <(curl -s https://raw.githubusercontent.com/jrjang/ncyu-2021/ex5/scripts/ex5-pre.sh) GITHUB_ACCOUNT
```

2. 切到 ncyu-2021-ex5 資料夾下

3. 將 "Example 5: 2" 這筆 commit reset 成 unstaging everything

4. 清除所有未追蹤檔案

5. 完成後 "不用commit", 在 ncyu-2021-ex5 資料夾下, 執行以下指令

```
bash <(curl -s https://raw.githubusercontent.com/jrjang/ncyu-2021/ex5/scripts/ex5-test.sh) GITHUB_ACCOUNT
```
