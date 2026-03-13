## Задание 1

### API 
<img width="1056" height="393" alt="image" src="https://github.com/user-attachments/assets/cc4c01d1-fae8-434e-a96e-f983b8be01ef" />

### Создание коллекции в Postman
для вывода всех пользователей
<img width="595" height="195" alt="image" src="https://github.com/user-attachments/assets/9127f585-2ffc-4b81-a782-8f9ae66aff7b" />

Вывод по конкретному id
<img width="591" height="224" alt="image" src="https://github.com/user-attachments/assets/ba2a2f68-6f95-4744-bb47-5aff5a805419" />

Вывод страницы
<img width="591" height="241" alt="image" src="https://github.com/user-attachments/assets/25c306dc-e58c-4167-b50e-f488f9732e4e" />

### Создание переменной для базового адреса выбранного API
<img width="582" height="188" alt="image" src="https://github.com/user-attachments/assets/0d3e28fc-5e23-4ceb-b6a2-9e3bf12abd6f" />

Обращение к переменной
<img width="602" height="216" alt="image" src="https://github.com/user-attachments/assets/edc5833a-5dec-4f56-a050-c300d0064249" />

### Написание простых тестов
Код ответа равен ожидаемому
<img width="386" height="77" alt="image" src="https://github.com/user-attachments/assets/083c7c31-dcfe-4996-8d34-a3e97fd97cf0" />

В теле ответа существует основное поле с данныим
<img width="320" height="95" alt="image" src="https://github.com/user-attachments/assets/6d83de8e-0ceb-4a05-aef1-dcc9e28d78e7" />

Время отклика меньше 500 мс
<img width="445" height="77" alt="image" src="https://github.com/user-attachments/assets/e3b9b541-62e7-424e-9f38-80566812875a" />

### Использование Collection Runner
<img width="833" height="726" alt="image" src="https://github.com/user-attachments/assets/1d981797-24ed-4523-be4f-d48715d88d76" />

## Задание 2

### Импорт готовой коллекции
<img width="185" height="129" alt="image" src="https://github.com/user-attachments/assets/a2ee7fa0-594e-49bd-8937-07d7628b04b3" />

### Настрока переменных
<img width="827" height="216" alt="image" src="https://github.com/user-attachments/assets/d16b1719-07a6-4a6e-bc9e-deb50b59fd28" />

### Структура коллекции ServerREST
<img width="263" height="613" alt="image" src="https://github.com/user-attachments/assets/078c2e8c-8394-450a-add5-fcebd7eb8a59" />

### Запуск базовых сценариев
<img width="832" height="723" alt="image" src="https://github.com/user-attachments/assets/488ee5c8-6424-43c1-ae7d-64908222cbd6" />

### Изучение автоматизированных тестов
<img width="825" height="856" alt="image" src="https://github.com/user-attachments/assets/599ae54a-9e44-4c74-86d9-52ca1a8e54bc" />

### Ошибочные сценарии

Запросы на создание пользователя с повторяющейся почтой и дальнейшее удаление. В втором тесте показано что статус кода = 400, ошибка создания пользователя.
<img width="828" height="302" alt="image" src="https://github.com/user-attachments/assets/6d1f64b4-873f-4f67-8d73-a77e5bf73c6e" />

Обновление почты, на ту, которая уже существует. Нельзя обновить почту на уже зарегестрированую. Ошибка в тесте Update User by ID 
<img width="780" height="605" alt="image" src="https://github.com/user-attachments/assets/8c02d161-461c-4999-831f-d1a1f37da931" />

Запрещено удалять пользователя с существующей корзиной. Ошибка в тесте Delete user by ID
<img width="777" height="503" alt="image" src="https://github.com/user-attachments/assets/0b8c4966-b248-47a4-8381-82eacc1c2d4d" />

Нельзя создать продукты с одинаковыми названиями. Ошибка в тесте Cadastrar produto com nome repetido
<img width="782" height="713" alt="image" src="https://github.com/user-attachments/assets/84339862-42a2-408a-8428-f154ea58394e" />

Нельзя удалить продукт, который был добавлен в корзину. Ошибка в тесте Delete product
<img width="785" height="764" alt="image" src="https://github.com/user-attachments/assets/35e27d4d-7434-4f9d-ad99-75899e4d9b1e" />

Неккоректный ввод ID. ID должен состоять из 16 символов(и буквы и цифры). Ошибка в тесте Update product
<img width="780" height="718" alt="image" src="https://github.com/user-attachments/assets/7cfa01b5-ef38-4892-9199-bc87cb8324b3" />

Ошибка создания больше 1 корзины. Ошибка в тесте Create cart 2 
<img width="781" height="519" alt="image" src="https://github.com/user-attachments/assets/da1d6077-d2b3-4e74-9022-058dd55ad2f1" />

## Задание 3

в запросах уже используется переменая baseUrl и дополнительные переменные (page, id, limit и т.п.). Созданы несколько наборов параметров, котореы были запущены через Collection Runner.



