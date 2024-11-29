# Лабораторная работа №6
### Пункты № 1 - 6 задания
**GitHub перед началом работы уже был установлен и полностью настроен**
**Для начала создадим фаил в Githab:**

![создание файла](https://github.com/Slavarzhanov/LR6/blob/report/photo/%D1%81%D0%BE%D0%B7%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5%20%D1%84%D0%B0%D0%B9%D0%BB%D0%B0%20%D0%B2%20%D0%B3%D0%B8%D1%82%D1%85%D0%B0%D0%B1%D0%B5.png)

**До создания файла клонируем репозиторий:**


![конирование репозитория](https://github.com/Slavarzhanov/LR6/blob/report/photo/%D0%BA%D0%BB%D0%BE%D0%BD%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5%20%D1%80%D0%B5%D0%BF%D0%BE%D0%B7%D0%B8%D1%82%D0%BE%D1%80%D0%B8%D1%8F.png)

**Подтягиваем изменения с Githab и смотрим log**


![подтягивание изменений](https://github.com/Slavarzhanov/LR6/blob/report/photo/%D0%BF%D0%BE%D0%B4%D1%82%D1%8F%D0%B3%D0%B8%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5%20%D0%B8%D0%B7%D0%BC%D0%B5%D0%BD%D0%B5%D0%BD%D0%B8%D0%B9%20%D0%B8%20%D0%BB%D0%BE%D0%B3.png)

### Пункты № 7 - 9 задания.
**Смотрим какие у нас есть ветки и выполняем слияние и решаем возникший конфликт**

![Просмотр веток и слияние](https://github.com/Slavarzhanov/LR6/blob/report/photo/%D0%B2%D0%B5%D1%82%D0%BA%D0%B8%20%D0%B8%20%D1%81%D0%BB%D0%B8%D1%8F%D0%BD%D0%B8%D0%B5%20%D1%81%20%D1%80%D0%B5%D1%88%D0%B5%D0%BD%D0%B8%D0%B5%D0%BC.png)


### Пункты № 10-13 задания
**После слияния не забываем удалить ветку и изменяем наш файл**


![удаление ветки](https://github.com/Slavarzhanov/LR6/blob/report/photo/%D0%B8%D0%B7%D0%BC%D0%B5%D0%BD%D0%B5%D0%BD%D0%B8%D0%B5%20%D0%B8%20%D0%BE%D1%82%D0%BA%D0%B0%D1%82.png)


**Создаем комит и выполняем откат его и состояния файла**


![Комит и его откат](https://github.com/Slavarzhanov/LR6/blob/report/photo/%D0%BE%D1%82%D0%BA%D0%B0%D1%82%20-%202.png)

### Пункты № 14 - 15 задания
**Создаем ветку и папку для фото**


![Создание ветки и папки для фото](https://github.com/Slavarzhanov/LR6/blob/report/photo/%D1%81%D0%BE%D0%B7%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5%20%D0%B2%D0%B5%D1%82%D0%BA%D0%B8%20%D0%B8%20%D0%BF%D0%B0%D0%BF%D0%BA%D0%B8.png)

**Переходим к оформлению README:**


![Работа по оформлению README](https://github.com/Slavarzhanov/LR6/blob/report/photo/%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B0%20%D0%B2%20VSCode.png)

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
mkdir photo
```

### История операций в форматированном виде

![Отформатированый log](https://github.com/Slavarzhanov/LR6/blob/report/photo/%D1%82%D1%84%D0%BE%D1%80%D0%BC%D0%B0%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D1%8B%D0%B9%20%D0%BB%D0%BE%D0%B3.png)
