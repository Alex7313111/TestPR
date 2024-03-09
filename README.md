# PullRequest
В своем аккаунте не GitHub создать копию репозитория из другого аккаунта с помощью кнопки **Fork**

# Привет Github! 
![Git Logo](git_logo.JPG)
# Работа с Git
## 1. Проверка наличия установленного Git
В терминале набрать команду 
```
git --version
```
Если Git установлен, появится сообщение с информацией о версии программы, иначе будет сообщение об ошибке.
## 2. Установка Git
Загружаем последнюю версию программы с
 [сайта](https://git-scm.com/downloads)
 Устанавливаем с настройками по умолчанию.
## 3. Настройка Git
 При первом использовании Git необходимо представиться.
Для этого нужно ввести в терминале 2 команды:
```
git config --global user.name «Ваше имя английскими буквами»
```
```
git config --global user.email ваша почта@example.com
```
## 4. Инициализация репозитория 
 Для инициализации репозитория необходимо ввести команду: 
 ```
 git init
 ```
## 5. Запись изменений репозитория 
 Для записи изменений репозитория необходимо использовать команду:
 ```
 git commit -am "Комментарий"
 ```
## 6. Просмотр изменений репозитория 
 Для просмотра истории всех коммитов с их хеш-кодами необходимо использовать команду:
 ```
 git log
 ```
## 7. Перемещение между коммитами
Для переходамот одного коммита к другому необходимо использовать команду:
```
git checkout "хэш коммита"
``` 
Чтобы перейти в ветку master, после просмотра другого сохарнения, необходимо использовать команду:
```
git switch
```
либо:
```
git checkout master
```
## 8. Игнорирование файлов
Для того, чтобы исключить из отслеживания в репозитории определенные файлы или папки необходимо создать файл ***.gitignor*** и записать в него названия или шаблоны, соответствующие таким файлам или папкам например:
```
*.JPG
/название папки
```
## 9. Создание веток в Git
По умолчанию имя основной ветки в Git *master*.
Создать ветку можно командой: 
```bash
git brach <имя новой ветки>
```
Список веток в репозитории можно посмотреть командой 
```bash
git branch
```
## 10. Удаление веток в Git
Для удаления веток необходимо использовать команду: 
```
git branch -d <имя ветки, которую необходимо удалить>
```
Для принудительного удаления необходимо использовать команду:
```bash
git branch -D <имя ветки, которую необходимо удалить>
```
## 11. Cлияние веток в Git
Для того, чтобы совершить слияние двух веток, можно использовать команду:
```bash
git merge <имя ветки, c которой нужно совершить слияние>
```
