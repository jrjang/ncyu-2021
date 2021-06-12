[HW] 1072912

Example 2:
新增練習項目:revert 實作

1. 先執行以下指令, 會將環境準備好

```
cd $HOME
bash <(curl -s https://raw.githubusercontent.com/jrjang/ncyu-2021/ex2/scripts/ex2-pre/scripts/ex2-pre.sh) GITHUB_ACCOUNT
```

2. 使用git checkout 切換到到 branch ex7 

3. 使用 revert 對Example 2 commit 進行反向執行

4. 觀察git log 可以看到revert commit的動作

5. 要修復工作的話，對剛才revert過的commit在進行一次revert

6. 觀察git log 可以看到又一個新的revert commit的動作，將原始的commit復原

7. 完成後, 在 ncyu-2021-ex2 資料夾下, 執行以下指令

```
bash <(curl -s https://raw.githubusercontent.com/jrjang/ncyu-2021/ex2/scripts/ex2/scripts/ex2-test-test.sh) GITHUB_ACCOUNT
```

