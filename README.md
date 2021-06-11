Example 6:

1.下載自己帳號的 ncyu-2021 project 至 ncyu-2021-ex6 資料夾中
[提示] ncyu-2021 project 位置是 ``` git@github.com:YOUR_ACCOUNT/ncyu-2021 ```
```
git clone git@github.com:YOUR_ACCOUNT/ncyu-2021
```
```
git clone git clone https://github.com/YOUR_ACCOUNT/ncyu-2021
```  
2.加入 remote repositoiry 
``` 
git remote add official https://github.com/jrjang/ncyu-2021
``` 
3.更新 remote repositoiry 底下 branch 的修改內容
```
git fetch origin
``` 
4. 完成後 , 在 ncyu-2021-ex6 資料夾下 , 執行以下指令
```
bash <(curl -s https://raw.githubusercontent.com/jrjang/ncyu-2021/ex6/scripts/ex6-test.sh) GITHUB_ACCOUNT
```
