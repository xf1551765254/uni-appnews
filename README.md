
# 运行项目 

将 master 分之中的代码 clone 到本地

1. manifest.json 文件，重新获取 appid
2. cloudfunctions 目录，右键=》选择云服务空间（若不存在，则先创建）
3. cloudfunctions 目录下的 db_init.json 文件，右键=》初始化云数据库
4. cloudfunctions 目录，右键=》上传所有云函数
5. cloudfunctions 目录，右键=》打开 uniCloud Web 控制台，检查云函数和云数据库是否都有对应的数据
6. 在Web控制台，打开 user 表 ，复制第一行的 _id 
7. app.vue 中修改 user_id 为上述复制的 _id，确保请求正确的用户信息 
8. 运行到指定平台，查看效果

