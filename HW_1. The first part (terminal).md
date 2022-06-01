Окружение MAC OC

1. Посмотреть где я
```bash
pwd
```
2. Создать папку
```bash
mkdir papka
```
3. Зайти в папку
```bash
cd papka
```
4. Создать 3 папки
```bash
mkdir papka_1 papka_2 papka_3
```
5. Зайти в любоую папку
```bash
cd papka_1
```
6. Создать 5 файлов (3 txt, 2 json)
```bash
touch qwe_1.txt qwe_2.txt qwe_3.txt asd_1.json asd_2.json
```
7. Создать 3 папки
```bash
mkdir zxc_1 zxc_2 zxc_3
```
9. Вывести список содержимого папки
```bash
ls
```
10. Открыть любой txt файл
```bash
cat qwe_1.txt
```
11. Написать туда что-нибудь, любой текст.
```bash
nano qwe_1.txt #  написала что-то, сохранила CTRL+J, вышла CTRL+X, Y, ENTER
```
12. Сохранить и выйти. (пункт выше)
13. Выйти из папки на уровень выше
```bash
cd ..
```
14. Переместить любые 2 файла, которые вы создали, в любую другую папку.
```bash
mv qwe_1.txt qwe_2.txt zxc_1/
```
15. Скопировать любые 2 файла, которые вы создали, в любую другую папку.
```bash
cp asd_1.json asd_2.json zxc_1/
```
16. Найти файл по имени
```bash
find . -name "qwe_3.txt"
```
17. Просмотреть содержимое в реальном времени (команда grep) изучите как она работает.
```bash
cat qwe_1.txt
```
18. Вывести несколько первых строк из текстового файла
```bash
head -n 2 qwe_1.txt
```
19. Вывести несколько последних строк из текстового файла
```bash
tail -n 2 qwe_1.txt
```
20. Просмотреть содержимое длинного файла (команда less) изучите как она работает.
```bash
less qwe_1.txt
```
21. Вывести дату и время
```bash
date
```
=========

Задание *
1. Отправить http запрос на сервер.
http://162.55.220.72:5005/terminal-hw-request
```bash
curl http://162.55.220.72:5005/terminal-hw-request
curl http://162.55.220.72:5005/get_method\?name\=\(\Tatiana\)\&age\=\(33\)
```
2. Написать скрипт который выполнит автоматически пункты 3, 4, 5, 6, 7, 8, 13
```bash
mkdir -p dir_1 && cd dir_1 && mkdir folder_1 folder_2 folder_3 && cd folder_1 && touch bla_1.txt bla_2 bla_3 vbn_1.json vbn_2.json && mkdir qwe ewq weq && ll && mv *.json weq/
```
