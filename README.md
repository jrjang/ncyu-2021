Example 1:

1. 執行以下指令

```
cd $HOME
mkdir ncyu-2021-ex1		# 建立 ncyu-2021-ex1 資料夾
cd ncyu-2021-ex1
git init			# 執行 git init
echo "Example 1" > ex1.txt
```

2. 將 ex1.txt 加入 Git local repository 並 commit

[注意] 只能有"一筆"commit
便會出現Your commit number is more than 1 此時可以到使用者資料夾將整個ncyu-2021-ex1檔案刪除再重新操作即可

3. 在 ncyu-2021-ex1 資料夾下, 執行以下指令


```
bash <(curl -s https://raw.githubusercontent.com/jrjang/ncyu-2021/ex1/scripts/ex1-test.sh) GITHUB_ACCOUNT
```

GITHUB_ACCOUNT: github帳號
