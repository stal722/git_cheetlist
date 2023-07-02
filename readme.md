## Список команд для работы в Git

1. Инициализация локального репозитория

```
git init

```

2. Определения состояния файлов в репозитории

```
git status

```

3. Добавление файлов в версионный контроль

```
git add <название_файла>
git add --all
git add .

```

4. Создание коммита 

```
git commit -m "Сообщение описывающее изменения"

```

5. Синхронизация локального и удаленного репозитория

```
git remote add origin git@github.com:<название_аккаунта>/<название_репозитория>.git

```

6. Отправка изменений в удаленный репозиторий (используется при отправке изменений в репозиторий, далее можно использовать git push)

```
git push -u origin master

``` 
