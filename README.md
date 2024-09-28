# 文件位置
## 前端文件
```
https://github.com/hanruoxiyu/childrenfriend-front.git
```
## 后端文件
```
https://github.com/hanruoxiyu/childrenfriend-back.git
```
  
# 使用方式
## 修改代码
```
// 前端 request.js

const service = axois.create({
  baseURL: 'http://0.0.0.0:8000/', 修改为服务器主机的代码
  timeout: 120000, // 请求超时时间
  changeOrigin: true,//是否允许跨越
})
```
```
// 后端 back/settings.py

DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.mysql',  # 数据库引擎
        'NAME': 'xitong',  # 数据库名称
        'HOST': '127.0.0.1',  # 数据库地址，本机 ip 地址 127.0.0.1
        'PORT': 3306,  # 端口
        'USER': 'root',  # 数据库用户名
        'PASSWORD': '1234',  # 数据库密码
    }
}
```
## 前端
```
npm install
npm run serve
```
## 后端
```
python manage.py runserver 本机地址:8000
```
  
# 服务器预览
```
http://10.10.10.44:3006/
```
