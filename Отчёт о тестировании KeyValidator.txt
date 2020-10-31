# Отчёт о тестировании KeyValidator

## Краткое описание

31.10.2020 - 31.10.2020 было проведено функциональное тестрование приложения KeyValidator.

На тестирование затрачено: 2 часа

В результате тестирования выявлены следующие дефекты:
* https://github.com/mkorolkova311/-1---KeyValidator/issues/1
* https://github.com/mkorolkova311/-1---KeyValidator/issues/2
* https://github.com/mkorolkova311/-1---KeyValidator/issues/3

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* Руководство использования KeyValidator
* Тест кейс
* Баг-репорты


В качестве тестовых данных использовались данные Руководства использования KeyValidator:
* 8f05e6a7-70e9-33d7-bfe7-b19eae0d8998 OK
* 80b427f8-92cd-3aae-ba04-3927fbe17c6 OK
* b295bc63-9f03-3b4b-af80-969b39f8c262 OK
* 387eedc6-12e9-3b32-9881-63b6b5e85317 OK
* c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180 OK

* 18252235-78e0-44a5-8720-556f0c7da17a FAIL
* e66075b6-ddad-445e-baf6-161b3289522b FAIL
* b6d53250-f07e-4352-a293-6102ddf7f1ca FAIL
* c2bc778a-1cb9-46c6-b435-0489649d2a42 FAIL
* 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1 FAIL


Тестирование производилось в следующем окружении:
* MINGW64_NT-6.3-9600 SONY 3.1.6-340.x86_64 2020-07-09 14:33 UTC x86_64 Msys
* OpenJDK11
