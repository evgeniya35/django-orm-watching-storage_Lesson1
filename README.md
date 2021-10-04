# Пульт охраны банка 

Показывает из базы данных информацию о посещениях сотрудниками хранилища.

**models.py** содержит описание моделей данных: Passcard - информация о ключах доступа. Visit - информация о посещениях хранилища. 
Функция **is_visit_long** при выводе информации о посещениях информирует о подозрительных посещениях (время посещения хранилища превышает 60 минут).

Скрипт **active_passcards_view.py** выводит список активных ключей доступа.

Скрипт **storage_information_view.py** выводит список находящихся в хранилище сотрудников.

Скрипт **passcard_info_view.py** выводит историю посещения сотрудником хранилища.
