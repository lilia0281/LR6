# Лабораторная работа №6: Система контроля версий
## Цель работы
Изучение базовых возможностей системы управления версиями, опыт работы с Git Api, опыт работы с локальным и удаленным репозиторием. 
## Ход работы
### 1. Создание аккаунта на сайте GitHub
![изображение](https://github.com/Natasikk/LR6/blob/Report/images/гит1.png)

### 2. Создание копии репозитория
![изображение](https://github.com/Natasikk/LR6/blob/Report/images/гит2.png)

### 4. Настройка клиента Git
```sh
git config --global user.email "liliadebil.2014@gmail.com"
git config --global user.name "Группа 4217 Мирошниченко Л.А."

```
![изображение](https://github.com/Natasikk/LR6/blob/Report/images/гит3.png)

### 5. Клонирование личного удалённого репозитория на компьютер
```sh
 git clone + [ссылка на репозиторий].

```
![изображение](https://github.com/Natasikk/LR6/blob/Report/images/гит4.png)

### 6. Добавление файла в удаленный репозиторий, подтягивание изменений
Добавила файл `New_file.txt` через интерфейс GitHub. Подтянула изменения в локальный репозиторий \
![изображение](https://github.com/Natasikk/LR6/blob/Report/images/гит4.png)
![изображение](https://github.com/Natasikk/LR6/blob/Report/images/гит5.png)

### 7. История операций для ветки master
```sh
git pull origin master
```
![изображение](https://github.com/Natasikk/LR6/blob/Report/images/гит6.png)

### 8. Слияние в ветку master и удаление побочной ветки
```sh
git checout master
git merge new-branch
git branch -d new-branch
```
![изображение](https://github.com/Natasikk/LR6/blob/Report/images/гит7.png)

### 9. Несколько изменений
```sh
git add New_file
git commit -m "Изменения1"
```
![изображение](https://github.com/Natasikk/LR6/blob/Report/images/гит20.png)
![изображение](https://github.com/Natasikk/LR6/blob/Report/Images/гит21.png)

### 10. Откат последнего коммита
```sh
git revert HEAD
```
![изображение](https://github.com/Natasikk/LR6/blob/Report/images/гит8.png)

### 11. Создание ветки для отчёта
```sh
git branch new_branch
```
![изображение](https://github.com/Natasikk/LR6/blob/Report/images/гит11.png)

### 12. История операций
```sh
git log
git log --pretty=format:"%h + %an + %an + %s".

```
![изображение](https://github.com/Natasikk/LR6/blob/Report/images/гит10.png)
![изображение](https://github.com/Natasikk/LR6/blob/Report/images/гит12.png)
![изображение](https://github.com/Natasikk/LR6/blob/Report/images/гит13.png)

### 13. Загрузка изменений в удалённый репозиторий
```sh
git push origin new_branch
```
![изображение](https://github.com/Natasikk/LR6/blob/Report/images/гит14.png)

## Вывод
В ходе данной лабораторной работы были изучены базовые возможности системы управления версиями и был получен опыт работы с Git Api, локальным и удаленным репозиторием.
