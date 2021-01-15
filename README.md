# Краткое описание
 Совместимость приложения KeyValidator c Java 11, Функциональное тестирование приложения KeyValidator на основе предоставленных для тестирования валидных и не валидных ключей
#### Дата начала: 20.12.20
#### Дата окончания: 20.12.20

На тестирование затрачено: 1 час.

### В результате тестирования выявлены следующие дефекты:
1. Ключи из списка валидных оказались невалидными:
* 80b427f8-92cd-3aae-ba04-3927fbe17c6
* 387eedc6-12e9-3b32-9881-63b6b5e85317
2. ключи из списка невалидных оказались валидными:
* 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1

* Заведены два Баг-репорта:
1. [Невалидный ключ проходит валидацию](https://github.com/friklen/KeyValidator-/issues/2#issue-772371962)
2. [Валидный ключ не проходит валидацию](https://github.com/friklen/KeyValidator-/issues/1#issue-772367266)

### Описание процесса тестирования
1. Скачать OpenJDK11 в соответствии с инструкцией по установке [OpenJDK11](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/openjdk11-manual.md)
2. Протестировать установку OpenJDK11 через терминал, используя команду java -version
3. Скачать приложение [KeyValidator.class](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md) из руководсва польвания
4. Создать локальный репозиторий, добавить в него файл с приложением KeyValidator
5. Запустить в терминале приложение KeyValidator командой java KeyValidator  предоставленные для валидации ключи
6. Проверить предоставленные для тестирования ключи валидации, фиксируя результаты для валидных ключей - ОК, для невалидных - FAIL

[В качестве тестовых данных использовались данные ключи валидации ](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md)



### Тестирование производилост в следующем окружении:
*  Ноутбук Xiaomi Mi Air
* Windows 10 Домашняя x64
* версия Java 11.0.9.1
* IntelliJ IDEA
