# Next juejin Blog

使用 Next 和掘金 api 搭建的个性博客

## 使用

Fork 本仓库后，新建`.env` 文件，写入 `uid=`, uid 值为掘金主页 url 上的 Id

修改 `src/config.js`

```js
export const config = {
  title: " InnozzZ",
  description: "分享 JavaScript 以及热门框架，记录前端工程师学习成长历程。",
  author: "InnozzZ",
  avatar:
    "https://p3-passport.byteimg.com/img/user-avatar/d6a270e545b3a8feee4556b8b2ddfa82~100x100.awebp",
  banner: "InnozzZ Blog",
};
```

## 部署

使用 GitHub 账户登录 https://vercel.com/ 导入这个项目， 即可部署成功
