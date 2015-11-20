Introduction
============

相關套件
--------

-	[sails](http://sailsjs.org/)
-	[sequelize](http://docs.sequelizejs.com/en/latest/)

課程內容
--------

### async/await

### try/catch

### log level

### model CRUD

-	完成 User model CRUD 操作

### bootstrap

### service CRUD

-	若有 error catch 使用 throw
-	完成 UserService CRUD function

### controller CRUD

-	定義 routes
-	若有 error catch 使用 res.serverError
-	完成 UserController CRUD action

### login 實作

-	navbar 新增 login 按鈕
-	login 頁面實作

### sinon 使用

-	mock login success

### 使用 policies (before filter)

-	保護 controller
-	進入 controller 前，前置處理
-	使用者清單未登入不允許檢視 User 清單

### 使用 response (after filter)

-	根據不同狀況統一處理
-	資料出去前前置處理

作業
----

### User 註冊功能

-	spec 定義
	-	User 註冊功能
-	後端實作
	-	User 建立
-	前端實作
	-	註冊 User 表單
	-	navbar 新增註冊
	-	使用者登入後 navbar 註冊隱藏

### User 篩選功能

-	policies 定義
	-	未登入不允許使用此功能
	-	導入到 302 頁面
-	spec 定義
	-	篩選 User.username 功能
-	後端實作
	-	資料查詢
-	前端實作
	-	User 查詢 input

### Post 清單顯示

-	spec 定義
	-	Post 清單顯示
-	後端實作
	-	Post 查詢
-	前端實作
	-	navbar 新增 Post
	-	Post 清單頁面

### Post 建立

-	policies 定義
	-	未登入不允許使用此功能
	-	導入到 302 頁面
-	spec 定義
	-	mock 使用者已登入
	-	Post 建立必要歸屬於登入的 User
-	後端實作
	-	Post 建立
	-	將 Post 歸屬於登入的 User
-	前端實作
	-	Post 清單新增 Post 建立 link
	-	Post 建立表單

### Post 檢視

-	spec 定義
	-	透過 Post.id 檢視特定 Post
-	後端實作
	-	Post 查詢
-	前端實作
	-	Post 清單對每筆資料新增 link
	-	Post 檢視頁面

### Post 更新

-	policies 定義
	-	未登入不允許使用此功能
	-	導入到 302 頁面
-	spec 定義
	-	透過 Post.id 更新特定 Post
-	後端實作
	-	Post 更新功能
-	前端實作
	-	Post 檢視頁面新增修改 link
	-	新增 Post 更新表單

### Post 刪除

-	policies 定義
	-	未登入不允許使用此功能
	-	導入到 302 頁面
-	spec 定義
	-	Post 刪除功能
-	後端實作
	-	Post 刪除
-	前端實作
	-	Post 檢視時新增刪除 link
