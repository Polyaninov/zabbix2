Домашнее задание к занятию 9.3 «Система мониторинга Zabbix. Часть 2» Полянинов Максим 

В практике есть 4 основных и 5 дополнительных (со звездочкой) заданий. Основные задания нужно выполнять обязательно, со звездочкой - по желанию и его решение никак не повлияет на получение вами зачета по этому домашнему заданию, при этом вы сможете глубже и/или шире разобраться в материале.

Пожалуйста, присылайте на проверку все задачи сразу. Любые вопросы по решению задавайте в чате учебной группы.

Цели задания
Научитья создавать свои шаблоны в Zabbix, добавлять в Zabbix хосты и связывать шаблон с хостами

Научиться составлять кастомный дашборд

Научиться создавать UserParameter на Bash

Научиться создавать Python-скрип, добавляться в него UserParameter и прикреплять к шаблону

Научиться создавать Vagrant-скрипты для Zabbix Agent

Чеклист готовности к домашнему заданию

 Просмотрите в личном кабинете занятие "Система мониторинга Zabbix. Часть 2"
 
Инструкция по выполнению домашнего задания

Сделайте fork репозитория c шаблоном решения к себе в Github и переименуйте его по названию или номеру занятия, например, https://github.com/имя-вашего-репозитория/gitlab-hw или https://github.com/имя-вашего-репозитория/8-03-hw).

Выполните клонирование этого репозитория к себе на ПК с помощью команды git clone.

Выполните домашнее задание и заполните у себя локально этот файл README.md:

впишите вверху название занятия и ваши фамилию и имя;

в каждом задании добавьте решение в требуемом виде: текст/код/скриншоты/ссылка;

для корректного добавления скриншотов воспользуйтесь инструкцией «Как вставить скриншот в шаблон с решением»;

при оформлении используйте возможности языка разметки md. Коротко об этом можно посмотреть в инструкции по MarkDown.

После завершения работы над домашним заданием сделайте коммит (git commit -m "comment") и отправьте его на Github (git push origin).

Для проверки домашнего задания преподавателем в личном кабинете прикрепите и отправьте ссылку на решение в виде md-файла в вашем Github.

Любые вопросы задавайте в чате учебной группы и/или в разделе «Вопросы по заданию» в личном кабинете.


Задание 1

Создайте свой шаблон, в котором будут элементы данных, мониторящие загрузку CPU и RAM хоста.

Процесс выполнения

Выполняя ДЗ сверяйтесь с процессом отражённым в записи лекции.

В веб-интерфейсе Zabbix Servera в разделе Templates создайте новый шаблон

Создайте Item который будет собирать информацию об загрузке CPU в процентах

Создайте Item который будет собирать информацию об загрузке RAM в процентах

Требования к результату

 Прикрепите в файл README.md скриншот страницы шаблона с названием «Задание 1»
 
 Ответ:
 
 ![Screenshot_17](https://user-images.githubusercontent.com/75700701/227310907-4d9320bc-c01c-48d5-ae8f-cf1c2b3e65bc.png)
 
 
 ![Screenshot_15](https://user-images.githubusercontent.com/75700701/227311150-1627a029-638b-442f-b7c7-fdf4a496e4d1.png)
 
 
 ![Screenshot_16](https://user-images.githubusercontent.com/75700701/227311624-14e42a78-d490-40e0-a062-3fdf5baa25cf.png)


Задание 3

Привяжите созданный шаблон к двум хостам. Также привяжите к обоим хостам шаблон Linux by Zabbix Agent.

Процесс выполнения

Выполняя ДЗ сверяйтесь с процессом отражённым в записи лекции.

Зайдите в настройки каждого хоста и в разделе Templates прикрепите к этому хосту ваш шаблон
Так же к каждому хосту привяжите шаблон Linux by Zabbix Agent

Проверьте что в раздел Latest Data начали поступать необходимые данные из вашего шаблона
Требования к результату

 Прикрепите в файл README.md скриншот страницы хостов, где будут видны привязки шаблонов с названиями «Задание 2-3». Хосты должны иметь зелёный статус подключения

 
 

 
 

 
 
 
 
 
 
 
 
