# webcode

Заряженный html без БД + w3css, 2018, версия 1 из 2.

Шаблон для образовательного или аналогичного сайта. 
База данных не задумывалась для использования в этом проекте.
При установке на свой сервер понадобится исправить путь BASE_URI в файле includes/initialize.php

Проект создавался с 27.08.2018 по 20.09.2018.
В проекте реализовывалась возможность максимально разделить внешний вид сайта от контента с целью лёгкого видоизменения внешнего вида в будущем. 
Также реализовывалась возможность безболезненного переноса любого файла с контентом или любого другого файла между папками в проекте: благодаря моему "ноухау" - файлу thislevel.php (насколько это новый, удачный и безопасный способ либо точно наоборот, судить не берусь).

Проект проходил проверку при параметре 
error_reporting = E_ALL
на серверах с PHP 5.6 и 7.1.
