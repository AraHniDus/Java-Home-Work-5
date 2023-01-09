# Домашняя работа Java Телефоный справочник
## 1. Задачя.
Реализовать телефонный справочник.
В справочнике есть фамилии и номера телефонов.
В справочнике обычно ищем номер по фамилии.
При этом могут быть однофамильцы -> за одной фамилией скрывается несколько номеров
## 2. Реализация.
Класс `Phonebook` реализует базу данный «Телефонный справочник»
БД постоена на основе контейнера `HashMap<String, String>`
в качестве ключа используется номер телефона в виде строку, а в качестве значения - фамилия
класс включает в себя метод main который запускает работу с БД
также включены методы:
* `addPB` - добавляет запись по заданным номеру телефона и фамилии
* `delPB` - удаляет запись по номеру телефона
* `savePB` - сохраняет БД в текстовом файле phone.txt
* `loadPB` - загружает БД из текстового файла phone.txt
* `PrintPhonebook` - выводит на екран все записи БД
* `FindSurname` - производит поиск фамилии по номеру телефона
* `FindNumberPhone` - производит поиск списка номеров по фамилии
