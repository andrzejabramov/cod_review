Задание №18: Код-ревью проекта 
После выполнения задания напишите об этом в телеграм t.me/python_backend_homework чтобы ваше задание было оперативно проверено 
Необходимо сделать код-ревью любого из указанных проектов (либо найти свой) 

https://github.com/artyomklg/fastapi-jwt-auth-example  
https://github.com/theshohidul/FastAPI-Boilerplate  
https://github.com/devbutlazy/LazyWeb  
https://github.com/emptybutton/Aqua/tree/main/services/backend  
https://github.com/Tishka17/fastapi-template (сложно)  
https://github.com/SamWarden/user_service (самый сложный проект, брать только при большой уверенности в своих знаниях) 

В код-ревью обязательно должны быть: 
Комментарии о том, какие участки кода для вас остались непонятными. Если вы не поняли, зачем что-то написано, сообщите об этом, выделив непонятные для вас строчки  — я помогу разобраться, и у вас улучшится понимание 
Общий комментарий ко всему проекту: Что нового я узнал(а) 
Общий комментарий ко всему проекту: Какой % кода мне понятен 

Code review — это не всегда простой и быстрый процесс. Если вы что-то не понимаете, попытайтесь сначала загуглить, зачем и почему так пишут код, и лишь в случае отсутствия в интернете ответа на ваш запрос пишите об этом в код-ревью. 
Как делается код-ревью? 
Если вкратце, то нужно создать pull request в GitHub (или merge request в GitLab), и сделать в нем ревью. 

Какой способ я предлагаю (вы можете использовать свой): 
1. Создать пустой публичный репозиторий на GitHub/GitLab 
2. Локально подключиться к этому репозиторию 
3. Закоммитить и запушить самый простенький файл в ветку main (можно пустой .gitignore файл) 
4. Ответвиться от текущей ветки в новую под названием review (можно создать новую ветку локально, а можно через сайт GitHub/GitLab) 
5. Переключиться на новую ветку review 
6. Скачать понравившийся вам репозиторий для код-ревью к себе локально в любую папку (через https/ssh/как zip архив) 
7. Поместить все файлы из скачанного репозитория в ваш локальный репозиторий (кроме папки .git, ее лучше удалить из скачанного репозитория, чтобы история коммитов была пустая) 
8. Добавить все файлы в индекс (git add), сделать коммит и запушить в ваш репозиторий в ветку review 
9. Создать pull request (PR) / merge request (MR) из ветки review в ветку main 
10. Внутри PR или MR провести code review и отправить его 
11. Приложить ссылку на PR / MR в задание 

А теперь покажу часть пунктов на картинках :) 

Весь процесс показывать не буду, так как вам нужна практика в работе с Git 

Пример моего PR: https://github.com/artemonsh/code_review/pull/1

Примеры PR учеников:
https://github.com/Dmitry178/project-review/pull/1
https://github.com/Derlngton/che-to-tam/pull/1
https://github.com/oleg-afonick/task_19/pull/1
В качестве примера я создал репозиторий code_review https://github.com/artemonsh/code_review

Сделал пустой коммит 