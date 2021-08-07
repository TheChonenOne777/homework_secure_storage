# Secure Storage

OTUS Репозиторий домашней работы по безопасности

### Задание 1. Реализуйте безопасное хранение auth token:

1. Обязательно реализуйте шифрование полученного токена авторизации `AES` алгоритмом
2. Предусмотрите безопасное хранение ключа
3. Обеспечьте поддержку API < 23

###### _Дополнительно_
4. Используйте максимально безопастный режим шифрование (не `ECB`)

### Задание 2. Реализуйте вход используя биометрию:

1. Релизуйте авторизацию в приложение через `BiometricPrompt`
2. Обеспечьте поддержку `STRONG` и `WEAK` биометрию
3. Добавьте поддержку темной темы в биометрии

###### _Дополнительно_
4. Добавьте возможность включать или отключать авторизацию через биометрию

##### Материаы, которыми можно пользоваться:

[otus_security](https://github.com/vitalyraevsky/otus_security)
[Документация по KeyStore](https://developer.android.com/training/articles/keystore)