# todolistSequelize
一個使用 Node.js + Express 打造的todolist網站

[Demo Website](http://localhost:3001/)

## 專案畫面
![image]([https://github.com/WeiWayne1030/todolistSequelize/blob/1316a190dec2e27c6c41f4588c1a63fe6f422949/img/%E6%88%AA%E5%9C%96%202023-05-12%20%E4%B8%8B%E5%8D%888.25.21.png])


## Features - 產品功能
* 使用者可以註冊帳號：登入與登出以及註冊過程中的錯誤或警告都有給予使用者提示。以下功能皆須登入後才能使用。
* 使用者可以瀏覽所有待辦事項。
* 使用者可以新建待辦事項：待辦事項是必填欄位。
* 使用者可以刪除特定待辦事項。
* 使用者可以修改特定待辦事項。

## Environment SetUp - 環境建置

1. [Node.js](https://nodejs.org/en/)
2. [MongoDB4.0 以上]（https://www.mongodb.com/try/download/community）

## Installing - 專案安裝流程

1. 打開你的 terminal，Clone 此專案至本機電腦

```
git clone https://github.com/WeiWayne1030/todolistSequelize.git
```

2. 開啟終端機(Terminal)，進入存放此專案的資料夾

```
cd todolistSequelize
```

3. 安裝 npm 套件

```
在 Terminal 輸入 npm install 指令
```

4.安裝 express 套件

```
在 Terminal 輸入 npm install express@4.16.4 指令
```

5. 安裝 nodemon 套件

```
在 Terminal 輸入 npm install -g nodemon
```

6. 啟動種子檔案

```
使用 npx sequelize db:seed:all 執行
```

7. 啟動伺服器，輸入執行專案

```
使用 npm run dev 執行
```

7. 當 terminal 出現以下字樣，表示伺服器已啟動並成功連結

```
Express is listening on http://localhost:3001
```
```
該種子資料會生成一位使用者，且擁有十個待辦事項。測試帳號如下： email: root@example.com password: 12345678
```
## Contributor - 專案開發人員

> [Wayne Sun]([https://github.com/WeiWayne1030])
