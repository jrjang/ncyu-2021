Example 4:

1. 先執行以下指令, 會準備好 ncyu-2021-ex4 資料夾

```
cd $HOME
bash <(curl -s https://raw.githubusercontent.com/jrjang/ncyu-2021/ex4/scripts/ex4-pre.sh) GITHUB_ACCOUNT
```

2. 切到 ncyu-2021-ex4 資料夾下. 依照投影片描述做修改

3. 修改前可透過git log指令確認當前commit資訊，已得知後續git rebase -i後續所需之commit編號

4. 進行rebase及merge指令時，如遇到conflict，使用git status指令了解conflict原因

5. 解決conflict後須輸入git rebase --continue或git merge --continue以完成已下達之rebase、merge指令

6. 完成並commit後, 在 ncyu-2021-ex4 資料夾下, 執行以下指令

```
bash <(curl -s https://raw.githubusercontent.com/jrjang/ncyu-2021/ex4/scripts/ex4-test.sh) GITHUB_ACCOUNT
```
