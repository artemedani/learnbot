Catbot
======

Catbot - это бот для Telegram

Установка
---------

Создайте виртуальное окружение и активируйте его и выполните:

.. code-block:: text

    pip install -r requirements.txt

Положите картинки в папку Images. Название файлов должно начинаться со screenshot и заканчиваться .jpg

Настройка
=========

Создайте файл Settings.py 

.. code-block:: python

PROXY = {'proxy_url': 'socks5://ВАШ_ПРОКСИ:1080',
         'urllib3_proxy_kwargs': {'username': 'ЛОГИН', 'password': 'ПАРОЛЬ'}}

API_KEY = "КЛЮЧ"

USER_EMOJI = [':smiley_cat:', ':smiling_imp:', ':panda_face:', ':dog:']

Запуск
======

В активированном виртуальном окружении выполните:

.. code-block:: text

    python3 bot.py



