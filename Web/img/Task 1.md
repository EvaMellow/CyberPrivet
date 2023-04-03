Цель: найти скрытые цифры
https://vuln-hunter.ru/task.zip

Последовательность:
Осмотреть сайт, найти https://vuln-hunter.ru/robots.txt
Там найти https://vuln-hunter.ru/password.txt
На этой странице есть пароль от архива, в архиве картинка, на ней ссылка на https://vuln-hunter.ru/welc0me_to_thhhe_club.
По ссылке страница вордпреса, там в коде страницы можно нати скрытый элемент, а в нём ссылка на https://vuln-hunter.ru/h0w_to_grep.txt
По этой ссылке надо скачать текстовый файл и отгрепать его.

Инструменты:
dirb/dirsearch
Инструменты разработчика и код элемента.
[grep](https://habr.com/ru/post/229501/)

Вводная статья