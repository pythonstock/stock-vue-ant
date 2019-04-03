
项目说明
----

-  使用 【 Ant Design Pro Vue 】 模板进行开发的。
-  人家的项目地址： https://github.com/sendya/ant-design-pro-vue
-  稍作修改，不更改主要的架构，这样方便进行更新组件。我只是实现我自己的项目逻辑。
-  页面在 src/views ，接口在 src/api 下面。


github提交
----

```

git init
git add README.md
git commit -m "first commit"
git remote add origin git@github.com:pythonstock/stock-vue-ant.git
git push -u origin master

```



项目修改
----

没有登录界面。要是以后有登录也是跳转sso登录，或者微信扫描登录。

- 【去掉权限，去掉登录页面之间进入系统】
- https://blog.csdn.net/freewebsys/article/details/88361751
- 【使用 ant-design-pro-vue 修改配置文件打包 ，去掉sourceMap，保证代码安全】
- https://blog.csdn.net/freewebsys/article/details/88703898

