# Django

создать новый проект Django
```
django-admin startproject myproject .
```

запустить сервера разработки
```
python manage.py runserver
```

создать новое приложение
```
python manage.py startapp myapp
```

создать миграцию базы данных
```
python manage.py makemigrations
```

применить миграции базы данных
```
python manage.py migrate
```

создать суперпользователя
```
python manage.py createsuperuser
```

запустить оболочку Django
```
python manage.py shell
```



# Git/GitHub

добавить легкий тег "v1.4"
```
git tag v1.4
```

просмотреть все теги
```
git tag
```

добавить легкий тег "v1.4" для коммита "9fceb02"
```
git tag v1.4 9fceb02
```

отправить тег "v1.4" на удаленный репозиторий
```
git push origin v1.4
```

отправить все теги на удаленный репозиторий
```
git push origin --tags
```

удалить тег "v1.4"
```
git tag -d v1.4
```

удалить тег "v1.4" на удаленном репозитории
```
git push origin --delete v1.4
```

перейти к тегу "v1.2" (состояние "detached HEAD")
```
git checkout v1.2
```

начать новую ветку "version2" oт тега "v1.2" (для исправления багов в старых версиях)
```
git checkout -b version2 v1.2
```


