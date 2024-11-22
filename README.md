# LR6
## Лабораторная работа №6
### 1) Добавляем файл с помощью интерфейса GitHub:
![screenshot](photo/image-1.png)

**после чего подтянем его в локальный репозиторий:**

![alt text](photo/image-2.png)
### 2) Просмотрим историю изменений:
![alt text](photo/image-3.png)
### 3) Посмотрим ветки:
![alt text](photo/image-4.png)
### 4) Производим слияние веток:
![alt text](photo/image-5.png)
### 5) Устраняем конфликт и удаляем ветку:
![alt text](photo/image-6.png)
### 6) Изменяем файл:
![alt text](photo/image-7.png)

**Делаем коммит:**

![alt text](photo/image-8.png)
### 7) Откатываем коммит:
![alt text](photo/image-9.png)

**откатываем также и файл:**

![alt text](photo/image-10.png)

### 8) Переходим к оформлению README для этого создаю папку которая будет хранить фото работы и сохраняю изменения:
![alt text](photo/image-12.png)

## Лог команд:
```
cd ... (смена текущей директории)
git clone ... (клонирование репозитория для локальной работы)
git pull (подтягивание изменений с гитхаба)
git log --all (просмотр истории изменений)
git branch -a (просмотр всех веток)
git merge origin/branch1 (автоматическое слияние веток)
git checkout --ours mergefile.txt (выбор текущей ветки как основной для определенного файла(в нашем случае это mergefile.txt))
git add mergefile.txt (добавление измененных файлов в следующий коммит)
git commit -m "..." (создание коммита с комментарием)
git push origin :branch1 (пуш изменений без ветки branch1)
echo "..." >>file.txt (запись данных в файл)
cat file.txt (просмотр содержимого файла)
git reset HEAD~1 (откат коммита назад на 1)
git status (просмотр состояния файлов в ветке(есть ли изменения))
git checkout -- file.txt (откат файла на 1 версию назад)
mkdir photo (создание директории)
```
## История операций в отформатированном виде:
![alt text](photo/image-13.png)
## Демонстрация оформления отчёта в README
![alt text](photo/image-14.png)