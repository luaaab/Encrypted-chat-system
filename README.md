# Encrypted-chat-system
该项目是一个基于RSA加密的加密聊天系统，可以实现用户注册登录、加密聊天房间创建以及消息的加密发送与接收功能。

一、配置环境
（1）新建虚拟环境
conda create -n RSA python=3.8
（2）安装依赖库
pip install -r requirements.txt

二、运行说明
（1）建立数据库
python manage.py makemigrations
python manage.py migrate
（2）运行本地服务器
1）start the redis server:
	docker run -p 6379:6379 -d redis:6.2
2）Start the ASGI channels server: 
	python manage.py runserver

三、使用说明
各功能详细使用情况见screenshots
