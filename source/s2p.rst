s2p
===

s2p расшифровывается как *set to perl*.

Это программа написанная автром языка **perl** Ларри Уолом.
Она позволяет конвертировать **sed** скрипты в программы на языке
**perl**.

Установить s2p довольно просто. Введите в консоли.

.. code-block:: bash

 cpan install App::s2p

Программа установки будет задавать различные вопросы и предлагать
ответы по умолчанию. Приняв все дефолтные ответы и перелогинившись
мы получим установленную программу s2p в окружении пользователя.

Запуск s2p

.. code-block:: bash

 s2p -n 'sed скрипт' # sed -nre 'скрипт'
 # или
 s2p 'sed скрипт'  # sed -re 'скрипт'

s2p выведет на стандартный вывод код программы.