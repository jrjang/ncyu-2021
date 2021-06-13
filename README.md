Example 6:

1. 下載自己帳號的 ncyu-2021 project 至 ncyu-2021-ex6 資料夾中
[提示]
有兩種下載方式， SSH 或 HTTPS URL 。建議優先使用 SSH URL 。如果使用 HTTPS URL ，則每次都需要輸入 github 密碼
* SSH URL: git@github.com:GITHUB_ACCOUNT/ncyu-2021
* HTTPS URL: https://github.com/GITHUB_ACCOUNT/ncyu-2021

另外，使用 HTTPS URL 失敗時，可以試試以下動作:

win + R -> control -> 使用者帳戶 -> 認證管理員 -> Windows 認證 -> 移除 github

2. 加入 remote repository
[提示] 
remote name 是 official
remote url 是 https://github.com/jrjang/ncyu-2021

3. 將修改上傳到 github 上，自己的 ncyu-2021 project 的 refs/heads/ex6-2 branch

4. 完成後, 在 ncyu-2021-ex6 資料夾下, 執行以下指令
```
bash <(curl -s https://raw.githubusercontent.com/jrjang/ncyu-2021/ex6/scripts/ex6-test.sh) GITHUB_ACCOUNT
```

5. 到 github ncyu-2021 project 下，切到 ex6 branch 進行 pull request