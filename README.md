# notepad

A fullstack demo used Vue2 & Koa2(详细说明参见`项目笔记.md`).

![Todolist](http://7xog0l.com1.z0.glb.clouddn.com/vue-koa-demo/todolist-5.gif 'todolist')

View the [article](https://molunerfinn.com/Vue+Koa/) for more details.

## Install

`git clone https://github.com/aizhiheng/notepad.git`

`npm install` or `yarn`

Also you need to install MySQL & create a database named `todolist`,and execute 2 sql files `list.sql` & `user.sql`.Their are in `sql/`

After that, You need to change the password for mysql user. -> `server/config/db.js`

find `mysql://root:XXXX@localhost/todolist` and change the `XXXX` into your own password.

### Run

#### Development: 

`npm run dev` && `node app.js`

open browser: `localhost:8080`

#### Production:

`npm run build` and then `node app.js`

open browser: `localhost:8088`

注册的邮箱验证部分还在完善中

## License

[MIT](http://opensource.org/licenses/MIT)

Copyright (c) 2017 Molunerfinn


