Example 6:

1. 依照投影片描述做修改

(1) clone your ncyu-2021 project from Github to the ncyu-2021-ex6 folder

method 1

```
git clone git@github.com:YOUR_ACCOUNT/ncyu-2021
```

method 2

```   
git clone https://github.com/YOUR_ACCOUNT/ncyu-2021
```

[提示]

建議以 method 1 為優先，push 時不需要輸入帳號與密碼，但是 method 2 每次都需要

若使用 method 2 ，但 push 時登入總是失敗，可以試試以下動作 : 

win + R -> control -> 使用者帳戶 -> 認證管理員 -> Windows 認證 -> 移除 github


(2) add and fetch remote repositor

remote url: https://github.com/jrjang/ncyu-2021/

remote name is "official"


(3) push HEAD to origin refs/heads/ex6-2 branch




2. 完成後, 在 ncyu-2021-ex6 資料夾下, 執行以下指令

```
bash <(curl -s https://raw.githubusercontent.com/jrjang/ncyu-2021/ex6/scripts/ex6-test.sh) GITHUB_ACCOUNT
```
