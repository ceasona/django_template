# Django Template

- 安装djangorestframework

  ```
  pip install djangorestframework
  ```

- 创建app

  ```
  cd api && django-admin startapp quickstart
  ```

- app中model文件有改变时, makemigrations, 生成sql语句

  ```
  python ../manage.py makemigrations snippets
  ```

- 执行sql

  ```
  python ../manage.py migrate snippets
  ```

- 创建admin

  ```
  python manage.py createsuperuser --email admin@example.com --username admin
  ```

  







python ../manage.py makemigrations snippets
python ../manage.py migrate snippets

python manage.py shell





参考资料：

1. [django-rest-framework官方教程](https://www.django-rest-framework.org/tutorial/quickstart/)
2. [django-视图集ViewSet](https://blog.csdn.net/qq_29286967/article/details/80921198)
3. [django官方文档](https://docs.djangoproject.com/zh-hans/2.0/topics/http/urls/)
4. [Gunicorn](https://docs.gunicorn.org/en/latest/run.html)
5. [uWSGI 托管 Django](https://docs.djangoproject.com/zh-hans/3.0/howto/deployment/wsgi/uwsgi/)
6. [Django request_id](https://github.com/dabapps/django-log-request-id)
7. [Django logger](https://docs.djangoproject.com/zh-hans/4.0/howto/logging/#logging-how-to)
8. [DjangoRestFramework 使用 django-oauth-toolkit](https://blog.csdn.net/css_aaa/article/details/118651288)
