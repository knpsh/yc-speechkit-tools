# SpeechKit Streaming Recognizer

Этот скрипт приведен для демонстрации потокового распознавания.

Скрипт записывает голос через микрофон и передает его на распознавание в сервис [SpeechKit](https://cloud.yandex.ru/services/speechkit), результат распознавания выводится в консоль.

Скрипт написан на Python поэтому может быть легко разобран, доработан и оптимизирован под ваш сценарий.

<br><br>

## Установка

xxx

## Использование

Необходимо [создать сервисную учетную запись](https://cloud.yandex.ru/docs/iam/operations/sa/create), а также – [назначить роль](https://cloud.yandex.ru/docs/iam/operations/sa/assign-role-for-sa) `ai.speechkit-stt.user`. 

Для созданной сервисной учетной записи необходимо получить [API-ключ](https://cloud.yandex.ru/docs/iam/operations/api-key/create), его секрет потребуется для запуска скрипта.

