# Домашняя работа №2. Telegram-бот для расчёта нормы воды, калорий и трекинга активности
@HW2_ConverterBot
## 1. Начало работы бота
![image](https://github.com/user-attachments/assets/3861ba02-4b04-45d3-b924-4c7879754d9d)

## 2. Вводим команду /help
![image](https://github.com/user-attachments/assets/1887b695-af84-4a03-85a0-ebf5de286cc2)

## 3. Пытаемся посмотреть данные профиля не создав его заранее
![image](https://github.com/user-attachments/assets/2f19eefc-f029-473b-8bae-839bad395026)

Аналогичное сообщение будет вылезать для всех кнопок

![image](https://github.com/user-attachments/assets/f73f9bca-0718-4302-8004-d8fab490e8cb)

## 4. Создаем профиль
При создании профиля есть некоторые ограничения для ввода данных. Например, имя должно содержать только буквы (на русском или на англиском языках). Также есть ограничения на возраст, вес, рост, время. Название города можно написать только на английском языке. Калории можно вводить или сделать расчет "по умолчанию".

![image](https://github.com/user-attachments/assets/1344eeba-465a-4e98-bf0d-5821934b507f)
![image](https://github.com/user-attachments/assets/1dd3ffe1-1c5a-4af2-8f58-55c1bdb7ff91)

Получились следующие данные:

![image](https://github.com/user-attachments/assets/3dbeedf0-79eb-4670-ba80-fd568410d231)

Как можно заметить, только после заполнения профиля появляются кнопки

## 5. Посмотрим на заполненный профиль. Пока что тут нет дополнительных данных
![image](https://github.com/user-attachments/assets/2b80159a-085b-46a2-85c2-04d8aa6c62e4)

## 6. Перейдем к кнопке "Вода"
Тут тоже есть свои ограничения для данных. Максимальное количество потребляемой воды связано с ограничениями организма.

![image](https://github.com/user-attachments/assets/927befce-ff3b-4882-a23e-86e87045735b)

## 7. Перейдем к кнопке "Еда"
Здесь есть ограничения для количества потребляемой еды.

![image](https://github.com/user-attachments/assets/1d74c76e-6656-435a-9f50-1614153dbe72)

Если еще раз нажать на эту кнопку, то калории будут суммироваться

![image](https://github.com/user-attachments/assets/93c8e9fd-fa72-4554-ab24-12c20e87853b)
![image](https://github.com/user-attachments/assets/29673dbc-a92b-4424-b09e-cc96b8c96fba)

## 8. Перейдем к кнопке "Тренировка"
Название тренировки можно ввести только на английском, есть ограничения на время.

![image](https://github.com/user-attachments/assets/35c847f9-77b4-4a8c-b50f-abf7600bd1fe)

Если еще раз нажать на эту кнопку, то дополнительная вода и сожженные калории будут суммироваться

![image](https://github.com/user-attachments/assets/95237b5d-7497-4851-8fd1-07e0569e02c5)

## 9. Еще раз посмотрим на профиль
В нем данные изменились

![image](https://github.com/user-attachments/assets/bfe2aa5d-fcc1-472d-8c2d-3d076534a2f8)


## 10. Еще зайдем в раздел "Вода"
![image](https://github.com/user-attachments/assets/378a1875-2c85-4633-bb5e-3f9cfbb8abc9)

После записи трениировок наши данные изменились. Теперь появилось сообщение о дополнительном количестве воды, которое нужно выпить

## 11. Посмотрим прогресс

![image](https://github.com/user-attachments/assets/5d7c30fe-c0e2-4d46-b1a0-4b401fd4e44c)
![image](https://github.com/user-attachments/assets/af1903b3-bd53-4fa7-824a-b45c6b318423)

## 12. Если заново нажать "Создать профиль", то мы начнем с чистого листа

![image](https://github.com/user-attachments/assets/9d7d97a5-f868-47f5-9218-9c8cd2e4d05b)
![image](https://github.com/user-attachments/assets/afc7c2c3-d116-43d6-b797-0a8e601652b9)

Если Выпить больше рассчитанной нормы, то появится предупреждение

![image](https://github.com/user-attachments/assets/51cb605d-64ba-4975-95cd-8fea2eb330c7)

Если выпить норму, то появится другое сообщение

![image](https://github.com/user-attachments/assets/d8e00a5b-0702-4a79-8628-7443e4d38033)

Теперь посмотрим какие графики полоучатся, если потраченных калорий будет больше съеденных

![image](https://github.com/user-attachments/assets/c371aa1b-592d-43c6-b428-e02edb463d0c)
![image](https://github.com/user-attachments/assets/78fdfb51-75e3-4ade-8175-7b362967ef01)



