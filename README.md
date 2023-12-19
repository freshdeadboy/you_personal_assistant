# Ваш особистий асистент

Це Python-додаток, який надає функціонал для управління адресною книгою, створення нотаток і сортування будь-якої теки з різними файлами. Додаток дозволяє керувати контактними записами, додавати та видаляти номери телефонів та електронні адреси, управляти днями народження та адресами, а також шукати записи за різними критеріями. Також ви можете створювати та управляти нотатками, додавати бажані теги і шукати нотатки за будь-яким ключовим словом або тегом. Нарешті, додаток може сортувати будь-яку теку з різними типами файлів в зручні підпапки, такі як зображення, відео, документи і т. д.

## Table of Contents

- [Функціонал](#функціонал)
- [Встановлення](#встановлення)
- [Використання](#використання)
- [Команди](#команди)

## Функціонал

### Управління Адресною Книгою

- Створення та управління контактними записами з наступною інформацією:
  - Ім'я
  - Номери телефонів
  - Електронні адреси
  - День народження
  - Адреса
- Редагування та видалення контактних записів.
- Додавання, редагування або видалення номерів телефонів та електронних адрес для контакту.
- Встановлення чи видалення дня народження для контакту.
- Встановлення чи видалення адреси для контакту.
- Пошук контактів за рядком пошуку.
- Перегляд надходжень днів народження протягом визначеної кількості днів.
- Перегляд усіх контактних записів.

### Управління Нотатками

- Створення та управління нотатками з вмістом та тегами.
- Пошук слів за будь-яким ключовим словом у назві або самій нотатці.
- Пошук нотаток за тегами.
- Перегляд усіх нотаток.
- Редагування або видалення нотаток.

### Сортування теки

- Сортування будь-якої теки "звалища" на підкатегорії, такі як ЗОБРАЖЕННЯ, ВІДЕО, АУДІО, ДОКУМЕНТИ, АРХІВИ та ІНШЕ

## Встановлення

 1. Завантажте наданий файл пакету your_personal_assistant.zip
 2. Розпакуйте архів
 3. Встановіть пакет, перейшовши в папку з попереднього кроку і використовуючи команду: ```pip install .```

## Використання

 1. Запустіть додаток, виконавши команду ```my_assistant``` в терміналі.

## Команди
Додаток підтримує наступні команди:

- add [Ім'я]: Створити новий контактний запис із зазначеним ім'ям.
- edit [Ім'я] [нове_Ім'я]: Змінити ім'я контактного запису.
- del [Ім'я]: Видалити контактний запис.
- add-phone [Ім'я] [Телефон]: Додати номер телефону до контакту.
- edit-phone [Ім'я] [Телефон] [новий_Телефон]: Замінити номер телефону у контакті.
- del-phone [Ім'я] [Телефон]: Видалити номер телефону з контакту.
- add-email [Ім'я] [Електронна_пошта]: Додати електронну адресу до контакту.
- edit-email [Ім'я] [Електронна_пошта] [нова_Електронна_пошта]: Замінити електронну адресу у контакті.
- del-email [Ім'я] [Електронна_пошта]: Видалити електронну адресу з контакту.
- birthday [Ім'я] [День_народження]: Встановити день народження для контакту.
- del-birthday [Ім'я]: Видалити день народження з контакту.
- address [Ім'я] [Адреса]: Встановити адресу для контакту.
- del-address [Ім'я]: Видалити адресу з контакту.
- find [рядок_пошуку]: Пошук контактних записів за рядком пошуку.
- help: Відображення списку доступних команд.
- add-note: Додати нотатку в Блокнот.
- all-notes: Перелічити всі нотатки
- del-note [Назва_нотатки]: Видалити нотатку з Блокнота
- add-tag [ID_нотатки] [Тег]: Додати тег до нотатки
- del-tag [ID_нотатки] [Тег]: Видалити тег з нотатки
- find-notes [рядок_пошуку]: Перелік всіх нотаток із даними рядка пошуку в нотатці та тегах
- find-tag [рядок_пошуку]: Перелік всіх нотаток із даними рядка пошуку в тегах
- sort-tag: Виводить список нотаток відсортований за кількістю тегів
- show-all-tags: Перелічити всі збережені теги
- next-birthdays [ціле_число]: Показати надходження днів народження протягом вказаної кількості днів.
- show-all: Перелічити всі контактні записи.
- close,exit або bye: Вийти з додатка.
