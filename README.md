# Моя шпаргалка по git

# Команды git

Установка имени

``` 
$ git config --global user.name "User Namovich"
```

---

Установка электронной почты

``` 
$ git config --global user.email username@yandex.ru
```

---

Создание репозитория в папке

``` 
git init
```

---

Удалить репозиторий из папки 

``` 
rm -rf .git
```

---

Позволяет узнать статус проекта

``` 
git status
```

---

Добавляет файл в git

``` 
git add
```

---

Добавляет все файлы в git

``` 
git add --all
```

---

«Сделать коммит» (сохранить текущую версию файла.)

``` 
git commit -m
```

---

Просмотреть историю коммитов 

``` 
git log
```

---

Соединяет локальный репозиторий с репозиторием в облаке

``` 
git remote add origin
```

---

Показывает ссылку со связанным внешним репозиторием

``` 
Git remote -v
```

---

Отправить изменения на удалённый репозиторий (первый раз)

``` 
git push -u origin main
```

---

Второй и следующие пуши

``` 
git push
```

---

Клонировать репозиторий

``` 
git clone
```

---

Заменить ссылку на удаленный репозиторий

``` 
git remote set-url origin 
```

---

А работать с git вы можете научиться на курсах [ЯндексПрактикума](https://practicum.yandex.ru)

---