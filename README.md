# project

## 載入新專案
1.在github專案下載zip檔
<img width="100%" alt="image" src="https://github.com/lalalag27/project/assets/119072843/e9fb3a4b-a48f-4955-8de0-10b5f133d205">
2.在ftp建立站台，主機:副域名/使用者:廠商
密碼:要看是新專案還是舊專案選密碼<資料都在ftp試算表>
<img width="100%" alt="image" src="https://github.com/lalalag27/project/assets/119072843/b2d0de36-5389-4809-a17a-3fd831db7503">
3.下載.env
<img width="970" alt="image" src="https://github.com/lalalag27/project/assets/119072843/14b4410d-0533-4f78-9c5f-82772e906451">
4.打開wampserver
5.依照專案的.env dbnme設定資料庫名稱
<img width="1058" alt="image" src="https://github.com/lalalag27/project/assets/119072843/7f2042ab-0e98-48dc-9d5b-93f8800f2e64">
<img width="1023" alt="image" src="https://github.com/lalalag27/project/assets/119072843/0b88d1f4-6fec-4041-b098-ef036b20cac7">
6.新增使用者帳號並執行
<img width="1055" alt="image" src="https://github.com/lalalag27/project/assets/119072843/b23dfa79-cfc9-47c1-990f-447ed4181eb0">
7.將sql檔案上傳到資料庫<br>
8.在專案的終端機輸入
```
npm i
compoder i
php artisan migrate:fresh --seed
```
