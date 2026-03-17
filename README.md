# Домашнее задание к занятию «Защита хоста»
### Задание 1
Установите eCryptfs.
Добавьте пользователя cryptouser.
Зашифруйте домашний каталог пользователя с помощью eCryptfs.
В качестве ответа пришлите снимки экрана домашнего каталога пользователя с исходными и зашифрованными данными.

### Ответ:
Проверка созданно домашней папки пользователя cryptouser:
<img width="492" height="77" alt="image" src="https://github.com/user-attachments/assets/ddeec662-c545-4526-a1f4-ad4f743504d7" />

Переключение на пользователя cryptouser и создание файла:
<img width="730" height="223" alt="image" src="https://github.com/user-attachments/assets/50cc35b2-1544-4f25-8070-01a9f87db155" />

Проверка после шифрования: 
<img width="1053" height="265" alt="image" src="https://github.com/user-attachments/assets/c8974ea3-99f0-4b82-b1b6-b04fcf670f56" />


### Задание 2
Установите поддержку LUKS.
Создайте небольшой раздел, например, 100 Мб.
Зашифруйте созданный раздел с помощью LUKS.
В качестве ответа пришлите снимки экрана с поэтапным выполнением задания.

### Ответ:
Создание файла-раздела:
<img width="899" height="91" alt="image" src="https://github.com/user-attachments/assets/01d1ee9f-a5ca-4ec4-8073-102500e28be9" />

Создание LUKS контейнера 
<img width="849" height="243" alt="image" src="https://github.com/user-attachments/assets/5ddbe8ec-acd0-4fd0-b47f-1c975c81721d" />

Открытия раздела
<img width="842" height="178" alt="image" src="https://github.com/user-attachments/assets/34d56742-583a-4656-8f19-183c0ce7a131" />

Создание файловой системы:
<img width="799" height="250" alt="image" src="https://github.com/user-attachments/assets/01c4c09a-b02d-4298-a6d7-51387dee93aa" />

Выполнение монтирования:
<img width="873" height="266" alt="image" src="https://github.com/user-attachments/assets/07bf50e7-2d01-4dc3-b2e8-6c82e93128e6" />

Выполнение шифрования:
<img width="856" height="124" alt="image" src="https://github.com/user-attachments/assets/4f5311ab-42c9-40eb-8606-311d8ee576bf" />
