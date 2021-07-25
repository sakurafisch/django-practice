# Django Practice

Django 官方教程走一波
当前进度：https://docs.djangoproject.com/en/3.2/intro/tutorial05/

## Init

### Windows

首次 `git clone` 后请执行 `init.bat`

每次打开工程，因为需要 venv，所以请执行 `ac.bat`

### Linux 

请根据 `*.bat` 文件自行编写脚本

## Start 

```cmd
python manage.py runserver 0.0.0.0:8000
```

## 修改 Model 的步骤

- Change your models (in `models.py`).
- Run [`python manage.py makemigrations`](https://docs.djangoproject.com/en/3.2/ref/django-admin/#django-admin-makemigrations) to create migrations for those changes
- Run [`python manage.py migrate`](https://docs.djangoproject.com/en/3.2/ref/django-admin/#django-admin-migrate) to apply those changes to the database.