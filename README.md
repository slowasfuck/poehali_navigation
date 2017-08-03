**Система навигации для дрона с помощью двух веб-камер и opencv**

*Установка:*
- два ноутбука с веб-камерами, смотрящими на поле перпендикулярно друг другу
- дрон с бортовым компьютером и мигающей лентой
- общая локальная сеть для трех компьютеров

*Программа:*
- на 2х компьютерах запускаем camera_client.py (один из них обозначить как left в шапке python-файла)
- на дроне запускаем drone_server.py

drone_server расчитывает свои координаты на основе принимаемых данных

*Как протестить:*
Запустить в разных терминалах оба файла
