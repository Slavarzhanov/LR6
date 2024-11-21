# Лабораторная работа №6
### Пункты № 1 - 6 задания
**Для начала создадим фаил в Githab:**


![создание файла](image.png)

**До создания файла клонируем репозиторий:**


![конирование репозитория](image.png)

**Подтягиваем изменения с Githab**


![подтягивание изменений](image.png)

### Пункты № 7 - 10 задания.
**Смотрим какие у нас есть ветки и выполняем слияние и решаем возникший конфликт**

![Просмотр веток и слияние](image.png)


**После слияния не забываем удалить ветку**


![удаление ветки](image.png)

### Пункты № 11-13 задания
**Изменению файла**


![Изменение файла и создание комита](image.png)

**Создаем комит и выполняем откат его и состояния файла**


![Комит и его откат](image.png)

### Пункты № 14 - 15 задания
**Создаем ветку и папку для фото**


![Создание ветки и папки для фото](image.png)

**Переходим к оформлению README для этого создаю папку которая будет хранить фото работы и сохраняю изменения:**


![Работа по оформлению README](image.png)

### Лог команд
**Последовательность используемых команд:**

```
cd ...
git clone ...
git pull
git log --all
git branch -a
git merge origin/branch1
git checkout --ours mergefile.txt
git add mergefile.txt
git commit -m "..."
git push origin :branch1
echo "..." >>file.txt
cat file.txt
git reset HEAD~1
git status
git checkout -- file.txt
mkdir photo_laba
```

### История операций в форматированном виде

