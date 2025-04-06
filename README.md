# Домашнее задание к занятию «Что такое DevOps. СI/СD»

# Климов Дмитрий

## Задание 1
Что нужно сделать:

1. Установите себе jenkins по инструкции из лекции или любым другим способом из официальной документации. Использовать Docker в этом задании нежелательно.
2. Установите на машину с jenkins golang.
3. Используя свой аккаунт на GitHub, сделайте себе форк репозитория. В этом же репозитории находится дополнительный материал для выполнения ДЗ.
4. lСоздайте в jenkins Freestyle Project, подключите получившийся репозиторий к нему и произведите запуск тестов и сборку проекта go test . и docker build ..
В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки.



## Ответ:

![Снимок экрана (704)](https://github.com/user-attachments/assets/5a5aaad0-9a8b-4c18-a9ae-24d307fd4bad)

![Снимок экрана (715)](https://github.com/user-attachments/assets/1df73a2e-9c7e-49d7-a19a-071f8b5c0075)

![Снимок экрана (716)](https://github.com/user-attachments/assets/ef9ec9f7-a8a6-4853-84a5-ec8dd4c16352)

![Снимок экрана (717)](https://github.com/user-attachments/assets/ff2f1a58-561f-41dd-a882-0492d04ae6e9)

![Снимок экрана (718)](https://github.com/user-attachments/assets/67ee0499-dafa-4a3a-9556-350f2fccfcde)

![Снимок экрана (719)](https://github.com/user-attachments/assets/ecde1f06-509e-4f30-8ac3-2595f9d77f17)

![Снимок экрана (720)](https://github.com/user-attachments/assets/1ce716c1-2e53-499b-a2d0-f620fb8b6fad)

![Снимок экрана (722)](https://github.com/user-attachments/assets/41055f2e-8dd5-4e6b-81a3-053ed273686b)

![Снимок экрана (721)](https://github.com/user-attachments/assets/f1cb3b58-61ce-4f80-beb5-e76188c4b7a9)



## Задание 2

Что нужно сделать:

Создайте новый проект pipeline.
Перепишите сборку из задания 1 на declarative в виде кода.
В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки.


![Снимок экрана (723)](https://github.com/user-attachments/assets/dd74b778-005a-481a-bf33-3732fb0a4400)

![Снимок экрана (725)](https://github.com/user-attachments/assets/7dafe407-3a56-4a4e-9634-d75ca5870a26)

![Снимок экрана (731)](https://github.com/user-attachments/assets/49c42fd3-a99b-405f-a192-983fe01ef6aa)

![Снимок экрана (738)](https://github.com/user-attachments/assets/ae8f97a4-bea5-47c3-b5cb-44fea8c8be40)

![Снимок экрана (739)](https://github.com/user-attachments/assets/c6fe5c1c-898e-4716-b6b4-d26fe9b161cf)

![Снимок экрана (732)](https://github.com/user-attachments/assets/90d97db1-a1f1-4f64-ae6b-b7eb54d7c063)

![Снимок экрана (733)](https://github.com/user-attachments/assets/b3f8f1c5-4611-4e0f-96dd-0fd6e6693d90)

![Снимок экрана (736)](https://github.com/user-attachments/assets/f4413e27-f256-424b-879b-8db90b3d0dce)

![Снимок экрана (737)](https://github.com/user-attachments/assets/04001f5e-b2ab-47b2-9446-859d0aeb278c)


## Задание 3
Что нужно сделать:

1. Установите на машину Nexus.
2. Создайте raw-hosted репозиторий.
3. Измените pipeline так, чтобы вместо Docker-образа собирался бинарный go-файл. Команду можно скопировать из Dockerfile.
4. Загрузите файл в репозиторий с помощью jenkins.
В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки.

