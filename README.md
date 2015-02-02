# ExpressHelloWorld
Hello World &amp; Some Tutorial of Express.js

Express 的初心者教學

# Install

Ref: [Installing - Express 官網](http://expressjs.com/starter/installing.html)

````
$ sudo npm install -g express
$ express my_app    # (-e)
$ cd my_app
$ sudo npm install
$ npm start   # 或是 node app.js
			  # 或是 env DEBUG=my_app ./bin/www
-> http://localhost:3000/ 
````

1. [Express小入門 - 使用EJS當模組](http://abc123634.github.io/2013/05/09/express%E5%B0%8F%E5%85%A5%E9%96%80/)
2. Terminal 會顯示 console.log() 輸出的訊息

# Structure

Ref: [Express 檔案目錄結構](http://blog.winwu.today/2013/04/nodejs-express-2-express.html)

- app.js: 網站核心設定檔。
- package.json: 管理這個 node.js project 用了哪些 package。當我們用 `express my_app`
產生了 express 的 project 之後，還要再用 `sudo npm install`　來安裝相依的 package,
這時候 npm 就是透過 package.json 來得知需要安裝哪些 package 的。
- Public 資料夾: `/images`, `/javascripts`, `/stylesheets` 分別用來放置、管理圖片、js、css檔。
- Routes 跟 Views 資料夾: Routes 用來管理網站 Routing 路徑，Views 放置相對應的前端網頁檔。

# Routing



# 應用
- [node.js教學－利用Express來寫HTTP伺服器](http://blog.allenchou.cc/nodejs-tuts-2-using-express-framework/)
- [用 Express 和 MongoDB 寫一個 todo list](http://dreamerslab.com/blog/tw/write-a-todo-list-with-express-and-mongodb/)
