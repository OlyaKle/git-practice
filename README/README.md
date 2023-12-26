# Лабораторная работа 5
## Подготовка
ssh-keygen
cd ~/.ssh
-> git-ptactice
git clone git@github.com:cs-itmo-2023/git-ptactice.git
cd git-ptactice
## Здадание первое
touch example.txt
cat >> example.txt
втсавили стишок
ctrl + D
git add example.txt
git commit -m "File added example.txt"
git push origin main
## Здадание второе
git branch feature-branch
git checkout feature-branch
cat >> example.txt
show must go on
ctrl + D
git add example.txt
git commit -m "File added modified example.txt"
git push origin main
## Здадание третье
git checkout main
git merge feature-branch
git push origin main
картинки из терминала
картинка из гитхаба
## Здадание четвёртое
touch contents.txt
cat >> contents.txt
вставим предложенное оглавление
ctrl + D
git checkout -b feature-login
cat >> contents.txt
вставим предложенные изменения
ctrl + D
git add contents.txt
git commit -m "Добавлена глава 3: Вход в систему"
git push origin feature-login
картинки из терминала
## Здадание пятое
git checkout main
cat >> contents.txt
предложенные изменения
ctrl + D
git add contents.txt
git commit -m "Изменено название книги и введение"
git push origin main
картинка из терминала
git checkout feature-login
cat >> contents.txt
предложенные изменения
ctrl + D
git add contents.txt
git commit -m "Добавлен раздел о магии конфликтов"
git push origin feature-login
картинка с терминала
git checkout main
git pull origin main
cat >> contents.txt
предложенныое разрешение
ctrl + D
cat >> contents.txt
предложенные изменения
ctrl + D
git add contents.txt
git commit -m "Resolved conflict in chapter 2"
git push origin main
картинка с термнала
картинки с гитхаба
## Здадание шестое
## Здадание седьмое
