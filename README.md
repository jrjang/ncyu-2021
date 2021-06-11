新增練習題目 (使用 ex2 來做練習)

練習使用 reset :

1. 先執行以下指令, 會準備好 ncyu-2021-ex2 資料夾

```
cd $HOME
bash <(curl -s https://raw.githubusercontent.com/jrjang/ncyu-2021/ex2/scripts/ex2-pre.sh) GITHUB_ACCOUNT
```

2. 切到 ncyu-2021-ex2 資料夾

3. 使用 git log 觀看紀錄

```
$ git log --oneline
025ab5a (HEAD, origin/ex2) [Example 2] 1072911
bf839d0 (official/ex2) Example 2
```

4. 使用 --hard reset 刪除 commit

```
$ git reset --hard HEAD~1
HEAD is now at bf839d0 Example 2
```

5. git log 就可看到 025ab5a 這筆 commit 已被刪除

```
$ git log --oneline
bf839d0 (HEAD, official/ex2) Example 2
```

6. 再次使用 reset 來恢復 commit

```
$ git reset --hard 025ab5a
HEAD is now at 025ab5a [Example 2] 1072911
```

7. git log 就可看到已恢復原本的狀態

```
$ git log --oneline
025ab5a (HEAD, origin/ex2) [Example 2] 1072911
bf839d0 (official/ex2) Example 2
```

8. 完成並commit後, 在 ncyu-2021-ex2 資料夾下, 執行以下指令

```
bash <(curl -s https://raw.githubusercontent.com/jrjang/ncyu-2021/ex2/scripts/ex2-test.sh) GITHUB_ACCOUNT
```
