# LR6
Лабораторная работа №6

**Цель лабораторной работы:** изучение базовых возможностей системы управления версиями, получение опыта работы с Git Api, опыта работы с локальным и удаленным репозиторием.

**Клонирование репозитория на компьютер**
![Клонирование репозитория на компьютер](/screenshots/clone_locally.png)

**Добавление файла в репозиторий средствами GitHub**
![Добавление файла в репозиторий средствами GitHub](/screenshots/adding_a_file.png)

**Подтягиваем изменения в локальный репозиторий**
![Подтягиваем изменения в локальный репозиторий](/screenshots/git_pull.png)

**История операций для ветки master**
![История операций для ветки master](/screenshots/git_log_master.png)

**[История операция для ветки branch1**
![История операция для ветки branch1](/screenshots/git_log_branch1.png)

**Разрешение конфликта слияния**
В процессе разрешения конфликта слияния было принято решение оставить **mergefile.txt** в том виде, в котором он был представлен в ветке **master**
![Разрешение конфликта слияния](/screenshots/merge_conflict_resolution.png)

**Коммит о слиянии веток**
![Коммит о слиянии веток](/screenshots/merge_commit.png)

**Удаление ветки**

![Удаление ветки](/screenshots/delete_branch1.png)

**Добавление папки со скриншотами в репозиторий**
![Добавление папки со скриншотами в репозиторий](/screenshots/screenshots_added.png)

**Создание ветки для отчёта**

![Создание ветки для отчёта](/screenshots/branch_report.png)

**Лог команд**
```
git clone https://github.com/tush00nka/LR6.git  - клонирование репозитория на компьютер
cd LR6/  - переход в папку репозитория
git pull  - подтягивание изменений
git log origin/branch1  - получение истории операций для ветки branch1
git merge branch1  - слияние с веткой branch1
git commit -m "Merged branch1"  - коммит об успешном слиянии
git branch --delete branch1  - удаление ветки branch1
mv ../Документы/3\\ semester/programming_basics/lab6/screenshots/ ./screenshots - добалвяем папку со скриншотами
git status  - получение статуса репозитория
git commit -m "screenshots folder added"  - коммит
vim the_file.txt  - изменение файла the_file.txt
git commit -m "the_file.txt modified"  - коммит
git revert 6bd43e0  - откат коммита
git commit -m "reverted the_file.txt modification"  - коммит об откате коммита
git branch report  - создание ветки для отчёта
git switch report  - переключение на ветку отчёта
```

**История операций**
```
84700ce 2024-09-19 tush00nka screenshot links fixed again
c3600f6 2024-09-19 tush00nka screenshot links fixed
a53a07b 2024-09-19 tush00nka all screenshots added to report
2a3964f 2024-09-19 tush00nka first screenshot
139a52d 2024-09-19 tush00nka reverted the_file.txt modification
6bd43e0 2024-09-19 tush00nka the_file.txt modified
3bbb5e4 2024-09-19 tush00nka screenshots folder added
f3bc9f4 2024-09-19 tush00nka Merged branch1
6198a08 2024-09-19 GitHub Create the_file.txt
921f53b 2020-11-21 GitHub Обновление информации
0f9f50d 2020-11-21 GitHub Заполнил файл
c08a654 2020-11-21 GitHub Файл создан пустым
3c6e913 2020-11-21 GitHub Initial commit
```

**Вывод**
Я изучил базовые возможности системы управления версиями, получил опыт работы с Git Api, опыт работы с локальным и удаленным репозиторием.
