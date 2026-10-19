# 代码词典

规则：一行一条，只记「是什么 / 从哪来 / 传什么 / 返回什么」。不写心得。

- render(request, template, context) ｜ 把模板渲染成 HTML 返回 ｜ context 是传给模板的字典
- request ｜ Django 在视图函数执行前创建，代表这次 HTTP 请求 ｜ 含 method、GET、POST、user
- migrations ｜ 模型改动到数据库结构之间的迁移文件 ｜ 用 makemigrations 生成、migrate 执行
