# D1.3

1/1Задание для самостоятельной работы (HW-03)
Описание:

Мы продолжаем развивать наш интернет-магазин по продаже носков. В этом задании мы посмотрим, как Docker Swarm работает в облаке. Для этого мы создадим несколько серверов в Yandex.Cloud, установим туда Docker, объединим эти инстансы в кластер и задеплоим туда наш интернет-магазин по продаже носков.

После успешной инсталляции необходимо зайти по выделенному IP и убедиться, что наш проект доступен извне через браузер.

Для выполнения задания нужно использовать конфигурацию для Docker Compose из предыдущего задания. Некоторые директивы нужно модифицировать таким образом, чтобы сервисы запустились без ошибок в новом swarm-кластере.

Все инструкции по выполнению этого задания выполнены с помощью Terraform. Если у вас возникают сложности с выполнением, вы можете посмотреть решение. Можно выполнять задание любым удобным способом.

Задание:
Подготовить аккаунт в Yandex.Cloud.
Создать три инстанса в Yandex.Cloud:
Объединить их в сеть.
Добавить внешний IP для доступа к проекту через браузер.
Создать Docker Swarm кластер с одной управляющей нодой и двумя worker-нодами.
Задеплоить в swarm-кластер исправленный файл docker-compose.yml.
Проверить в браузере, что проект работает.
Масштабировать frontend-сервис до двух реплик.
Для проверки задания необходимо отправить:
Описание — каким образом и какие команды использовались для решения задания.
Скриншот страницы в браузере (главной страницы проекта, работающего в Yandex.Cloud).
Вывод команды docker service ls.
Вывод команды docker node ls.
Погасить проект.
Полезные ссылки:
Yandex.Cloud;
Getting started with swarm mode;
Microservices-demo на GitHub;
Sock Shop. A Microservices Demo Application;
Scale the service in the swarm.
123
