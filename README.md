# Library-Web-Application
## Инструкция по запуску приложения

### Установка и запуск серверной части

1. Скачайте серверную часть приложения <a href="https://github.com/nikasuschinskaya/Library-Web-Application-Back"> **Library-Web-Application-Back** </a>
2. Для запуска проекта необходимо иметь следующие компоненты:
   - СУБД **MSSQL Server**
   - IDE **Visual Studio**
   - **.NET 8**
3. Откройте **Консоль диспетчера пакетов** в Visual Studio, выберите проект **Library.Infrastructure** и введите команду:
   
   ```bash
   Update-Database

В случае успешного выполнения будет создана база данных приложения. 

4. Далее запустите API. База данных заполнится при запуске API.

**ВАЖНО!** Администратор приложения создаётся через инициализатор. Ручная регистрация на клиенте для создания администратора невозможна.

Данные для входа администратора:
   - Email: nikaAdmin@gmail.com
   - Password: Nika2003!

### Установка и запуск клиентской части

5. Скачайте клиентскую часть приложения <a href="https://github.com/nikasuschinskaya/Library-Web-Application-Front"> **Library-Web-Application-Front** </a>
6. Для запуска проекта необходимо иметь Visual Studio Code.
7. Откройте терминал и введите команду:
   
   ```bash
   npm i

Это установит все модули проекта.

8. Далее введите команду:
   
    ```bash
   npm run dev

для запуска клиентской части приложения.

9. Нажмите Ctrl + щелчок на ссылку локального развертывания проекта.

<p align="center">
  <img src="https://github.com/user-attachments/assets/8baf1d32-5958-4e96-93f7-90226c79d372">
</p>

10. Войдите под администратором и протестируйте все функции приложения (или зарегистрируйте пользователя)

## Инструкция по эксплуатации приложения

1. Войдите как администратор

![image](https://github.com/user-attachments/assets/3154bfe4-90ec-46e4-8957-41db00eea25b)

2. Главная страница пользователя с книгами, взятыми из библиотеки пока что пуста

![image](https://github.com/user-attachments/assets/3fb5f71e-0dc0-4fc8-be8c-c6253decdf52)

4. Перейдите по вкладке "Каталог книг", где будут отображены все книги в библиотеке. Только для администратора кнопка "Добавить книгу." 

![image](https://github.com/user-attachments/assets/91137fd6-356a-4357-b60b-0c97fd2d4b7a)

5. Поиск книги по названию (для поиска нажмите на Enter или на кнопку "Поиск")

![image](https://github.com/user-attachments/assets/a5fcad46-64e1-4e91-8827-047ddfd9343a)

6. Фильтрация по жанру/автору 

![image](https://github.com/user-attachments/assets/d5f58cbe-ddcf-4c81-9304-abc7b6ad1f84)

7. Нажмите на карточку книги и отобразиться подробная информация по конкретной книге. Только для администратора кнопки "Редактировать" и "Удалить".

![image](https://github.com/user-attachments/assets/ee434fd6-54c7-488b-a9c4-a048015ff665)

8. При нажатии на кнопку "Взять книгу" кнопку заменит надпись и выбранная книга добавится на страницу пользователя в "Мои книги" 

![image](https://github.com/user-attachments/assets/2e6ea2fd-230f-4fc1-937b-682060402216)
![image](https://github.com/user-attachments/assets/f7d4e0f6-c0c8-45c0-a8e6-7a1a93986c64)

9. При нажатии на кнопку "Редактировать" открывается страница редактирования книги
    
![image](https://github.com/user-attachments/assets/7581d833-0f89-4233-a63e-67397389c020)

10. При нажатии на кнопку "Удалить" появляется модальное окно с подтверждением об удалении книги

![image](https://github.com/user-attachments/assets/67c99ab9-955f-4273-a95d-a2d1250c74cd)

11. При нажатии на кнопку "Добавить книгу" ткрывается страница добавления книги

![image](https://github.com/user-attachments/assets/ba692ec3-21c0-4afe-93e9-a27cc3802eb7)

12. В случае если у книги нет картинки, то можно добавить картинку, нажав на кнопку "+"

![image](https://github.com/user-attachments/assets/689a0504-668c-4f13-b6dc-9b21837033d9)

