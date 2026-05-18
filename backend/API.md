# API 设计
## 用户
### 认证
- `POST /auth/register` 注册
- `POST /auth/login` 登录
### 信息
- `GET /users/me` 获取当前登录用户的信息
- `PUT /users/me` 更改当前登录用户的信息
- `POST /users/change-password` 更改当前登录用户的密码
- `GET /users/{user_id}` 获取其他用户的公开信息

## 文章
- `POST /posts`
- `GET /posts/list`
- `GET /posts/{post_id}`
- `PUT /posts/{post_id}`
- `DELETE /post/{post_id}`