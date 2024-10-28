# Library-Web-Application
Инструкция по запуску приложения

## Установка и запуск серверной части

1. Скачайте серверную часть приложения **Library-Web-Application-Back**.
2. Для запуска проекта необходимо иметь следующие компоненты:
   - СУБД **MSSQL Server**
   - IDE **Visual Studio**
   - **.NET 8**
3. Откройте **Консоль диспетчера пакетов** в Visual Studio, выберите проект **Library.Infrastructure** и введите команду:
   ```bash
   Update-Database
