# Django

## 0. setting
- `.gitignore`
- 가상환경 설정
- `README.md`


## 1. Django 프로젝트

1. Django 설치
```shell
pip install django
```

2. 프로젝트 생성
```shell
django-admin startproject {project_name} {path}
```

3. 서버 실행(종료: ctrl + c)
```shell
python manage.py runserver
```

4. 앱 생성
```shell
django-admin startapp {app_name}
```

5. 앱 등록(`settings.py` -> 'INSTALLED_APPS'에 app폴더명 추가)
```python
INSTALLED_APPS = [
    ...,
    '{app-name}',
]
```

- faker : 가짜 데이터를 생성해주는 library