# Домашнее задание к занятию «Что такое DevOps. СI/СD» Ожигов Иван
## Инструкция по выполнению домашнего задания

 1.Сделайте fork репозитория c шаблоном решения к себе в GitHub и переименуйте его по названию или номеру занятия, например, https://github.com/имя-вашего-репозитория/gitlab-hw или https://github.com/имя-вашего-репозитория/8-03-hw.  
 2.Выполните клонирование этого репозитория к себе на ПК с помощью команды git clone.  
 3.Выполните домашнее задание и заполните у себя локально этот файл README.md:  
    - впишите сверху название занятия, ваши фамилию и имя;  
    - в каждом задании добавьте решение в требуемом виде — текст, код, скриншоты, ссылка.  
    - для корректного добавления скриншотов используйте инструкцию «Как вставить скриншот в шаблон с решением»;  
    - при оформлении используйте возможности языка разметки md. Коротко об этом можно посмотреть в инструкции по MarkDown.  
 4.После завершения работы над домашним заданием сделайте коммит git commit -m "comment" и отправьте его на GitHub git push origin.  
 5.Для проверки домашнего задания в личном кабинете прикрепите и отправьте ссылку на решение в виде md-файла в вашем GitHub.  
 6.Любые вопросы по выполнению заданий задавайте в чате учебной группы или в разделе «Вопросы по заданию» в личном кабинете.  

 Желаем успехов в выполнении домашнего задания!
 
## Задание 1

### Что нужно сделать:

 1.Установите себе jenkins по инструкции из лекции или любым другим способом из официальной документации. Использовать Docker в этом задании нежелательно.  
 2.Установите на машину с jenkins golang.  
 3.Используя свой аккаунт на GitHub, сделайте себе форк репозитория. В этом же репозитории находится дополнительный материал для выполнения ДЗ.  
 4.Создайте в jenkins Freestyle Project, подключите получившийся репозиторий к нему и произведите запуск тестов и сборку проекта go test . и docker build ..

 В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки.

## Ответ
![alt text](https://github.com/IvanOzhigov/08-02-hw/blob/sckrin/1-1.png)
![alt text](https://github.com/IvanOzhigov/08-02-hw/blob/sckrin/1-2.png)
![alt text](https://github.com/IvanOzhigov/08-02-hw/blob/sckrin/1-3.png)
![alt text](https://github.com/IvanOzhigov/08-02-hw/blob/sckrin/1-4.png)
![alt text](https://github.com/IvanOzhigov/08-02-hw/blob/sckrin/1-5.png)
![alt text](https://github.com/IvanOzhigov/08-02-hw/blob/sckrin/1-6.png)
![alt text](https://github.com/IvanOzhigov/08-02-hw/blob/sckrin/1-7.png)
![alt text](https://github.com/IvanOzhigov/08-02-hw/blob/sckrin/1-8.png)
![alt text](https://github.com/IvanOzhigov/08-02-hw/blob/sckrin/1-9.png)

## Задание 2

### Что нужно сделать:

 1.Создайте новый проект pipeline.  
 2.Перепишите сборку из задания 1 на declarative в виде кода.

 В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки.

## Ответ
![alt text](https://github.com/IvanOzhigov/08-02-hw/blob/sckrin/2-1.png)
![alt text](https://github.com/IvanOzhigov/08-02-hw/blob/sckrin/2-2.png)
![alt text](https://github.com/IvanOzhigov/08-02-hw/blob/sckrin/2-3.png)
![alt text](https://github.com/IvanOzhigov/08-02-hw/blob/sckrin/2-4.png)
![alt text](https://github.com/IvanOzhigov/08-02-hw/blob/sckrin/2--5.png)

## Задание 3

### Что нужно сделать:

 1.Установите на машину Nexus.  
 2.Создайте raw-hosted репозиторий.  
 3.Измените pipeline так, чтобы вместо Docker-образа собирался бинарный go-файл. Команду можно скопировать из Dockerfile.  
 4.Загрузите файл в репозиторий с помощью jenkins.

 В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки.

## Ответ
![alt text](https://github.com/IvanOzhigov/08-02-hw/blob/sckrin/3-1.png)
![alt text](https://github.com/IvanOzhigov/08-02-hw/blob/sckrin/3-2.png)
![alt text](https://github.com/IvanOzhigov/08-02-hw/blob/sckrin/3-3.png)
![alt text](https://github.com/IvanOzhigov/08-02-hw/blob/sckrin/3-4.png)
